#### Test 5615109389cecbd_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1949): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/GAV2    ( 4710): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  964): Killing 4149:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 1 tasks}
D/dalvikvm( 1949): GC_CONCURRENT freed 1668K, 22% free 19433K/24832K, paused 4ms+5ms, total 61ms
D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1949): fetch service done; releasing wakelock
I/ConfigFetchService( 1949): stopping self
D/AndroidRuntime( 4753): 
D/AndroidRuntime( 4753): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4753): CheckJNI is OFF
D/dalvikvm( 4753): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4753): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4753): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4753): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4753): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4753): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4753): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4753): failed to load memtrack module: -2
I/Icing   ( 1949): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4753): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4753
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (121 us)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2}
D/Icing   ( 1949): Loaded CLD2 Version V2.0 - 20141016
D/dalvikvm(  964): GC_FOR_ALLOC freed 24288K, 54% free 28006K/59844K, paused 112ms, total 112ms
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{432ffc18 stackId=1, 2 tasks}
D/AndroidRuntime( 4753): Shutting down VM
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/SlideAside( 4136): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/UsbSettingsControl( 2624): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2624): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4753): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 1ms
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4779 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4136): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4136): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4779): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1949): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4779): Binding Chromium to the background looper Looper (main, tid 1) {427f3c98}
I/chromium( 4779): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4779): Initializing chromium process, renderers=0
W/chromium( 4779): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4779): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4779): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4779): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4779): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4779): Remote Branch: 
I/Adreno-EGL( 4779): Local Patches: 
I/Adreno-EGL( 4779): Reconstruct Branch: 
I/dalvikvm( 4779): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4779): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4779): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4779): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4779): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4779): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4779): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4779): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4779): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4779): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4779): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4779): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4779): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4779): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4779): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4779): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4779): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4779): Enabling debug mode 0
W/AwContents( 4779): nativeOnDraw failed; clearing to background color.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/InputMethodManagerService(  964): IME STATUS OFF
W/AwContents( 4779): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +442ms
I/ActivityManager( 4779): Timeline: Activity_idle id: android.os.BinderProxy@427f5378 time:120141
D/JsMessageQueue( 4779): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4779): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427f9890
D/dalvikvm( 4779): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427f9890
D/jxcore_app_log( 4779): JniHelper::setJavaVM(0x416be838), pthread_self() = 1632251272
D/JX-Cordova( 4779): jxcore cordova android initializing
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024020033, nextTick: 59999, mDrawingTime: 0
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024020036, nextTick: 59997, mDrawingTime: 0
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} time:120454
D/ActivityManager(  964): no-history finish of ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{43203020 ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2624): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4779): GC_CONCURRENT freed 2682K, 12% free 21970K/24832K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 338K, 10% free 22357K/24832K, paused 38ms, total 38ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.047MB for 42652-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 104K, 11% free 22364K/24876K, paused 36ms, total 36ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 126K, 11% free 22384K/24876K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.125MB for 95956-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 178K, 11% free 22419K/24972K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.205MB for 143930-byte allocation
,W/PluginManager( 4779): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2040): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/dalvikvm( 4779): GC_FOR_ALLOC freed 254K, 11% free 22467K/25116K, paused 24ms, total 24ms
I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.319MB for 215890-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 367K, 12% free 22541K/25328K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.495MB for 323830-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 567K, 12% free 22661K/25648K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.766MB for 485740-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 862K, 13% free 22837K/26124K, paused 25ms, total 26ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 1118K, 12% free 23077K/26124K, paused 24ms, total 24ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 211K, 12% free 23042K/26124K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 25.717MB for 1092904-byte allocation
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/dalvikvm( 4779): GC_CONCURRENT freed 1802K, 14% free 23523K/27192K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 207K, 14% free 23395K/27192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 26.583MB for 1639352-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 1934K, 17% free 24033K/28796K, paused 2ms+3ms, total 41ms
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 972K, 17% free 23980K/28796K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 27.937MB for 2459024-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 417K, 16% free 26350K/31200K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 4081K, 20% free 25014K/31200K, paused 36ms, total 37ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 30.119MB for 3688532-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 371K, 19% free 28532K/34804K, paused 3ms+4ms, total 63ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 4390K, 25% free 26124K/34804K, paused 40ms, total 40ms
,W/jxcore-log( 4779): Initializing JXcore engine
,W/jxcore-log( 4779): JXcore engine is ready
,D/dalvikvm( 4779): GC_CONCURRENT freed 402K, 17% free 28942K/34804K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 4779): Starting JXcore engine
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,W/jxcore-log( 4779): Platform android
W/jxcore-log( 4779): 
W/jxcore-log( 4779): Process ARCH arm
W/jxcore-log( 4779): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/jxcore-log( 4779): JXcore Cordova bridge is ready!
I/jxcore-log( 4779): 
,W/jxcore-log( 4779): JXcore engine is started
,I/chromium( 4779): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4779): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4779): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4779): Toggling radios to true
I/jxcore-log( 4779): 
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431894f8:true
,D/BluetoothAdapter( 4779): enable(): BT is already enabled..!
D/WifiService(  964): New client listening to asynchronous messages
D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2040): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2040): wlan0: Cancelling scan request
D/wpa_supplicant( 2040): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2040): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2040): TDLS: Tear down peers
,D/wpa_supplicant( 2040): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4779): Radios toggled
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): My device name is: LGE-LG-D802
I/jxcore-log( 4779): 
D/WifiService(  964): setWifiEnabled: true pid=4779, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4779, uid=10304
D/WifiService(  964): reconnect pid=4779, uid=10304
,D/wpa_supplicant( 2040): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2040): wlan0: Deauthentication notification
D/wpa_supplicant( 2040): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2040): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
,I/wpa_supplicant( 2040): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2040): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2040): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2040): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7f0dd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2040):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2040): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2040): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: External notification - portValid=0
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2040): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2040): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2040): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2040): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2040): nl80211: Event message available
D/wpa_supplicant( 2040): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2040): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2040): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2040): Fast associate: Old scan results
D/wpa_supplicant( 2040): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2040): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2040): wlan0: nl80211: scan request
D/wpa_supplicant( 2040): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2040): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiNative-wlan0(  964):    returned true
D/wpa_supplicant( 2040): nl80211: Event message available
D/wpa_supplicant( 2040): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2040): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2040): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2040): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2040): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/QCNEA   (  491): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  491): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  491): |CAC| updateNetCfgInfo
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC|                   Netconfig               
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  491): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  491): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  491): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  491): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  491): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  491): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| Received bssid= 
D/QCNEA   (  491): |CAC| net type = 3
V/QCNEA   (  491): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  491): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  491): |CAC| 	ssid           =NG700
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  491): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  491): |CAC| dispatchNetCfg: updating:0xb88408dc
D/QCNEA   (  491): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  964): hidePasspointNotification off =false
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4828 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
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
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
V/        (  264): RouteController
D/WifiStateMachine(  964): handleMessage: X
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4828): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4828): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4828): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,W/NetworkManagementService(  964): route cmd failed: 
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x61e9a5d0 clazz=0x6cf00001 iface=wlan0 mask=0x3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/PCSuite ( 4828): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4828): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1518): Read error: ssl=0x63971120: I/O error during system call, Connection timed out
,V/NativeCrypto( 1518): SSL shutdown failed: ssl=0x63971120: I/O error during system call, Broken pipe
W/ProcessCpuTracker(  964): Skipping unknown process pid 4848
W/ProcessCpuTracker(  964): Skipping unknown process pid 4849
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4863 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  964): Killing 4282:com.google.android.talk/u0a77 (adj 15): empty #17
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QRemote ( 4863): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4863): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4863): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4863): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4863): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4863): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4863): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4863): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4863): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 4386:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,I/GAV2    ( 4710): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1518): onDestroy
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.443665 Y: -0.406921 Z: 9.786407 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443665 .y:-0.406921 .z:9.786407
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.446625 Y: -0.411560 Z: 9.780396 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446625 .y:-0.411560 .z:9.780396
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4779): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4779): 
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4107): onReceive
,D/AppUp4:CustFacade( 4107): Context : android.app.ReceiverRestrictedContext@42810468
D/AppUp4:CustFacade( 4107): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4107): isOpenOperator : true
,D/AppUp4:CustFacade( 4107): isPhone : true
I/LicenseContentProvider( 3051): start selecting data
,D/SIMObserver( 3051): simInfo1
,I/AppUp4:EulaManager( 4107): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4107): begin check event
,I/AppUp4:CustModeStarterReceiver( 4107): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4892 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2040): nl80211: Event message available
D/wpa_supplicant( 2040): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2040): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2040): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2040): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 2040): nl80211: Survey data missing
D/wpa_supplicant( 2040): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2040): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 2040): wlan0: New scan results available
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2040): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2040): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2040): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2040): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2040): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2040): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2040): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2040): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2040): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2040): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2040): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2040): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2040): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7f0f5a8  current_ssid=0x0
D/wpa_supplicant( 2040): scard is not null..
D/wpa_supplicant( 2040): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2040): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2040): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2040): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2040): wlan0: Cancelling scan request
D/wpa_supplicant( 2040): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2040): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2040): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2040): RSN: PMKSA cache search - network_ctx=0xb7f0f5a8 try_opportunistic=0
D/wpa_supplicant( 2040): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2040): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2040): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2040): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2040): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2040): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2040): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2040): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2040): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2040): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2040): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2040): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2040): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2040): nl80211: Unsubscribe mgmt frames handle 0xb7f0e590 (mode change)
D/wpa_supplicant( 2040): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2040): nl80211: Register frame type=0xd0 nl_handle=0xb7f0e590
D/wpa_supplicant( 2040): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2040): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2040):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040):   * freq=2412
D/wpa_supplicant( 2040):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2040):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040):   * Auth Type 0
D/wpa_supplicant( 2040):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2040): nl80211: Connect request send successfully
D/wpa_supplicant( 2040): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2040): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2040): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2040): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
V/DownloadManager( 4892): DownloadService onCreate
D/EAS     ( 4693): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4693): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4693): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4892): in removeSpuriousFiles
I/LgeMiscReceiver( 4460): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4460): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4460): networkInfo.isConnected() = false
V/DownloadManager( 4892): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4283a750 on behalf of 4892
I/DownloadManager( 4892): in trimDatabase
D/wpa_supplicant( 2040): nl80211: Event message available
D/wpa_supplicant( 2040): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2040): nl80211: Connect event
D/wpa_supplicant( 2040): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2040): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2040): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2040): wlan0: Association info event
D/wpa_supplicant( 2040): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2040): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2040): wlan0: freq=2412 MHz
D/wpa_supplicant( 2040): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2040): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2040): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2040): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2040): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): scard is not null..
D/wpa_supplicant( 2040): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2040): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2040): TDLS: Remove peers on association
D/wpa_supplicant( 2040): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2040): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2040): EAPOL: enable timer tick
D/wpa_supplicant( 2040): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2040): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2040): wlan0: Cancelling scan request
D/wpa_supplicant( 2040): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
V/DownloadManager( 4892): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4283c0e0 on behalf of 4892
V/DownloadManager( 4892): DownloadService onStartCommand
V/DownloadManager( 4892): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/linker  ( 4693): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4922 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4693): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4693): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4693): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4283e3b0 on behalf of 4892
D/HyLog   ( 4922): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/dalvikvm( 4693): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HyLog   ( 4922): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4922): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HtmlEditor( 4693): register_HtmlEditor, Success
D/HtmlEditor( 4693): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4693): register_HtmlEditorTimer, Success
D/HtmlEditor( 4693): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4693): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4693): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4693): register_HtmlEditorFont, Success
D/HtmlEditor( 4693): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4693): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4693): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4693): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4693): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4693): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4693): JNI_OnLoad Success
V/DownloadManager( 4892): DownloadService onDestroy
I/HubEmail( 4693): JNI_OnLoad()
I/HubEmail( 4693): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4693): registerNatives()
I/HubEmail( 4693): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4693): registerNativeMethods()
I/HubEmail( 4693): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2040): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 ...
D/wpa_supplicant( 2040): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2040): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2040): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2040): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2040): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2040):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2040):   key_nonce - hexdump(len=32): ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 a9 d4 e2 02 d8 78 31 3c 44 71 d2 d3 ca 0c d0 d1 58
D/wpa_supplicant( 2040):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 ...
D/wpa_supplicant( 2040): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2040): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2040): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2040): Get randomness: len=32 entropy=7
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
D/wpa_supplicant( 2040): WPA: Renewed SNonce - hexdump(len=32): e9 1d 7c cb a3 2e 99 cf 41 22 96 2f 26 21 2d 54 db e3 de f4 85 b5 ce 3f 84 c8 b5 ea 2d 67 61 d0
D/wpa_supplicant( 2040): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): WPA: Nonce1 - hexdump(len=32): e9 1d 7c cb a3 2e 99 cf 41 22 96 2f 26 21 2d 54 db e3 de f4 85 b5 ce 3f 84 c8 b5 ea 2d 67 61 d0
D/wpa_supplicant( 2040): WPA: Nonce2 - hexdump(len=32): ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 a9 d4 e2 02 d8 78 31 3c 44 71 d2 d3 ca 0c d0 d1 58
D/wpa_supplicant( 2040): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2040): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2040): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2040): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2040): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2040): WPA: Derived Key MIC - hexdump(len=16): e2 b3 a2 fa bc 0f a8 ed f8 c1 c4 65 39 7b 34 a4
D/wpa_supplicant( 2040): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e9 1d 7c cb a3 2e 99 cf 41 22 96 2f 26 21 2d ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/ActivityManager(  964): Killing 4008:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
V/LGRssiData( 4922): [loadRssi] File not exist 
V/LGRssiData( 4922): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4922): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4922): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4922): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4922): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4922): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
D/MobileConnectivityChangeReceiver( 4922): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 4922): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4922): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4922): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4922): onReceive CONNECTIVITY_CHANGE networkType=1
D/wpa_supplicant( 2040): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 ...
D/wpa_supplicant( 2040): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2040): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2040): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2040): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2040):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2040):   key_nonce - hexdump(len=32): ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 a9 d4 e2 02 d8 78 31 3c 44 71 d2 d3 ca 0c d0 d1 58
D/wpa_supplicant( 2040):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_rsc - hexdump(len=8): cf c7 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2040):   key_mic - hexdump(len=16): 76 2b b2 53 08 c8 93 c7 64 6d 93 8a c3 84 7d da
D/wpa_supplicant( 2040): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ef 69 ce 10 7a 98 43 12 3c 51 27 bc 33 53 34 ...
D/wpa_supplicant( 2040): RSN: encrypted key data - hexdump(len=56): 95 e5 d2 56 64 27 98 b2 3a 59 14 c4 85 00 0f 47 e9 c0 72 05 3c 23 44 f7 fe b0 67 a6 1b 85 9f 02 ...
D/wpa_supplicant( 2040): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2040): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2040): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2040): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e0 fe ...
D/wpa_supplicant( 2040): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2040): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2040): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2040): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2040): WPA: Derived Key MIC - hexdump(len=16): 79 99 5d cf a6 8d e5 7e 1d 52 c3 49 10 6c 9e e1
D/wpa_supplicant( 2040): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2040): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7f0ec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2040):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2040): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2040): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6,f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2040): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2040): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2040): WPA: RSC - hexdump(len=6): cf c7 00 00 00 00
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5a03a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2040):    broadcast key
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 2040): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2040): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2040): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2040): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2040): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
E/PhoneMonitor( 4922): onOtaspChanged old =0, new =3
D/wpa_supplicant( 2040): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2040): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2040): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2040): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2040): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2040): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2040): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2040): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2040): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2040): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2040): EAPOL authentication completed successfully
D/wpa_supplicant( 2040): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2040): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2040): nl80211: if_removed already cleared - ignore event
V/PhoneMonitor( 4922): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4939 uid=10063 gids={50063, 3003, 1028, 1015}
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/Wi,fiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2040): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
I/jxcore-log( 4779): Test app app.js loaded
I/jxcore-log( 4779): 
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
I/ActivityManager(  964): Killing 4446:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
I/Choreographer( 4779): Skipped 207 frames!  The application may be doing too much work on its main thread.
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
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@431dfa50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@43005708 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  964): ObtainingIpState{ when=-14ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-12ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2040): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-14ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
I/chromium( 4779): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4952 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  964): Killing 4617:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4952): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2936): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Killing 4650:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4965 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/LGDMClient( 2936): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2040): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2040): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2040): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431b3038 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431b3038 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/HyLog   ( 4965): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/HyLog   ( 4965): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/HyLog   ( 4965): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2040): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2040): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2040): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/LGDMSGCM( 4965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
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
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
E/Parcel  (  491): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): handleMessage: E msg.what=135190
E/Parcel  (  491): Reading a NULL string not supported here.
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
E/Parcel  (  491): Reading a NULL string not supported here.
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
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4980 uid=10101 gids={50101, 1028, 1015, 3003}
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  964): Killing 4679:com.lge.bnr/1000 (adj 15): empty #17
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 22ms
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 14ms
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4980): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
,D/dalvikvm(  964): GC_CONCURRENT freed 1207K, 51% free 29689K/59844K, paused 5ms+5ms, total 93ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 65ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 61ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 64ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 58ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 55ms
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,I/NFS     ( 4980): connectivityManager.getNetworkInfo = TYPE_WIFI
,V/        (  264): RouteController
,I/Wireless_Storage( 4980): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4980): intf.getDisplayName() = lo
I/Wireless_Storage( 4980): intf.getDisplayName() = sit0
I/Wireless_Storage( 4980): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4980): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4980): intf.getDisplayName() = wlan0
V/        (  264): RouteController
D/NFS     ( 4980): interface name:wlan0 name:wlan0
D/NFS     ( 4980): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 4980): interface name:wlan0 name:wlan0
V/        (  264): RouteController
D/NFS     ( 4980): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4980): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4999 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4316:com.android.contacts/u0a21 (adj 15): empty #17
V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4999): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4999): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4999): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  264): RouteController
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  491): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  491): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  491): |CAC| updateNetCfgInfo
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC|                   Netconfig               
V/QCNEA   (  491): |CAC| *********************************************
V/QCNEA   (  491): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  491): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  491): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  491): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  491): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  491): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  491): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  491): |CAC| net type = 1
V/QCNEA   (  491): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  491): |CAC| Received ssid= NG700
V/QCNEA   (  491): |CAC| 	ssid           =NG700
V/QCNEA   (  491): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  491): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  491): |CAC| *********************************************
D/QCNEA   (  491): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  491): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  491): |CAC| dispatchNetCfg: updating:0xb88408dc
D/QCNEA   (  491): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1949): Checking schedule, now: 1453024026679 next: 1453023962457
,I/CheckinService( 1949): active receiver: enabled
,W/GAV2    ( 4999): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinService( 1949): Preparing to send checkin request
,I/EventLogService( 1949): Accumulating logs since 1453023928794
,I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1518): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1518): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1518): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1518): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1518): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromium( 4999): Binding Chromium to the main looper Looper (main, tid 1) {427f1410}
,I/chromium( 4999): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4999): Initializing chromium process, renderers=0
,W/chromium( 4999): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4999): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4999): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4999): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4999): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4999): Remote Branch: 
I/Adreno-EGL( 4999): Local Patches: 
I/Adreno-EGL( 4999): Reconstruct Branch: 
,I/Auth    ( 1518): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1949): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x432869c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
I/NSApplication( 4999): Starting up...
,I/ActivityManager(  964): Killing 4330:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5070 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
,D/HyLog   ( 5070): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5070): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5070): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4863): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4863): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4863): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/dalvikvm( 5070): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5070): VFY: replacing opcode 0x60 at 0x000b
,I/QRemote ( 4863): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 5070): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5070): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5070): VFY: replacing opcode 0x62 at 0x005e
,D/QRemote ( 4863): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4863): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4828): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/MultiDex( 5070): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5070): install
,I/MultiDex( 5070): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/PCSuite ( 4828): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4863): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4863): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4863): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4863): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/MultiDex( 5070): loading existing secondary dex files
,I/MultiDex( 5070): load found 3 secondary dex files
,I/MultiDex( 5070): install done
,D/dalvikvm( 5070): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5070): VFY: unable to resolve instance field 61
,D/dalvikvm( 5070): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5070): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5070): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5070): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5070): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5070): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5070): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5070): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5070): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5070): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f92d8
,D/dalvikvm( 5070): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f92d8
,D/dalvikvm( 5070): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f92d8, skipping init
D/dalvikvm( 5070): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f92d8
D/dalvikvm( 5070): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f92d8
,V/JNIHelp ( 5070): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5070): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427f92d8
,D/dalvikvm( 5070): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427f92d8
D/dalvikvm( 5070): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427f92d8
,D/dalvikvm( 5070): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427f92d8
,I/ProviderInstaller( 5070): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1518): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1518): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1518): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1949): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1843): callingUid 10006, callindPid: 1843
,E/MDM     ( 1425): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 5070): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5070): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5070): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5070): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5070): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5070): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1949): Restart initialization of location
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff0000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff0000
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
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2215624302
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5070): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429c4250
,D/dalvikvm( 5070): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429c4250
,D/dalvikvm( 5070): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429c4250, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/wpa_supplicant( 2040): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2040): EAPOL: disable timer tick
,I/WVCdm   (  271): CdmEngine::OpenSession
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=3846490189
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
D/dalvikvm( 5070): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
D/dalvikvm( 5094): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
D/dalvikvm( 5070): DexOpt: --- END 'f.apk' (success) ---
D/dalvikvm( 5070): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 86ms
I/Adreno-EGL( 5070): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5070): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5070): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5070): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5070): Remote Branch: 
I/Adreno-EGL( 5070): Local Patches: 
I/Adreno-EGL( 5070): Reconstruct Branch: 
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/WifiStateMachine(  964): handleMessage: X
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Adreno-EGL( 5070): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5070): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5070): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5070): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5070): Remote Branch: 
I/Adreno-EGL( 5070): Local Patches: 
I/Adreno-EGL( 5070): Reconstruct Branch: 
I/Adreno-EGL( 5070): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5070): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5070): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5070): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5070): Remote Branch: 
I/Adreno-EGL( 5070): Local Patches: 
I/Adreno-EGL( 5070): Reconstruct Branch: 
W/Settings( 5070): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/CheckinRequestBuilder( 1949): Classify the device as Phone.
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/CheckinTask( 1949): Sending checkin request (11595 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1518): GC_EXPLICIT freed 965K, 29% free 17847K/24832K, paused 7ms+7ms, total 70ms
,D/GCM     ( 1518): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1518): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1518): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1518): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1518): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1518): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1518): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1518): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x432810d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1949): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1949): Classify the device as Phone.
,I/CheckinTask( 1949): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1949): Checking schedule, now: 1453024028981 next: 1453601424977
,I/CheckinService( 1949): active receiver: disabled
,D/dalvikvm( 1949): GC_CONCURRENT freed 1887K, 22% free 19533K/24832K, paused 4ms+4ms, total 48ms
,D/GCM     ( 1518): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2040): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4107): onReceive
,D/AppUp4:CustFacade( 4107): Context : android.app.ReceiverRestrictedContext@42810468
,D/AppUp4:CustFacade( 4107): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4107): isOpenOperator : true
,D/AppUp4:CustFacade( 4107): isPhone : true
,I/LicenseContentProvider( 3051): start selecting data
,D/SIMObserver( 3051): simInfo1
,I/AppUp4:EulaManager( 4107): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4107): begin check event
,I/AppUp4:CustModeStarterReceiver( 4107): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4107): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4107): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4107): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4107): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4107): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4892): DownloadService onCreate
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4693): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4460): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4460): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4460): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4922): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4922): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4892): in removeSpuriousFiles
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@42844248 on behalf of 4892
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4892): in trimDatabase
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LGDMClient( 2936): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@428458b0 on behalf of 4892
,D/LGDMSGCM( 4965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2936): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2936): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/Tethering(  964): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4892): DownloadService onStartCommand
V/DownloadManager( 4892): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/NFS     ( 4980): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4980): CONNECT : WIFI_CONNECT
E/LGDMClient( 2936): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@42847db0 on behalf of 4892
D/LGDMClient( 2936): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2936): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2936): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4892): DownloadService onDestroy
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4107): onReceive
,D/AppUp4:CustFacade( 4107): Context : android.app.ReceiverRestrictedContext@42810468
D/AppUp4:CustFacade( 4107): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4107): isOpenOperator : true
,D/AppUp4:CustFacade( 4107): isPhone : true
,I/LicenseContentProvider( 3051): start selecting data
,D/SIMObserver( 3051): simInfo1
,I/AppUp4:EulaManager( 4107): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4107): begin check event
,I/AppUp4:CustModeStarterReceiver( 4107): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4892): DownloadService onCreate
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4892): in removeSpuriousFiles
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4284c590 on behalf of 4892
,I/DownloadManager( 4892): in trimDatabase
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/LgeMiscReceiver( 4460): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4460): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4284da70 on behalf of 4892
I/LgeMiscReceiver( 4460): networkInfo.isConnected() = true
D/PhoneState( 4460): setPdpRejectCasuse : false
,W/Settings( 4693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4892): DownloadService onStartCommand
,V/DownloadManager( 4892): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4922): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4922): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@4284fb60 on behalf of 4892
,V/DownloadManager( 4892): DownloadService onDestroy
,D/LGDMClient( 2936): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2936): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2936): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  964): GC_EXPLICIT freed 2115K, 51% free 29711K/59844K, paused 2ms+6ms, total 82ms
,E/LGDMClient( 2936): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/NFS     ( 4980): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4980): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2936): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2936): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2936): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4107): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4107): onReceive
,D/AppUp4:CustFacade( 4107): Context : android.app.ReceiverRestrictedContext@42810468
,D/AppUp4:CustFacade( 4107): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4107): isOpenOperator : true
,D/AppUp4:CustFacade( 4107): isPhone : true
,I/LicenseContentProvider( 3051): start selecting data
,D/SIMObserver( 3051): simInfo1
,I/AppUp4:EulaManager( 4107): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4107): begin check event
,I/AppUp4:CustModeStarterReceiver( 4107): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4693): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4892): DownloadService onCreate
,I/LgeMiscReceiver( 4460): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4460): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4460): networkInfo.isConnected() = true
,D/PhoneState( 4460): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4922): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4922): onReceive CONNECTIVITY_CHANGE networkType=1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4892): in removeSpuriousFiles
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@42853ce8 on behalf of 4892
,D/LGDMClient( 2936): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4892): in trimDatabase
,V/DownloadManager( 4892): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@42854db8 on behalf of 4892
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/LGDMClient( 2936): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/LGDMClient( 2936): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMSGCM( 4965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/WifiController(  964): battery changed pluggedType: 2
,W/ContextImpl( 4965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2936): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2936): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2936): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 4980): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4980): CONNECT : WIFI_CONNECT
I/LGDMClient( 2936): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,V/DownloadManager( 4892): DownloadService onStartCommand
,V/DownloadManager( 4892): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4892): created cursor android.database.sqlite.SQLiteCursor@42857890 on behalf of 4892
,V/DownloadManager( 4892): DownloadService onDestroy
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/GAV2    ( 4999): Thread[GAThread,5,main]: No campaign data found.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2040): nl80211: survey data missing!
,E/Parcel  (  491): Reading a NULL string not supported here.
,E/Parcel  (  491): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Killing 4710:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/Finsky  ( 4348): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4348): [1] 5.onFinished: Installation state replication succeeded.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2040): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5233 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4136): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 4136): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mmsto"
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
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
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Babel   ( 5233): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5233): MmsConfig.loadMmsSettings
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/MediaCodecList( 5233): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5233): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5233): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5233): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5233): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5233): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5233): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5233): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/GmsNetworkLocationProvi( 1425): DISABLE
W/BaseRuntimeLoader( 5233): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5233): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5233): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5233): MmsConfig.loadFromResources
,E/Babel   ( 5233): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5233): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5233): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5233): [loadRssi] File not exist 
V/LGRssiData( 5233): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5233): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5233): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5233): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5233): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4107): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4107): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4107): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4107): onReceive
D/AppUp4:CustFacade( 4107): Context : android.app.ReceiverRestrictedContext@42810468
D/AppUp4:CustFacade( 4107): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4107): isOpenOperator : true
,D/AppUp4:CustFacade( 4107): isPhone : true
,I/LicenseContentProvider( 3051): start selecting data
,D/SIMObserver( 3051): simInfo1
,I/AppUp4:EulaManager( 4107): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4107): begin check event
D/AppUp4:Utils( 4107): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4107): Event For Nothing, skip.
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5280 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5280): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5280): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5280): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5280): BUILD Country: EU
,I/SystemConfig( 5280): BUILD Operator: OPEN
I/ActivityManager(  964): Killing 4828:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5296 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
I/SystemConfig( 5280): systemFeature RCS result false
D/SystemConfig( 5280): refreshRcsSupport() :false
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.467834 Y: -0.424072 Z: 9.801193 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467834 .y:-0.424072 .z:9.801193
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/ActivityManager(  964): Killing 4863:com.lge.qremote/u0a96 (adj 15): empty #17
,D/HyLog   ( 5296): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5296): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5296): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.467133 Y: -0.412872 Z: 9.792328 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467133 .y:-0.412872 .z:9.792328
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/ActivityManager(  964): Killing 4892:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2693): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1949): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1949): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{444fec08 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1949): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/IcingCorporaProvider( 2693): UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] 
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9937 usec
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
D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.446442 Y: -0.411835 Z: 9.783096 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446442 .y:-0.411835 .z:9.783096
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.468018 Y: -0.431946 Z: 9.803894 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468018 .y:-0.431946 .z:9.803894
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  481): sns_pwr.c(292):acquiring wakelock
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.445480 Y: -0.423309 Z: 9.800690 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445480 .y:-0.423309 .z:9.800690
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.455643 Y: -0.416779 Z: 9.807388 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455643 .y:-0.416779 .z:9.807388
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.462112 Y: -0.414917 Z: 9.808609 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462112 .y:-0.414917 .z:9.808609
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.459427 Y: -0.415100 Z: 9.792542 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459427 .y:-0.415100 .z:9.792542
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43cec738)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
I/WindowManager(  964): No lock screen! windowToken=null
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb8c6d450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.461121 Y: -0.416779 Z: 9.792160 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461121 .y:-0.416779 .z:9.792160
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
,D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2040): wlan0: Control interface command 'SIGNAL_POLL'
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/wpa_supplicant( 2040): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2040): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2040): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
,V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
,D/WeatherAncestor( 1891): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:47:18
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43185758 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,E/SlideAside( 4136): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 4136): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1891): 2 : This is isUpdating : false
,D/WeatherAncestor( 1891): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:47:18
D/WeatherService( 1891): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
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
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 397ms
D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024038442, nextTick: 41590, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024038495, nextTick: 41538, mDrawingTime: 0
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/WeatherService( 1891): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:47:18
,D/WeatherService( 1891): 2 : ACTION screen on
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,D/WeatherService( 1891): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:47:18
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.473312 Y: -0.409912 Z: 9.810196 
D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473312 .y:-0.409912 .z:9.810196
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/LGImmersionVibrator(  964): Vibrator off
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/wpa_supplicant( 2040): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/wpa_supplicant( 2040): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
,V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
D/UsbSettings( 2624): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
V/UsbSettings( 2624): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2624): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2624): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4324aa70 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 1 tasks}
,D/wpa_supplicant( 2040): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/VolumeVibrator( 1155): clear
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1891): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:47:18
D/WeatherService( 1891): 2 : ACTION screen off
,D/WeatherService( 1891): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:47:18
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
E/Parcel  (  491): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/dalvikvm( 1463): GC_CONCURRENT freed 1541K, 7% free 25440K/27280K, paused 1ms+1ms, total 12ms
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Sensors (  481): sns_pwr.c(320):releasing wakelock
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,I/GAV4    ( 5233): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024056285911722; DSPS: 5272844; Offset: 1453023895371483012
,I/GoogleURLConnFactory( 1518): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1518): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1518): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1518): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1518): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1518): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1518): No account for auth token provided
,W/Uploader( 1518): No account for auth token provided
,W/Uploader( 1518):  no longer exists, so no auth token.
,W/Uploader( 1518): No account for auth token provided
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024076287887287; DSPS: 5928268; Offset: 1453023895371505452
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024080056, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024080060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024096289997227; DSPS: 6583698; Offset: 1453023895371479161
,D/wpa_supplicant( 2040): wlan0: BSS: Remove id 5 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 dc:4a:3e:0f:c2:f1]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024116293058730; DSPS: 7239158; Offset: 1453023895371488906
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024136295543514; DSPS: 7894599; Offset: 1453023895371501766
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024140045, nextTick: 59971, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024140056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024156298065746; DSPS: 8550042; Offset: 1453023895371491039
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024176300651988; DSPS: 9205487; Offset: 1453023895371483287
,I/jxcore-log( 4779): TAP version 13
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # multiplex can send data
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 1 String should be length:200
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # basic
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 2 sane
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # another
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 3 sane
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 4 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 5 null
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 6 (unnamed assert)
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 7 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 8 should not throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024196302109168; DSPS: 9860895; Offset: 1453023895371475624
,I/jxcore-log( 4779): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 9 (unnamed assert)
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 10 (unnamed assert)
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 11 should not throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 12 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 13 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 14 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # failed to get mobile documents path
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 15 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 16 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 17 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 18 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #init should register the networkChanged event
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 19 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on null device name
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 20 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 21 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 22 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 23 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on negative port
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 24 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should throw on too large port
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 25 should throw
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 26 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 27 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 28 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
I/jxcore-log( 4779): ok 29 should be equal
I/jxcore-log( 4779): 
I/jxcore-log( 4779): ok 30 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 31 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 32 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 33 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 34 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 35 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 36 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 37 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 38 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 39 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 40 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 41 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 42 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 43 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): ok 44 should be equal
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # setup
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): # teardown
I/jxcore-log( 4779): 
,I/dalvikvm( 4779): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4779): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4779): start: Peer ID: 34:FC:EF:9D:93:0B, peer name: 1453024198539.4779
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4779): bind: Binding a new listener
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4779): initialize: My bluetooth address is 34:FC:EF:9D:93:0B
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4779): verifyIdentityString: Identity string created: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1453024198539.4779"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4779): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4779): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1224): SOCK FLAG = 0 ***********************
D/bt-btif ( 1224): btsock_rfc_listen, service_name:Thali_Bluetooth
D/bt-btif ( 1224): BTA_JvCreateRecordByUser:Thali_Bluetooth
I/bt-btif ( 1224): BTA_JvCreateRecordByUser
D/bt-btif ( 1224): jv_dm_cback: event:11, slot id:4
D/bt-btif ( 1224): name:Thali_Bluetooth, scn:7
,D/LGBluetoothServiceAdapter( 1224): [BTUI] createSocketChannel FD=97 mFd=96
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:14
I/bt-btif ( 1224): BTA_JvRfcommStartServer
D/bt-btif ( 1224): bta_jv_rfcomm_start_server: sec id in use:3, rfc_cb in use:3
,D/bt-btif ( 1224): bta_jv_alloc_rfc_cb port_handle:9 handle:0x84
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4779): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4779): start: OK
I/io.jxcore.node.ConnectionHelper( 4779): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4779): start: Peer ID: 34:FC:EF:9D:93:0B, peer name: 1453024198539.4779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4779): Waiting for incoming connections...
,W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4779): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 4779): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,D/dalvikvm( 4779): VFY: replacing opcode 0x22 at 0x0013
W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
I/dalvikvm( 4779): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
W/dalvikvm( 4779): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
,D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0002
E/dalvikvm( 4779): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4779): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,D/dalvikvm( 4779): VFY: replacing opcode 0x22 at 0x002d
,W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4779): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4779): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
W/dalvikvm( 4779): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 4779): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
,W/dalvikvm( 4779): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,D/dalvikvm( 4779): DexOpt: unable to opt direct call 0x0709 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
W/dalvikvm( 4779): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4779): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
D/dalvikvm( 4779): DexOpt: unable to opt direct call 0x072a at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
,D/dalvikvm( 4779): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/dalvikvm( 4779): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AndroidRuntime( 4779): Shutting down VM
,W/dalvikvm( 4779): threadid=1: thread exiting with uncaught exception (group=0x417b9e48)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at android.os.Looper.loop(Looper.java:136)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4779): 	at dalvik.system.NativeStart.main(Native Method)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024200054, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024200056, nextTick: 59976, mDrawingTime: 0
,D/wpa_supplicant( 2040): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2040): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/wpa_supplicant( 2040): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/wpa_supplicant( 2040): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024216308412347; DSPS: 10516461; Offset: 1453023895371492181
,D/dalvikvm( 2681): GC_CONCURRENT freed 7892K, 33% free 16761K/24832K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 2681): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/ActivityManager(  964): Killing 4693:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ffc18 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1518): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1518): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1518): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1518): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1518): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1518): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43017b38: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1518): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1518): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1518): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1518): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1518): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1518): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1518): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1518): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4348): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4348): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4348): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4348): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4348): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4348): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4348): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4348): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4348): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024236313995495; DSPS: 11172004; Offset: 1453023895371490613
,I/LocationManagerService(  964): remove 4325e130
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2681): GC_CONCURRENT freed 1733K, 32% free 17075K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2681): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2681): GC_CONCURRENT freed 1806K, 31% free 17317K/24832K, paused 3ms+2ms, total 51ms
,D/dalvikvm( 2681): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 2681): GC_FOR_ALLOC freed 1331K, 30% free 17542K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2681): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024256317592674; DSPS: 11827482; Offset: 1453023895371486717
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024260029, nextTick: 60001, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024260047, nextTick: 59985, mDrawingTime: 0
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5608
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5609
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024276325801930; DSPS: 12483111; Offset: 1453023895371486745
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024296328313544; DSPS: 13138553; Offset: 1453023895371495918
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/dalvikvm( 1141): GC_CONCURRENT freed 9614K, 13% free 68787K/78584K, paused 20ms+9ms, total 93ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024316334371565; DSPS: 13794112; Offset: 1453023895371480940
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024320035, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024320043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024336339552109; DSPS: 14449642; Offset: 1453023895371473496
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024356345446865; DSPS: 15105195; Offset: 1453023895371478360
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024376349007593; DSPS: 15760671; Offset: 1453023895371499049
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024380043, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024380050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024396354738273; DSPS: 16416219; Offset: 1453023895371492424
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024416361207524; DSPS: 17071791; Offset: 1453023895371491948
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024436364744227; DSPS: 17727267; Offset: 1453023895371488612
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024440049, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024440054, nextTick: 59978, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm(  964): GC_CONCURRENT freed 2993K, 50% free 29925K/59244K, paused 56ms+12ms, total 240ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024456370489685; DSPS: 18382815; Offset: 1453023895371496766
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024476377490476; DSPS: 19038405; Offset: 1453023895371478514
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024496385453696; DSPS: 19694026; Offset: 1453023895371476646
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024500080, nextTick: 59945, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024500085, nextTick: 59947, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024516391070870; DSPS: 20349570; Offset: 1453023895371478585
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024536397254629; DSPS: 21005133; Offset: 1453023895371467276
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024556403047647; DSPS: 21660682; Offset: 1453023895371492472
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024560048, nextTick: 59961, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024560063, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024576409357346; DSPS: 22316248; Offset: 1453023895371515550
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024596413003611; DSPS: 22971728; Offset: 1453023895371499705
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024616419347033; DSPS: 23627296; Offset: 1453023895371495471
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024620085, nextTick: 59939, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024620089, nextTick: 59943, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024636422417219; DSPS: 24282757; Offset: 1453023895371483382
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024656427224772; DSPS: 24938274; Offset: 1453023895371499675
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024676430958604; DSPS: 25593757; Offset: 1453023895371479845
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024680056, nextTick: 59964, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024680064, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024696435285551; DSPS: 26249258; Offset: 1453023895371503813
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024716439045264; DSPS: 26904742; Offset: 1453023895371479347
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024736444830034; DSPS: 27560291; Offset: 1453023895371496294
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024740045, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024740059, nextTick: 59973, mDrawingTime: 0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024756450789998; DSPS: 28215846; Offset: 1453023895371505331
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024776455553729; DSPS: 28871362; Offset: 1453023895371508319
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024796460312793; DSPS: 29526878; Offset: 1453023895371506641
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024800058, nextTick: 59970, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024800061, nextTick: 59968, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024816465149417; DSPS: 30182397; Offset: 1453023895371490970
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024836471341180; DSPS: 30837960; Offset: 1453023895371487665
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024856477022111; DSPS: 31493506; Offset: 1453023895371492326
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024860044, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024860047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024876481084069; DSPS: 32148999; Offset: 1453023895371495446
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024896487321884; DSPS: 32804564; Offset: 1453023895371477158
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024916493850507; DSPS: 33460138; Offset: 1453023895371475019
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024920048, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024920056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024936498263153; DSPS: 34115642; Offset: 1453023895371493134
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024956502688025; DSPS: 34771147; Offset: 1453023895371492957
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024976507582945; DSPS: 35426668; Offset: 1453023895371474547
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024980053, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453024980056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453024996514467939; DSPS: 36082253; Offset: 1453023895371493086
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025016521721234; DSPS: 36737851; Offset: 1453023895371483197
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025036524445802; DSPS: 37393300; Offset: 1453023895371491701
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025040048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025040053, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025056529015445; DSPS: 38048810; Offset: 1453023895371483707
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025076534487946; DSPS: 38704349; Offset: 1453023895371493562
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025096540341435; DSPS: 39359901; Offset: 1453023895371487676
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025100048, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025100054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025116546794400; DSPS: 40015472; Offset: 1453023895371501432
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025136549049183; DSPS: 40670906; Offset: 1453023895371497914
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025156558900041; DSPS: 41326589; Offset: 1453023895371491594
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025160075, nextTick: 59956, mDrawingTime: 2
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025160076, nextTick: 59956, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025176563629587; DSPS: 41982104; Offset: 1453023895371490916
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025196568709225; DSPS: 42637631; Offset: 1453023895371474118
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025216574692134; DSPS: 43293187; Offset: 1453023895371475582
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025220054, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453025220057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453025236581001661; DSPS: 43948753; Offset: 1453023895371498488
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6489): 
D/AndroidRuntime( 6489): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6489): CheckJNI is OFF
D/dalvikvm( 6489): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6489): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6489): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6489): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6489): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 6489): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 6489): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6489): failed to load memtrack module: -2
D/AndroidRuntime( 6489): Calling main entry com.android.commands.pm.Pm
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  964): Killing 4779:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  964):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  964):   Force finishing activity ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  964): moveHomeStack:
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
I/WindowState(  964): WIN DEATH: Window{4301e4b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  964): Client connection lost with reason: 4
D/bt-btif ( 1224): SOCK_THREAD_FD_EXCEPTION, cleanup, flags:4, need_close:0, pending size:0
D/bt-btif ( 1224): cleanup slot:4, fd:94, scn:7, sdp_handle:0x1000d
D/bt-btif ( 1224): del_rfc_sdp_rec: handle:0x1000d
I/bt-btif ( 1224): BTA_JvDeleteRecord
D/bt-sdp  ( 1224): SDP_DeleteRecord ok, num_records:13
I/bt-btif ( 1224): BTA_JvRfcommStopServer
E/bt-btif ( 1224): bta_jv_rfcomm_stop_server
D/bt-btif ( 1224): find_rfc_pcb(): FOUND rfc_cb_handle 0x4, port.jv_handle: 0x84, state: 4, rfc_cb->handle: 0x84
D/bt-btif ( 1224): bta_jv_rfcomm_stop_server: p_pcb:0x60cab124, p_pcb->port_handle:9
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60cab124, user:4, state:4, jv handle: 0x84
D/bt-btif ( 1224): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:7, user_data:4
D/bt-btif ( 1224): bta_jv_rfcomm_stop_server: sec id in use:3, rfc_cb in use:3
W/PackageSettings(  964): Skipping PackageSetting{42cd50a0 com.example.hello/10312} due to missing metadata
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} (in existing)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1}
D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43afd8f8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
D/dalvikvm( 2693): GC_EXPLICIT freed 6017K, 27% free 18232K/24832K, paused 1ms+4ms, total 54ms
D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
E/SlideAside( 4136): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
W/System.err( 2681): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
D/PhoneApp( 1450): getIsInUseVoLTE : false
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "sms"
I/ActivityManager(  964): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6512 uid=10090 gids={50090}
W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/System.err( 2681): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
I/SlideAside( 4136): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
W/System.err( 2681): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2681): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2681): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2681): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2681): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2681): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2681): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2681): 	at java.lang.reflect.Method.invoke(Method.java:515)
D/AppUp4:Utils( 4107): [getPackageName] uri : package:com.test.thalitest
W/System.err( 2681): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
D/AppUp4  ( 4107): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4107):  isExcludedPackage  packagename = com.test.thalitest
W/System.err( 2681): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2681): 	at dalvik.system.NativeStart.main(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4  ( 4107):  isExcludedPackage TRUE : com.test.thalitest
D/dalvikvm(  964): GC_EXPLICIT freed 1236K, 50% free 29847K/59244K, paused 2ms+7ms, total 110ms
W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/administrator(  964): Handling package changes for user 0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1491): [Launcher.java:894:onPause()]onPause
I/ActivityManager(  964): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6537 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} (pause complete)
I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
D/HyLog   ( 6512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6512): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1491): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "sms"
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/Binder  ( 1305): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1305): java.lang.NullPointerException
W/Binder  ( 1305): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1305): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1305): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1305): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  964): IME STATUS OFF
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4779 uid 10304
D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/HyLog   ( 6537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6537): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6537): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mms"
I/LockScreenSettings( 6512): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1491): [Launcher.java:4955:onStop()]onStop
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/[BNRAppListMgrReceiver]( 6537): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  964): GC_EXPLICIT freed 561K, 50% free 29949K/59244K, paused 2ms+12ms, total 178ms
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  964): updateIntentFilterConfig
I/InteractionManagerConfigurator(  964): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  964): removePackageParticipantsLocked: uid=10304 #1
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} time:1339811
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1141): createShortcutInfo...
D/AndroidRuntime( 6489): Shutting down VM
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
I/ActivityManager(  964): Killing 4922:com.google.android.setupwizard/u0a52 (adj 15): empty #17
D/dalvikvm( 6489): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
D/dalvikvm( 1491): GC_CONCURRENT freed 5336K, 9% free 60772K/66292K, paused 1ms+3ms, total 23ms
D/VoicemailCleanupService( 1808): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6554 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/HyLog   ( 6554): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6554): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6554): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1141): handleShortcutListChanged...
D/KeyguardModel( 1141): handleShortcutListChanged...
I/ActivityManager(  964): Killing 4939:com.android.chrome/u0a63 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{431f5838 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 6554): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
E/LGEmail ( 6554): Email Not Started (at LGEmailContentProvider.java query 509)[v:null]
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/LGEmail ( 6554): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/LGEmail ( 6554): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/BaseRuntimeLoader( 6554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
W/BaseRuntimeLoader( 6554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/PackageChangeReceiver( 6554): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  964): Killing 4952:com.lge.drmservice/u0a66 (adj 15): empty #17
D/PackageIntentReceiver( 2624): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2624): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2624): Delete mPackageMame : com.test.thalitest
I/IcingCorporaProvider( 2693): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c07118 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@427f6fc8 time:1340053
I/ActivityManager(  964): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6576 uid=10073 gids={50073, 3003, 1028, 1015}
D/HyLog   ( 6576): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6576): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6576): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/IcingCorporaProvider( 2693): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
