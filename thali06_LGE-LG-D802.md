#### Test 54970261e0c50c1_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4675): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 3626:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1969): fetch service done; releasing wakelock
I/ConfigFetchService( 1969): stopping self
D/ChimeraCfgMgr( 1969): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1969): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1969): GC_CONCURRENT freed 1532K, 22% free 19458K/24832K, paused 2ms+3ms, total 33ms
D/AndroidRuntime( 4721): 
D/AndroidRuntime( 4721): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4721): CheckJNI is OFF
D/dalvikvm( 4721): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4721): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4721): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4721): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4721): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4721): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1969): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1969): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1969): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4721): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4721): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4721): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4721
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (101 us)
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  960): startService SlideAside
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{4330f208 stackId=1, 2 tasks}
D/AndroidRuntime( 4721): Shutting down VM
D/UsbSettingsControl( 2608): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2608): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4721): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
I/SlideAside( 3791): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4736 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3791): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3791): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4736): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4736): Binding Chromium to the background looper Looper (main, tid 1) {4285ab10}
I/chromium( 4736): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4736): Initializing chromium process, renderers=0
I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4736): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4736): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4736): Remote Branch: 
I/Adreno-EGL( 4736): Local Patches: 
I/Adreno-EGL( 4736): Reconstruct Branch: 
W/chromium( 4736): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/dalvikvm( 4736): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4736): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4736): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4736): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4736): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4736): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4736): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4736): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4736): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4736): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4736): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4736): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4736): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4736): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4736): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4736): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/OpenGLRenderer( 4736): Enabling debug mode 0
,W/AwContents( 4736): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  960): IME STATUS OFF
,W/AwContents( 4736): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +523ms
,I/ActivityManager( 4736): Timeline: Activity_idle id: android.os.BinderProxy@4285c2e0 time:108292
D/ActivityManager(  960): no-history finish of ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{4317b678 ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} time:108511
D/JsMessageQueue( 4736): Set native->JS mode to OnlineEventsBridgeMode
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2608): [AUTORUN] onStop()
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4736): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 4736): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428609b8
D/dalvikvm( 4736): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428609b8
D/jxcore_app_log( 4736): JniHelper::setJavaVM(0x41726838), pthread_self() = 1632180752
D/JX-Cordova( 4736): jxcore cordova android initializing
I/chromium( 4736): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4736): GC_CONCURRENT freed 2787K, 12% free 21865K/24832K, paused 2ms+1ms, total 50ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 98K, 12% free 21877K/24832K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.598MB for 63974-byte allocation
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/dalvikvm( 4736): GC_FOR_ALLOC freed 139K, 13% free 21883K/24896K, paused 25ms, total 26ms
I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.635MB for 95956-byte allocation
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274500031, nextTick: 60000, mDrawingTime: 1
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 179K, 13% free 21917K/24992K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.714MB for 143930-byte allocation
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274500052, nextTick: 59981, mDrawingTime: 0
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 252K, 13% free 21964K/25136K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 23.830MB for 215890-byte allocation
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 368K, 14% free 22038K/25348K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 24.004MB for 323830-byte allocation
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 566K, 14% free 22159K/25668K, paused 30ms, total 30ms
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 864K, 13% free 22335K/25668K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 24.680MB for 728606-byte allocation
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 1280K, 15% free 22590K/26380K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 25.276MB for 1092904-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,D/dalvikvm( 4736): GC_CONCURRENT freed 1767K, 17% free 22972K/27448K, paused 3ms+3ms, total 46ms
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 284K, 17% free 22907K/27448K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 26.107MB for 1639352-byte allocation
,D/dalvikvm( 4736): GC_CONCURRENT freed 1740K, 19% free 23537K/29052K, paused 2ms+3ms, total 38ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 4736): GC_FOR_ALLOC freed 1253K, 19% free 23542K/29052K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 27.509MB for 2459024-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4736): GC_CONCURRENT freed 284K, 18% free 25844K/31456K, paused 2ms+4ms, total 39ms
,D/dalvikvm( 4736): GC_CONCURRENT freed 4337K, 22% free 24544K/31456K, paused 1ms+4ms, total 46ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/dalvikvm-heap( 4736): Grow heap (frag case) to 29.660MB for 3688532-byte allocation
,D/dalvikvm( 4736): GC_CONCURRENT freed 2935K, 27% free 25776K/35060K, paused 0ms+6ms, total 58ms
,W/jxcore-log( 4736): Initializing JXcore engine
,W/jxcore-log( 4736): JXcore engine is ready
,D/dalvikvm( 4736): GC_CONCURRENT freed 725K, 20% free 28153K/35060K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4736): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/jxcore-log( 4736): Starting JXcore engine
,W/jxcore-log( 4736): Platform android
W/jxcore-log( 4736): 
,W/jxcore-log( 4736): Process ARCH arm
W/jxcore-log( 4736): 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4736): JXcore Cordova bridge is ready!
I/jxcore-log( 4736): 
,W/jxcore-log( 4736): JXcore engine is started
,I/chromium( 4736): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4736): Skipped 156 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4736): Toggling radios to true
I/jxcore-log( 4736): 
,D/BluetoothManagerService(  960): Message: 20
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a1da30:true
,D/BluetoothAdapter( 4736): enable(): BT is already enabled..!
D/WifiStateMachine(  960): handleMessage: E msg.what=131145
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doBoolean: DISCONNECT
,I/jxcore-log( 4736): Radios toggled
I/jxcore-log( 4736): 
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2026): TDLS: Tear down peers
,D/wpa_supplicant( 2026): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  960): New client listening to asynchronous messages
D/WifiService(  960): setWifiEnabled: true pid=4736, uid=10304
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  960): disconnect pid=4736, uid=10304
D/WifiService(  960): reconnect pid=4736, uid=10304
,D/wpa_supplicant( 2026): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2026): wlan0: Deauthentication notification
D/wpa_supplicant( 2026): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2026): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2026): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2026): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2026): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb86d4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2026): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131146
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiNative-wlan0(  960): doBoolean: RECONNECT
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2026): Fast associate: Old scan results
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2026): wlan0: nl80211: scan request
D/wpa_supplicant( 2026): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2026): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147460
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  960):    returned true
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  960): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/QCNEA   (  599): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  599): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  599): |CAC| updateNetCfgInfo
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC|                   Netconfig               
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  599): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  599): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  599): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  599): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  599): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  599): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| Received bssid= 
D/QCNEA   (  599): |CAC| net type = 3
V/QCNEA   (  599): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  599): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  599): |CAC| 	ssid           =NG700
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  599): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  599): |CAC| dispatchNetCfg: updating:0xb7a008dc
D/QCNEA   (  599): |CAC| readCallback: read len:0, ret:-1, errno:11
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiHS20(  960): hidePasspointNotification off =false
D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4794 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  960): route cmd failed: 
W/NetworkManagementService(  960): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  960): '
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  960): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  960): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  960): android_net_utils_resetConnections in env=0x6379e2d8 clazz=0x6d200001 iface=wlan0 mask=0x3
D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ProcessCpuTracker(  960): Skipping unknown process pid 4809
D/QcConnectivityService(  960): resetConnections(wlan0, 3)
,V/NativeCrypto( 1535): Read error: ssl=0x63c5aa70: I/O error during system call, Connection timed out
,V/NativeCrypto( 1535): SSL shutdown failed: ssl=0x63c5aa70: I/O error during system call, Broken pipe
I/ActivityManager(  960): Killing 4199:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4794): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4831 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  960): Killing 4325:android.process.media/u0a23 (adj 15): empty #17
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4831): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4831): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4831): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4831): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4831): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4831): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4831): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4831): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  960): Killing 3956:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/DhcpStateMachine(  960): StoppedState
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,I/GAV2    ( 4675): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1535): onDestroy
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.449463 Y: -0.437622 Z: 9.786484 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449463 .y:-0.437622 .z:9.786484
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.447906 Y: -0.417419 Z: 9.787384 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447906 .y:-0.417419 .z:9.787384
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/WifiController(  960): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4072): onReceive
,D/AppUp4:CustFacade( 4072): Context : android.app.ReceiverRestrictedContext@428785a0
D/AppUp4:CustFacade( 4072): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4072): isOpenOperator : true
,D/AppUp4:CustFacade( 4072): isPhone : true
,I/LicenseContentProvider( 2977): start selecting data
,D/SIMObserver( 2977): simInfo1
,I/AppUp4:EulaManager( 4072): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4072): begin check event
,I/AppUp4:CustModeStarterReceiver( 4072): Event For GoodConnectivity
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4858 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4858): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2026): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2026): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2026): nl80211: Survey data missing
D/wpa_supplicant( 2026): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 8 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2026): wlan0: New scan results available
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2026): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
,D/wpa_supplicant( 2026): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2026): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2026): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[5] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2026): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2026): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb86d65a8  current_ssid=0x0
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2026): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2026): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2026): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2026): RSN: PMKSA cache search - network_ctx=0xb86d65a8 try_opportunistic=0
D/wpa_supplicant( 2026): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2026): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2026): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2026): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2026): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2026): nl80211: Unsubscribe mgmt frames handle 0xb86d5590 (mode change)
D/wpa_supplicant( 2026): nl80211: Subscribe to mgmt frames with non-AP handle 0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb86d5590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2026): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2026):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026):   * freq=2412
D/wpa_supplicant( 2026):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2026):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026):   * Auth Type 0
D/wpa_supplicant( 2026):   * WPA Versions 0x2
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 64:7c:34:b0:03:6e]
D/wpa_supplicant( 2026): nl80211: Connect request send successfully
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2026): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4858): DownloadService onCreate
D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Connect event
D/wpa_supplicant( 2026): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2026): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2026): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2026): wlan0: Association info event
D/wpa_supplicant( 2026): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2026): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): wlan0: freq=2412 MHz
D/wpa_supplicant( 2026): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2026): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2026): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2026): TDLS: Remove peers on association
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2026): EAPOL: enable timer tick
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/eas_req ( 4658): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4858): in removeSpuriousFiles
V/DownloadManager( 4858): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4413): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4413): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4413): networkInfo.isConnected() = false
V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428a08c8 on behalf of 4858
I/DownloadManager( 4858): in trimDatabase
V/DownloadManager( 4858): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428a2718 on behalf of 4858
,I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4884 uid=10052 gids={50052, 3003}
W/linker  ( 4658): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4658): JNI_OnLoad
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 ...
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 dd 7e 3e c1 55 42 58 9a d8 bf 18 69 ca 2b f3 9d 71
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 ...
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2026): Get randomness: len=32 entropy=10
D/wpa_supplicant( 2026): WPA: Renewed SNonce - hexdump(len=32): 6c 32 29 d3 4a 60 a8 46 7e 91 df 27 f3 7c 23 67 ec b7 c8 2c 9a 70 0e d3 d5 bd 8c 63 ba 2b ed e5
D/wpa_supplicant( 2026): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): WPA: Nonce1 - hexdump(len=32): 6c 32 29 d3 4a 60 a8 46 7e 91 df 27 f3 7c 23 67 ec b7 c8 2c 9a 70 0e d3 d5 bd 8c 63 ba 2b ed e5
D/wpa_supplicant( 2026): WPA: Nonce2 - hexdump(len=32): 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 dd 7e 3e c1 55 42 58 9a d8 bf 18 69 ca 2b f3 9d 71
D/wpa_supplicant( 2026): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2026): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 6c b9 76 0e 18 f5 85 bf e4 0a ff c5 47 40 9e 61
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 6c 32 29 d3 4a 60 a8 46 7e 91 df 27 f3 7c 23 ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
V/DownloadManager( 4858): DownloadService onStartCommand
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4658): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4658): register,_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4658): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4658): register_HtmlEditor, Success
D/HtmlEditor( 4658): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4658): register_HtmlEditorTimer, Success
D/HtmlEditor( 4658): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4658): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4658): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorFont, Success
D/HtmlEditor( 4658): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4658): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4658): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4658): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4658): JNI_OnLoad Success
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 ...
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 dd 7e 3e c1 55 42 58 9a d8 bf 18 69 ca 2b f3 9d 71
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): d2 44 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): cb 04 d8 18 83 3f ec 30 d7 be 3f a7 09 20 9b 7f
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1f 84 b3 d6 74 3e 12 dd fc 01 f6 d3 5e 96 f2 ...
D/wpa_supplicant( 2026): RSN: encrypted key data - hexdump(len=56): 38 01 7d 54 5c 92 fe e9 c2 b7 b6 57 23 f2 5e 61 fc d2 60 1f 4e c4 2c a2 f9 82 5c ce 9e 4f 65 28 ...
D/wpa_supplicant( 2026): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 85 d9 a1 2d f7 60 3f 87 76 03 e1 1a 74 11 56 ed
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb86d5c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4884): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/HubEmail( 4658): JNI_O,nLoad()
I/HubEmail( 4658): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4658): registerNatives()
D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 4658): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4658): registerNativeMethods()
I/HubEmail( 4658): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4858): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2026): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2026): WPA: RSC - hexdump(len=6): d2 44 00 00 00 00
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f8203a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2026):    broadcast key
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
I/wpa_supplicant( 2026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2026): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2026): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): EAPOL authentication completed successfully
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection established
D/WifiNative-wlan0(  960): doString: STATUS
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2026): wlan0: Control interface command 'STATUS'
W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428a5430 on behalf of 4858
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  599): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@43d81a00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/DhcpStateMachine(  960): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@44ea37a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-10ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
V/DownloadManager( 4858): DownloadService onDestroy
I/ActivityManager(  960): Killing 4394:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4884): [loadRssi] File not exist 
V/LGRssiData( 4884): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4884): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
W/BaseRuntimeLoader( 4884): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4884): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4884): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4884): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4884): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4884): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4884): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4884): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4884): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4884): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4904 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  960): Killing 4580:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432b5a88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432b5a88 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  960): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
D/WifiStateMachine(  960): processMsg: ObtainingIpState
I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4917 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  960): Killing 4615:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
,D/WifiStateMachine(  960): DHCP successful
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
,D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState enter
,D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  960): handleMessage: X
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  599): Reading a NULL string not supported here.
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/HyLog   ( 4917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4917): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  960): Killing 4643:com.lge.bnr/1000 (adj 15): empty #17
V/        (  264): RouteController
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4938 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/        (  264): RouteController
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  599): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  599): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  599): |CAC| updateNetCfgInfo
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC|                   Netconfig               
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  599): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  599): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  599): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  599): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  599): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  599): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  599): |CAC| net type = 1
V/QCNEA   (  599): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  599): |CAC| Received ssid= NG700
V/QCNEA   (  599): |CAC| 	ssid           =NG700
V/QCNEA   (  599): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  599): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  599): |CAC| dispatchNetCfg: updating:0xb7a008dc
D/QCNEA   (  599): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  960): GC_EXPLICIT freed 23530K, 49% free 29781K/57872K, paused 5ms+8ms, total 139ms
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4938): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1969): Checking schedule, now: 1452274505859 next: 1452274452599
,I/CheckinService( 1969): active receiver: enabled
,I/CheckinService( 1969): Preparing to send checkin request
,I/EventLogService( 1969): Accumulating logs since 1452274419400
,D/LGDMSGCM( 4938): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4973 uid=10101 gids={50101, 1028, 1015, 3003}
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4973): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,I/NFS     ( 4973): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4973): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4973): intf.getDisplayName() = lo
,I/Wireless_Storage( 4973): intf.getDisplayName() = sit0
I/Wireless_Storage( 4973): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4973): intf.getDisplayName() = teql0
I/Wireless_Storage( 4973): intf.getDisplayName() = wlan0
D/NFS     ( 4973): interface name:wlan0 name:wlan0
D/NFS     ( 4973): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4973): interface name:wlan0 name:wlan0
,D/NFS     ( 4973): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4973): CONNECT : WIFI_CONNECT
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4986 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4246:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/dalvikvm( 1535): GC_EXPLICIT freed 960K, 29% free 17815K/24832K, paused 3ms+3ms, total 27ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,W/GAV2    ( 4986): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x431df650: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1969): awaiting user notification for token
V/WebViewChromium( 4986): Binding Chromium to the main looper Looper (main, tid 1) {42864540}
I/chromium( 4986): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4986): Initializing chromium process, renderers=0
,W/chromium( 4986): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5027 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Adreno-EGL( 4986): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4986): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4986): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4986): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4986): Remote Branch: 
I/Adreno-EGL( 4986): Local Patches: 
I/Adreno-EGL( 4986): Reconstruct Branch: 
,D/HyLog   ( 5027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5027): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5027): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5027): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5027): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5027): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5027): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5027): VM with version 1.6.0 does not have multidex support
I/NSApplication( 4986): Starting up...
,I/MultiDex( 5027): install
,I/MultiDex( 5027): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5027): loading existing secondary dex files
,I/MultiDex( 5027): load found 3 secondary dex files
,I/MultiDex( 5027): install done
I/ActivityManager(  960): Killing 4262:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 5027): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5027): VFY: unable to resolve instance field 61
,D/dalvikvm( 5027): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5027): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5027): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5027): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5027): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5027): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5027): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5027): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5027): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5027): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285fcf0
D/dalvikvm( 5027): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285fcf0
,D/dalvikvm( 5027): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285fcf0, skipping init
,D/dalvikvm( 5027): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285fcf0
D/dalvikvm( 5027): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285fcf0
,V/JNIHelp ( 5027): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4831): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4831): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4831): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 5027): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285fcf0
,D/dalvikvm( 5027): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4285fcf0
D/dalvikvm( 5027): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285fcf0
,D/dalvikvm( 5027): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4285fcf0
,I/ProviderInstaller( 5027): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1535): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1535): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1969): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1875): callingUid 10006, callindPid: 1875
,E/MDM     ( 1427): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1969): Restart initialization of location
I/dalvikvm( 5027): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5027): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5027): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5027): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5027): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5027): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fc2000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fc2000
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=3889509515
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2026): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2026): EAPOL: disable timer tick
,D/dalvikvm( 5027): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a18d70
,D/dalvikvm( 5027): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a18d70
,D/dalvikvm( 5027): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a18d70, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 5027): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5058): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5027): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5027): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 111ms
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Adreno-EGL( 5027): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5027): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5027): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5027): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5027): Remote Branch: 
I/Adreno-EGL( 5027): Local Patches: 
I/Adreno-EGL( 5027): Reconstruct Branch: 
,D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2477925233
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 5027): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5027): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5027): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5027): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5027): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5027): Remote Branch: 
I/Adreno-EGL( 5027): Local Patches: 
I/Adreno-EGL( 5027): Reconstruct Branch: 
,I/Adreno-EGL( 5027): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5027): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5027): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5027): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5027): Remote Branch: 
I/Adreno-EGL( 5027): Local Patches: 
I/Adreno-EGL( 5027): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinTask( 1969): Sending checkin request (11461 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GCM     ( 1535): Connected
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1535): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x43d69b20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1969): awaiting user notification for token
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,I/CheckinTask( 1969): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1969): Checking schedule, now: 1452274508195 next: 1452851904192
,I/CheckinService( 1969): active receiver: disabled
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4072): onReceive
,D/AppUp4:CustFacade( 4072): Context : android.app.ReceiverRestrictedContext@428785a0
D/AppUp4:CustFacade( 4072): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4072): isOpenOperator : true
,D/AppUp4:CustFacade( 4072): isPhone : true
,I/LicenseContentProvider( 2977): start selecting data
,D/SIMObserver( 2977): simInfo1
,I/AppUp4:EulaManager( 4072): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4072): begin check event
,I/AppUp4:CustModeStarterReceiver( 4072): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4072): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4072): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4072): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4072): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4072): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4858): DownloadService onCreate
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4858): in removeSpuriousFiles
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428ab378 on behalf of 4858
,I/DownloadManager( 4858): in trimDatabase
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428ac448 on behalf of 4858
,V/DownloadManager( 4858): DownloadService onStartCommand
,V/DownloadManager( 4858): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4658): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4413): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4413): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4413): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4884): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428aef20 on behalf of 4858
,V/DownloadManager( 4858): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4938): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/ContextImpl( 4938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/NFS     ( 4973): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4973): CONNECT : WIFI_CONNECT
E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4072): onReceive
,D/AppUp4:CustFacade( 4072): Context : android.app.ReceiverRestrictedContext@428785a0
D/AppUp4:CustFacade( 4072): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4072): isOpenOperator : true
,D/AppUp4:CustFacade( 4072): isPhone : true
,I/LicenseContentProvider( 2977): start selecting data
,D/SIMObserver( 2977): simInfo1
,I/AppUp4:EulaManager( 4072): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4072): begin check event
,I/AppUp4:CustModeStarterReceiver( 4072): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4858): DownloadService onCreate
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4858): in removeSpuriousFiles
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4858): DownloadService onStartCommand
V/DownloadManager( 4858): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428b3f88 on behalf of 4858
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428b5c50 on behalf of 4858
I/DownloadManager( 4858): in trimDatabase
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428b7518 on behalf of 4858
,V/DownloadManager( 4858): DownloadService onDestroy
,I/LgeMiscReceiver( 4413): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4413): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4413): networkInfo.isConnected() = true
,D/PhoneState( 4413): setPdpRejectCasuse : false
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4884): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4938): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4973): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4973): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/jxcore-log( 4736): Test app app.js loaded
I/jxcore-log( 4736): 
,I/chromium( 4736): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-8ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4072): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4072): onReceive
,D/AppUp4:CustFacade( 4072): Context : android.app.ReceiverRestrictedContext@428785a0
D/AppUp4:CustFacade( 4072): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4072): isOpenOperator : true
,D/AppUp4:CustFacade( 4072): isPhone : true
,I/LicenseContentProvider( 2977): start selecting data
,D/SIMObserver( 2977): simInfo1
,I/AppUp4:EulaManager( 4072): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4072): begin check event
,I/AppUp4:CustModeStarterReceiver( 4072): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4858): DownloadService onCreate
,D/EAS     ( 4658): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/LgeMiscReceiver( 4413): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4413): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4413): networkInfo.isConnected() = true
,D/PhoneState( 4413): setPdpRejectCasuse : false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/MobileConnectivityChangeReceiver( 4884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4884): onReceive CONNECTIVITY_CHANGE networkType=1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4858): in removeSpuriousFiles
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/dalvikvm(  960): GC_EXPLICIT freed 2366K, 49% free 29729K/57872K, paused 4ms+6ms, total 87ms
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428baf58 on behalf of 4858
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4858): DownloadService onStartCommand
I/DownloadManager( 4858): in trimDatabase
V/DownloadManager( 4858): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428bd640 on behalf of 4858
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4938): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428be6d8 on behalf of 4858
,W/ContextImpl( 4938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4973): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4973): CONNECT : WIFI_CONNECT
V/DownloadManager( 4858): DownloadService onDestroy
E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 4986): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/ActivityManager(  960): Killing 4283:com.android.vending/u0a50 (adj 15): empty #17
I/ActivityManager(  960): Killing 4675:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  960): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5168 uid=10050 gids={50050, 3003, 1028, 1015}
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/HyLog   ( 5168): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5168): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5168): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5168): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5168): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5168): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5168): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5168): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5168): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5168): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5168): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5168): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5168): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5168): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5168): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5168): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5168): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5168): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5168): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4858): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4858): created cursor android.database.sqlite.SQLiteCursor@428c3d20 on behalf of 5168
,I/dalvikvm( 5168): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5168): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x0049
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5168): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5168): [1] 2.run: Finished loading 1 libraries.
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/Finsky  ( 5168): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5168): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5168): Total arena pages for JIT: 11
,I/dalvikvm( 5168): Total arena pages for JIT: 12
I/dalvikvm( 5168): Total arena pages for JIT: 13
,I/dalvikvm( 5168): Total arena pages for JIT: 14
,D/Finsky  ( 5168): [463] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5168): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  960): Killing 4794:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5168): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5168): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5168): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5168): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 5168): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5168): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1535): GC_EXPLICIT freed 1404K, 29% free 17813K/24832K, paused 2ms+6ms, total 45ms
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5168): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5168): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/Finsky  ( 5168): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5168): [1] DailyHygiene.reschedule: Scheduling new run in 81 minutes (failures=3)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5258 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3791): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
D/administrator(  960): Handling package changes for user 0
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3791): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.448822 Y: -0.432571 Z: 9.787369 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448822 .y:-0.432571 .z:9.787369
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/HyLog   ( 5258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5258): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.446609 Y: -0.433777 Z: 9.797791 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446609 .y:-0.433777 .z:9.797791
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Babel   ( 5258): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5258): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5258): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5258): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5258): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5258): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5258): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5258): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5258): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5258): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5258): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5258): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5258): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5258): MmsConfig.loadFromResources
E/Babel   ( 5258): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5258): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5258): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/LGRssiData( 5258): [loadRssi] File not exist 
,V/LGRssiData( 5258): [loadRssi] File not exist 
D/AppUp4:Utils( 4072): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4072): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4072): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/TelephonyAutoProfiling( 5258): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5258): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5258): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5258): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4072): onReceive
D/AppUp4:CustFacade( 4072): Context : android.app.ReceiverRestrictedContext@428785a0
D/AppUp4:CustFacade( 4072): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4072): isOpenOperator : true
,D/AppUp4:CustFacade( 4072): isPhone : true
,I/LicenseContentProvider( 2977): start selecting data
V/GmsNetworkLocationProvi( 1427): DISABLE
,D/SIMObserver( 2977): simInfo1
,I/AppUp4:EulaManager( 4072): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4072): begin check event
D/AppUp4:Utils( 4072): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4072): Event For Nothing, skip.
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5310 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5310): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5310): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5310): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  960): applying state to connected service
,D/LocationProviderProxy(  960): applying state to connected service
,I/ActivityManager(  960): Killing 4831:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5310): BUILD Country: EU
,I/SystemConfig( 5310): BUILD Operator: OPEN
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Killing 4658:com.lge.email/u0a24 (adj 15): empty #17
,I/SystemConfig( 5310): systemFeature RCS result false
,D/SystemConfig( 5310): refreshRcsSupport() :false
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5324 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5324): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5324): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5324): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  960): Killing 4884:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2687): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1969): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  960): Delaying start of: ServiceRecord{4331a4a0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageBroadcastService( 1969): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1969): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1969): GC_CONCURRENT freed 1930K, 22% free 19554K/24832K, paused 3ms+3ms, total 43ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  960): GC_EXPLICIT freed 1496K, 49% free 29881K/57872K, paused 3ms+16ms, total 144ms
,I/IcingCorporaProvider( 2687): UpdateCorporaTask done [took 411 ms] updated apps [took 411 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV4    ( 5258): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  960): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  960): [updateScreenState] screen on = false
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  960): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9703 usec
,D/qcom_sensors_hal(  960): hal_acquire_resources
,I/qcom_sensors_hal(  960): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  960): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  960): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  960): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  960): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  960): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  960): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  960): hal_sam_thresh_send_enable: Received Response: 0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.440018 Y: -0.421158 Z: 9.799454 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440018 .y:-0.421158 .z:9.799454
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.442764 Y: -0.427155 Z: 9.801514 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442764 .y:-0.427155 .z:9.801514
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Sensors (  570): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  960): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  960): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  960): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  960): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  960): proximitySensorChanged  positive = true
I/KnockOnPowerController(  960): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.451599 Y: -0.427933 Z: 9.819336 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451599 .y:-0.427933 .z:9.819336
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443985 Y: -0.428070 Z: 9.819305 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443985 .y:-0.428070 .z:9.819305
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.440933 Y: -0.425903 Z: 9.803375 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440933 .y:-0.425903 .z:9.803375
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.454346 Y: -0.418442 Z: 9.805115 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454346 .y:-0.418442 .z:9.805115
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  960): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4305cd48)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  960): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,I/WindowManager(  960): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb71f3450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.444946 Y: -0.424194 Z: 9.820267 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444946 .y:-0.424194 .z:9.820267
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  960): handleScreenStateChanged: true
,D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  960): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  960): stopMonitoring
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131127
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=132097
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  960): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2026): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  960): handleMessage: X
,E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
,V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,E/SlideAside( 3791): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433af2c0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1862): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:35:29
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3791): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
D/WeatherAncestor( 1862): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:35:29
D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
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
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in blankDisplay() while turning screen off: 413ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274529941, nextTick: 30090, mDrawingTime: 1
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 33, B = 33
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274529990, nextTick: 30042, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 27, B = 27
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
,D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:35:30
,D/WeatherService( 1862): 2 : ACTION screen on
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:35:30
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1453): Emergency Service
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qcom_sensors_hal(  960): hal_acquire_resources
D/qcom_sensors_hal(  960): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  960): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  960): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  960): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  960): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} (stop complete)
I/LGImmersionVibrator(  960): Vibrator off
D/UsbSettings( 2608): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/WifiStateMachine(  960): handleScreenStateChanged: false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
V/UsbSettings( 2608): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
D/WifiStateMachine(  960): handleMessage: X
V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1156): RESTART MSG
D/VolumeVibrator( 1156): clear
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
,D/WifiStateMachine(  960): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,I/[LGHome]EVENT( 1492): [Launcher.java:1567:onReceive()]Screen Off
V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{42cd79a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4330f208 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:35:30
,D/WeatherService( 1862): 2 : ACTION screen off
,D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:35:30
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1453): Emergency Service
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/NfcService( 1477): NFC-C OFF
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  570): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1535): Vacuum at: now=1452274538948 tag=VacuumService
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1535): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5168): [463] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5168): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1535):  no longer exists, so no auth token.
,W/Uploader( 1535): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274547605517659; DSPS: 5278810; Offset: 1452274386509021077
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  960): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274560044, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274560050, nextTick: 59961, mDrawingTime: 7
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274567607093015; DSPS: 5934222; Offset: 1452274386509009519
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274587608110248; DSPS: 6589615; Offset: 1452274386509019672
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274607609357844; DSPS: 7245016; Offset: 1452274386509016048
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274620041, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452274620046, nextTick: 59959, mDrawingTime: 10
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274627611024712; DSPS: 7900430; Offset: 1452274386509034966
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452274647612596475; DSPS: 8555842; Offset: 1452274386509019815
,I/jxcore-log( 4736): ****TEST TOOK:  ms ****
I/jxcore-log( 4736): 
,I/jxcore-log( 4736): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4736): 
,D/AndroidRuntime( 5600): 
D/AndroidRuntime( 5600): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5600): CheckJNI is OFF
,D/dalvikvm( 5600): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5600): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5600): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5600): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5600): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5600): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5600): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5600): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5600): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  960): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  960): Killing 4736:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  960):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  960):   Force finishing activity ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  960): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  960): moveHomeStack:
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
,I/WindowState(  960): WIN DEATH: Window{43cfcf78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  960): Client connection lost with reason: 4
,W/PackageSettings(  960): Skipping PackageSetting{42d2dd90 com.example.hello/10312} due to missing metadata
,V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  960): resumeTopActivityLocked: Resumed ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{43c73a28 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/ActivityManager(  960): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1492): [Launcher.java:4947:onStart()]onStart
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1492): [Launcher.java:717:onResume()]onResume
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 2663): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 2663): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
D/AppUp4:Utils( 4072): [getPackageName] uri : package:com.test.thalitest
W/System.err( 2663): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2663): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
D/AppUp4  ( 4072): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4072):  isExcludedPackage  packagename = com.test.thalitest
W/System.err( 2663): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2663): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2663): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2663): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2663): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2663): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2663): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  960):   Scheme: "sms"
,W/System.err( 2663): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2663): 	at dalvik.system.NativeStart.main(Native Method)
,D/AppUp4  ( 4072):  isExcludedPackage TRUE : com.test.thalitest
,E/SlideAside( 3791): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3791): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm( 2687): GC_EXPLICIT freed 4021K, 29% free 17878K/24832K, paused 4ms+4ms, total 74ms
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/ActivityManager(  960): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5627 uid=10090 gids={50090}
,W/GeofencerStateMachine( 1427): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5643 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/dalvikvm(  960): GC_EXPLICIT freed 1835K, 49% free 29898K/57872K, paused 3ms+8ms, total 147ms
,D/dalvikvm(  960): WAIT_FOR_CONCURRENT_GC blocked 73ms
,D/HyLog   ( 5627): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5627): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5627): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]LGActivityUtil( 1492): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
,I/[LGHome]EVENT( 1492): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
,I/[LGHome]EVENT( 1492): [Launcher.java:894:onPause()]onPause
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/HyLog   ( 5643): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5643): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5643): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
,I/[LGHome]EVENT( 1492): [Launcher.java:4955:onStop()]onStop
D/administrator(  960): Handling package changes for user 0
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1492): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/LockScreenSettings( 5627): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,W/Binder  ( 1314): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1314): java.lang.NullPointerException
W/Binder  ( 1314): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1314): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1314): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1314): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  960): IME STATUS OFF
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 4736 uid 10304
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): handleShortcutListChanged...
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
,D/[BNRAppListMgrReceiver]( 5643): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): handleShortcutListChanged...
I/ActivityManager(  960): Killing 4904:com.android.chrome/u0a63 (adj 15): empty #17
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  960): Killing 4917:com.lge.drmservice/u0a66 (adj 15): empty #17
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  960): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  960): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  960): removePackageParticipantsLocked: uid=10304 #1
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{43155460 u0 com.lge.launcher2/.Launcher t1} time:259201
I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/VoicemailCleanupService( 1820): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5659 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5659): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5659): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5659): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1140): GC_CONCURRENT freed 5043K, 9% free 70303K/76608K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 1140): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 1492): GC_CONCURRENT freed 5663K, 9% free 60777K/66644K, paused 2ms+3ms, total 41ms
,D/dalvikvm( 1492): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/LGEmail ( 5659): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5659): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/dalvikvm(  960): GC_EXPLICIT freed 642K, 49% free 29905K/57872K, paused 4ms+23ms, total 322ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/BaseRuntimeLoader( 5659): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5659): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5659): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5659): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/PackageChangeReceiver( 5659): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/PackageIntentReceiver( 2608): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2608): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2608): Delete mPackageMame : com.test.thalitest
I/ActivityManager(  960): Killing 4938:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/IcingCorporaProvider( 2687): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/ActivityManager(  960): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5682 uid=10073 gids={50073, 3003, 1028, 1015}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
D/HyLog   ( 5682): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5682): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5682): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 5600): Shutting down VM
I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/dalvikvm( 5600): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+1ms, total 2ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1492): Timeline: Activity_idle id: android.os.BinderProxy@4285f048 time:259521
,I/IcingCorporaProvider( 2687): UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GAV2    ( 5682): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  960): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5706 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/SQLiteLog( 2663): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
D/HyLog   ( 5706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5706): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SQLiteLog( 5682): (3850) statement aborts at 59: [DELETE FROM CachedSearch107 WHERE timestamp<?] disk I/O error
,E/AbstractDatabaseInstance( 5682): Failed to delete from CachedSearch107
E/AbstractDatabaseInstance( 5682): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 5682): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 5682): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AbstractDatabaseInstance( 5682): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AbstractDatabaseInstance( 5682): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 5682): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AbstractDatabaseInstance( 5682): 	at ahg.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 5682): 	at ahY.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 5682): 	at aiI.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 5682): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 5682): threadid=11: thread exiting with uncaught exception (group=0x41821e48)
,E/SQLiteDatabase( 2663): Error inserting f006=1000 f003=com.android.keychain f002=1452274650582 f005=5706 f004=13
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2663): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2663): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2663): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2663): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
E/AndroidRuntime( 5682): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 5682): Process: com.google.android.apps.docs, PID: 5682
E/AndroidRuntime( 5682): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5682): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5682): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 5682): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 5682): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5682): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 5682): 	at ahg.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 5682): 	at ahY.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 5682): 	at aiI.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 5682): 	at fv.run(DocsApplication.java:288)
,I/Process ( 5682): Sending signal. PID: 5682 SIG: 9
E/DropBoxManagerService(  960): Can't write: system_app_crash
E/DropBoxManagerService(  960): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  960): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  960): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  960): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  960): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  960): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  960): 	... 5 more
W/ContextImpl( 5706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/ActivityManager(  960): Process com.google.android.apps.docs (pid 5682) has died.
,W/ActivityManager(  960): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,E/SQLiteDatabase( 5706): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5706): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5706): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5706): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5706): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5706): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5706): threadid=10: thread exiting with uncaught exception (group=0x41821e48)
I/dalvikvm( 5168): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 5168): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 5168): VFY: replacing opcode 0x6e at 0x0013
,E/SQLiteLog( 1535): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,W/System.err( 1535): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/System.err( 1535): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,E/AndroidRuntime( 5706): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5706): Process: com.android.keychain, PID: 5706
E/AndroidRuntime( 5706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 5706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 5706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5706): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5706): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5706): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5706): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5706): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1535): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
W/System.err( 1535): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
W/System.err( 1535): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 1535): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
W/System.err( 1535): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
W/System.err( 1535): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
W/System.err( 1535): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
W/System.err( 1535): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2424)
W/System.err( 1535): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
W/System.err( 1535): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1276)
W/System.err( 1535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1535): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 1535): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 1535): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 1535): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 1535): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
I/Process ( 5706): Sending signal. PID: 5706 SIG: 9
W/System.err( 1535): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 1535): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 1535): Sending signal. PID: 1535 SIG: 9
E/DropBoxManagerService(  960): Can't write: system_app_crash
E/DropBoxManagerService(  960): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  960): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  960): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  960): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  960): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  960): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  960): 	... 5 more
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  960): Process com.android.keychain (pid 5706) has died.
W/ActivityManager(  960): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10972ms
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3b1a8 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): Process com.google.process.gapps (pid 1535) has died.
,W/ActivityManager(  960): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 10963ms
W/ActivityManager(  960): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20963ms
W/ActivityManager(  960): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 30963ms

```
