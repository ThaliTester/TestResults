#### Test 539786637913587_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
,W/GAV2    ( 4711): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 4124:com.google.android.gm/u0a68 (adj 15): empty #17
D/dalvikvm( 1549): GC_EXPLICIT freed 1228K, 29% free 17837K/24832K, paused 2ms+5ms, total 43ms
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1877): GC_CONCURRENT freed 1716K, 22% free 19397K/24832K, paused 4ms+5ms, total 44ms
D/dalvikvm( 1877): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/dalvikvm( 1877): WAIT_FOR_CONCURRENT_GC blocked 28ms
I/ConfigFetchService( 1877): fetch service done; releasing wakelock
I/ConfigFetchService( 1877): stopping self
D/AndroidRuntime( 4752): 
D/AndroidRuntime( 4752): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4752): CheckJNI is OFF
D/ChimeraCfgMgr( 1877): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1877): Module APK com.google.android.play.games already loaded
D/dalvikvm( 4752): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4752): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4752): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4752): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4752): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4752): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1877): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1877): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1877): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4752): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4752): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4752): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4752
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2602): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2602): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4752): Shutting down VM
D/dalvikvm( 4752): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 3ms
I/SlideAside( 3820): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4779 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3820): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3820): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4779): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/WebViewChromium( 4779): Binding Chromium to the background looper Looper (main, tid 1) {4288b978}
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
D/OpenGLRenderer( 4779): Enabling debug mode 0
W/AwContents( 4779): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
W/AwContents( 4779): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +390ms
I/ActivityManager( 4779): Timeline: Activity_idle id: android.os.BinderProxy@4288d238 time:110134
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4779): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4779): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42892c70
D/dalvikvm( 4779): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42892c70
D/jxcore_app_log( 4779): JniHelper::setJavaVM(0x41756838), pthread_self() = 1632343216
D/JX-Cordova( 4779): jxcore cordova android initializing
D/ActivityManager(  962): no-history finish of ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{42b9d600 ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2602): [AUTORUN] onStop()
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3} time:110523
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4779): GC_CONCURRENT freed 2796K, 12% free 21857K/24832K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 208K, 13% free 21832K/24832K, paused 22ms, total 23ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 187K, 12% free 21862K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 23.664MB for 146998-byte allocation
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 258K, 13% free 21911K/24976K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 23.781MB for 220492-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 374K, 13% free 21986K/25192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 23.959MB for 330734-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 581K, 14% free 22111K/25516K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.239MB for 496096-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 881K, 15% free 22289K/26004K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 24.650MB for 744140-byte allocation
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 1305K, 16% free 22550K/26732K, paused 22ms, total 22ms
,D/dalvikvm( 4779): GC_CONCURRENT freed 1671K, 15% free 22926K/26732K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/PluginManager( 4779): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 412K, 15% free 22889K/26732K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 26.123MB for 1674304-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 1799K, 18% free 23489K/28368K, paused 1ms+4ms, total 36ms
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 1323K, 18% free 23539K/28368K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 27.555MB for 2511452-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 278K, 16% free 25942K/30824K, paused 2ms+2ms, total 38ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 4400K, 21% free 24524K/30824K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4779): Grow heap (frag case) to 29.715MB for 3767174-byte allocation
,D/dalvikvm( 4779): GC_CONCURRENT freed 440K, 19% free 28008K/34504K, paused 2ms+3ms, total 45ms
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 4779): GC_FOR_ALLOC freed 2946K, 27% free 25480K/34504K, paused 26ms, total 28ms
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,W/jxcore-log( 4779): Initializing JXcore engine
W/jxcore-log( 4779): JXcore engine is ready
,D/WifiStateMachine(  962): handleMessage: X
,D/dalvikvm( 4779): GC_CONCURRENT freed 342K, 19% free 28129K/34504K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 4779): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4779): Starting JXcore engine
,W/jxcore-log( 4779): Platform android
W/jxcore-log( 4779): 
,W/jxcore-log( 4779): Process ARCH arm
W/jxcore-log( 4779): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/jxcore-log( 4779): JXcore Cordova bridge is ready!
I/jxcore-log( 4779): 
W/jxcore-log( 4779): JXcore engine is started
I/chromium( 4779): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/chromium( 4779): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4779): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/jxcore-log( 4779): Toggling radios to true
I/jxcore-log( 4779): 
D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a556a0:true
D/BluetoothAdapter( 4779): enable(): BT is already enabled..!
D/WifiStateMachine(  962): handleMessage: E msg.what=131145
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DISCONNECT
D/WifiService(  962): New client listening to asynchronous messages
D/WifiService(  962): setWifiEnabled: true pid=4779, uid=10304
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  962): disconnect pid=4779, uid=10304
I/jxcore-log( 4779): Radios toggled
I/jxcore-log( 4779): 
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2026): TDLS: Tear down peers
D/wpa_supplicant( 2026): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  962): reconnect pid=4779, uid=10304
D/wpa_supplicant( 2026): wlan0: Event DEAUTH (12) received
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
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8f06d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
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
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131146
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiNative-wlan0(  962): doBoolean: RECONNECT
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2026): Fast associate: Old scan results
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2026): wlan0: nl80211: scan request
D/wpa_supplicant( 2026): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2026): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  962): RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  962): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/QCNEA   (  685): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  685): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  685): |CAC| updateNetCfgInfo
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC|                   Netconfig               
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  685): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  685): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  685): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  685): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  685): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  685): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| Received bssid= 
D/QCNEA   (  685): |CAC| net type = 3
V/QCNEA   (  685): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  685): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  685): |CAC| 	ssid           =NG700
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  685): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  685): |CAC| dispatchNetCfg: updating:0xb7cb98dc
D/QCNEA   (  685): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiHS20(  962): hidePasspointNotification off =false
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4835 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
V/        (  264): RouteController
D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  962): '
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  962): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  962): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  962): android_net_utils_resetConnections in env=0x61f32fb0 clazz=0x6c500001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
V/NativeCrypto( 1549): Read error: ssl=0x60d4ea80: I/O error during system call, Connection timed out
V/NativeCrypto( 1549): SSL shutdown failed: ssl=0x60d4ea80: I/O error during system call, Broken pipe
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PCSuite ( 4835): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4835): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4835): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4870 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  962): Killing 4209:com.google.android.talk/u0a77 (adj 15): empty #17
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 4870): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4870): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4870): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
D/QRemote ( 4870): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4870): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.463684 Y: -0.393234 Z: 9.755890 
I/QRemote ( 4870): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463684 .y:-0.393234 .z:9.755890
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
I/QRemote ( 4870): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
I/QRemote ( 4870): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4870): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4870): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4870): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4870): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 3143:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
D/DhcpStateMachine(  962): StoppedState
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.455170 Y: -0.386703 Z: 9.759537 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455170 .y:-0.386703 .z:9.759537
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4711): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1549): onDestroy
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4779): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): my name is : LGE-LG-D802_PT3789
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): attempting to connect to test coordinator
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): check test folder
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): found test : ./testFindPeers.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): found test : ./testReConnect.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): found test : ./testSendData.js
I/jxcore-log( 4779): 
,I/jxcore-log( 4779): Test app app.js loaded
I/jxcore-log( 4779): 
,I/Choreographer( 4779): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4779): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4779): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/chromium( 4779): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4779): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4779): 
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2026): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2026): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2026): nl80211: Survey data missing
D/wpa_supplicant( 2026): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2026): wlan0: New scan results available
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2026): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2026): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2026): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2026): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8f085a8  current_ssid=0x0
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexd,ump(len=3): 2a 01 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2026): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2026): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2026): RSN: PMKSA cache search - network_ctx=0xb8f085a8 try_opportunistic=0
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
D/wpa_supplicant( 2026): nl80211: Unsubscribe mgmt frames handle 0xb8f07590 (mode change)
D/wpa_supplicant( 2026): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2026): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2026):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026):   * freq=2412
D/wpa_supplicant( 2026):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2026):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026):   * Auth Type 0
D/wpa_supplicant( 2026):   * WPA Versions 0x2
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:97]
I/ActivityManager(  962): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4904 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2026): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 ...
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 b8 2f f8 bb 58 50 88 9b a1 9a 18 41 c2 4d 33 7b 2d
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 ...
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2026): Get randomness: len=32 entropy=10
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2026): WPA: Renewed SNonce - hexdump(len=32): 53 76 24 b6 ce 17 46 04 7c dd 37 d2 fb f9 b1 92 95 62 8d d7 b0 df 5f 74 fc fa 05 39 09 0f c2 03
D/wpa_supplicant( 2026): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): WPA: Nonce1 - hexdump(len=32): 53 76 24 b6 ce 17 46 04 7c dd 37 d2 fb f9 b1 92 95 62 8d d7 b0 df 5f 74 fc fa 05 39 09 0f c2 03
D/wpa_supplicant( 2026): WPA: Nonce2 - hexdump(len=32): fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 b8 2f f8 bb 58 50 88 9b a1 9a 18 41 c2 4d 33 7b 2d
D/wpa_supplicant( 2026): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2026): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 34 d8 9d 6a 9f 12 d1 ae 92 b0 91 de 02 9d 1e 23
,D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 53 76 24 b6 ce 17 46 04 7c dd 37 d2 fb f9 b1 ...
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 ...
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 b8 2f f8 bb 58 50 88 9b a1 9a 18 41 c2 4d 33 7b 2d
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 5e 09 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): fe 64 73 45 c4 d4 6b 7a 32 58 2d a9 15 5c d3 7a
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 fe 1d 39 3a c0 cd 37 88 57 c7 cf f9 26 50 16 ...
D/wpa_supplicant( 2026): RSN: encrypted key data - hexdump(len=56): f9 92 05 15 e0 4f d1 d2 39 97 a5 aa ee d9 7d 0d 6d 22 f9 7f a0 0d 05 84 8e f1 5b db ed 3f 63 6b ...
D/wpa_supplicant( 2026): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
,D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): d7 b4 aa e2 e0 8a 2a 77 96 82 03 5b d9 ce 43 b0
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8f07c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2026): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2026): WPA: RSC - hexdump(len=6): 5e 09 00 00 00 00
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7e03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2026):    broadcast key
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2026): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2026): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): EAPOL authentication completed successfully
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection established
,D/WifiNative-wlan0(  962): doString: STATUS
,D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2026): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  962):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  962): ssid=NG700
D/WifiNative-wlan0(  962): id=0
D/WifiNative-wlan0(  962): mode=station
D/WifiNative-wlan0(  962): pairwise_cipher=CCMP
D/WifiNative-wlan0(  962): group_cipher=CCMP
D/WifiNative-wlan0(  962): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  962): wpa_state=COMPLETED
D/WifiNative-wlan0(  962): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  962): address=34:fc:ef:de:0a:e2
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  962): handleMessage: X
D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@43d3b5e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@43d77130 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-11ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,V/DownloadManager( 4904): DownloadService onCreate
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4904): in removeSpuriousFiles
,D/eas_req ( 4689): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428d22c8 on behalf of 4904
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428d52f0 on behalf of 4904
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428d7668 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onDestroy
,W/linker  ( 4689): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 4689): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4689): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4689): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4689): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 4689): register_HtmlEditor, Success
D/HtmlEditor( 4689): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4689): register_HtmlEditorTimer, Success
D/HtmlEditor( 4689): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4940 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4689): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4689): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4689): register_HtmlEditorFont, Success
D/HtmlEditor( 4689): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4689): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4689): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4689): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4689): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4689): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4689): JNI_OnLoad Success
I/HubEmail( 4689): JNI_OnLoad()
I/HubEmail( 4689): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4689): registerNatives()
I/HubEmail( 4689): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4689): registerNativeMethods()
I/HubEmail( 4689): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4940): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326edd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326edd0 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  962): Killing 3973:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  962): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): DHCP successful
V/LGRssiData( 4940): [loadRssi] File not exist 
V/LGRssiData( 4940): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4940): [loadFeatureFromXml] *** start feature loading from xml
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4940): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
,D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
,D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
V/TelephonyAutoProfiling( 4940): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4940): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4940): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/WifiStateMachine(  962): handleMessage: X
W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4940): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4940): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4955 uid=10063 gids={50063, 3003, 1028, 1015}
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  962): Killing 4373:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
I/CheckinService( 1877): Checking schedule, now: 1450442870011 next: 1450442815533
,I/CheckinService( 1877): active receiver: enabled
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4955): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/CheckinService( 1877): Preparing to send checkin request
,I/EventLogService( 1877): Accumulating logs since 1450442782872
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/QCNEA   (  685): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  685): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  685): |CAC| updateNetCfgInfo
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC|                   Netconfig               
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  685): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  685): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  685): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  685): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  685): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  685): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  685): |CAC| net type = 1
V/QCNEA   (  685): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  685): |CAC| Received ssid= NG700
V/QCNEA   (  685): |CAC| 	ssid           =NG700
V/QCNEA   (  685): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  685): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  685): |CAC| dispatchNetCfg: updating:0xb7cb98dc
D/QCNEA   (  685): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1877): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  962): GC_EXPLICIT freed 23374K, 49% free 29711K/57592K, paused 4ms+10ms, total 159ms
E/ActivityThread( 1877): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4994 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  962): Killing 4607:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4994): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Killing 4649:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5007 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/HyLog   ( 5007): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5007): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5007): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5007): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
W/ContextImpl( 5007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5023 uid=10101 gids={50101, 1028, 1015, 3003}
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/ActivityManager(  962): Killing 4677:com.lge.bnr/1000 (adj 15): empty #17
D/WifiController(  962): battery changed pluggedType: 2
D/WifiController(  962): battery changed pluggedType: 2
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
,D/HyLog   ( 5023): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5023): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5023): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 5023): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5023): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5023): intf.getDisplayName() = lo
I/Wireless_Storage( 5023): intf.getDisplayName() = sit0
I/Wireless_Storage( 5023): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5023): intf.getDisplayName() = teql0
I/Wireless_Storage( 5023): intf.getDisplayName() = wlan0
D/NFS     ( 5023): interface name:wlan0 name:wlan0
,D/NFS     ( 5023): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5023): interface name:wlan0 name:wlan0
D/NFS     ( 5023): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 5023): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5035 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4261:com.android.contacts/u0a21 (adj 15): empty #17
,D/HyLog   ( 5035): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5035): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5035): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1877): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x433e6788: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GAV2    ( 5035): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5053 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5053): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5053): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5053): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5053): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5053): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5053): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5053): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5053): install
I/MultiDex( 5053): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5053): loading existing secondary dex files
,I/MultiDex( 5053): load found 3 secondary dex files
,I/MultiDex( 5053): install done
,D/dalvikvm( 5053): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5053): VFY: unable to resolve instance field 61
,D/dalvikvm( 5053): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5053): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5053): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5053): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5053): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5053): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5053): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5053): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5053): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5053): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42892330
,D/dalvikvm( 5053): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42892330
,D/dalvikvm( 5053): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42892330, skipping init
,D/dalvikvm( 5053): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42892330
D/dalvikvm( 5053): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42892330
,V/JNIHelp ( 5053): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5035): Binding Chromium to the main looper Looper (main, tid 1) {4288aca8}
,I/chromium( 5035): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5035): Initializing chromium process, renderers=0
,W/chromium( 5035): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5035): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5035): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5035): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5035): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5035): Remote Branch: 
I/Adreno-EGL( 5035): Local Patches: 
I/Adreno-EGL( 5035): Reconstruct Branch: 
,D/dalvikvm( 5053): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42892330
,D/dalvikvm( 5053): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42892330
D/dalvikvm( 5053): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42892330
,D/dalvikvm( 5053): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42892330
,I/NSApplication( 5035): Starting up...
,I/ActivityManager(  962): Killing 4276:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4870): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4870): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4870): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4870): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 5053): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4870): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4870): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4835): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4835): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4870): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4870): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4870): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4870): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1549): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1549): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1549): Proximity feature is not enabled.
,I/dalvikvm( 5053): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5053): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5053): VFY: replacing opcode 0x6e at 0x000d
,V/GmsCoreStatsServiceLauncher( 1877): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 5053): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5053): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5053): VFY: replacing opcode 0x6e at 0x0201
,D/WearableService( 3451): callingUid 10006, callindPid: 3451
,D/LocationInitializer( 1877): Restart initialization of location
,E/MDM     ( 1427): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2079000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2079000
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
,D/wpa_supplicant( 2026): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2026): EAPOL: disable timer tick
D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1906563170
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5053): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6cc98
D/dalvikvm( 5053): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6cc98
,D/dalvikvm( 5053): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6cc98, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 5053): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3377473730
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4779): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4779): 
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 5053): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5098): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5053): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5053): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 5053): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5053): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5053): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5053): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5053): Remote Branch: 
I/Adreno-EGL( 5053): Local Patches: 
I/Adreno-EGL( 5053): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/Adreno-EGL( 5053): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5053): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5053): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5053): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5053): Remote Branch: 
I/Adreno-EGL( 5053): Local Patches: 
I/Adreno-EGL( 5053): Reconstruct Branch: 
,I/Adreno-EGL( 5053): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5053): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5053): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5053): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5053): Remote Branch: 
I/Adreno-EGL( 5053): Local Patches: 
I/Adreno-EGL( 5053): Reconstruct Branch: 
,D/GCM     ( 1549): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1549): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  962): handleMessage: X
,D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/CheckinRequestBuilder( 1877): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1877): Sending checkin request (11586 bytes)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1877): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1877): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x42c814c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1877): awaiting user notification for token
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1877): Classify the device as Phone.
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1877): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/CheckinService( 1877): Checking schedule, now: 1450442872746 next: 1451020268738
I/CheckinService( 1877): active receiver: disabled
,D/GCM     ( 1549): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  685): Reading a NULL string not supported here.
,E/Parcel  (  685): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
,D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4091): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4091): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4091): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4091): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4091): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4904): DownloadService onCreate
,I/DownloadManager( 4904): in removeSpuriousFiles
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428dd700 on behalf of 4904
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4689): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428df0f8 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428e12a8 on behalf of 4904
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4904): DownloadService onDestroy
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5007): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 5007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 5023): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5023): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4904): DownloadService onCreate
,I/DownloadManager( 4904): in removeSpuriousFiles
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428e5e60 on behalf of 4904
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428e7a60 on behalf of 4904
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428e8fb0 on behalf of 4904
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,V/DownloadManager( 4904): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5007): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5023): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5023): CONNECT : WIFI_CONNECT
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/dalvikvm( 4779): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4779): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4779): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4779): Shutting down VM
,W/dalvikvm( 4779): threadid=1: thread exiting with uncaught exception (group=0x41851e48)
,D/dalvikvm( 1877): GC_CONCURRENT freed 1817K, 22% free 19519K/24832K, paused 3ms+4ms, total 47ms
E/AndroidRuntime( 4779): FATAL EXCEPTION: main
E/AndroidRuntime( 4779): Process: com.test.thalitest, PID: 4779
E/AndroidRuntime( 4779): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4779): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4779): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4779): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4779): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4779): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4779): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4779): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4779): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4779): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4779): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4779): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4779): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4779): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4779): 	at dalvik.system.NativeStart.main(Native Method)
,D/dalvikvm(  962): GC_EXPLICIT freed 2095K, 49% free 29595K/57592K, paused 3ms+7ms, total 107ms
W/ActivityManager(  962):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): Activity pause timeout for ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{431c8d50 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  962): moveHomeStack:
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1492): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1492): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]LGActivityUtil( 1492): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1492): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1814): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:47:53
,D/UpdateThreadPoolManager( 1814): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1814): 2 : quick cover state : opened : 0
,D/WeatherService( 1814): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1814): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1814): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1814): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1814): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1814): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:47:53
,D/WeatherService( 1814): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherQuickCover( 1814): 2 : quick cover state : opened : 0
D/Weather.Utils( 1814): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1814): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1814): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1814): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1814): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1814): 2 : This is isUpdating : false
D/WeatherService( 1814): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1814): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1814): 2 : Map key string is -2
D/lim     ( 1814): 2 : time = 13:47
I/WeatherReflect( 1814): Model Name : LG-D802
D/WeatherTheme( 1814): 2 : Different view - status_min_formatted : 46 != 47
D/WeatherTheme( 1814): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1814): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1814): 2 : Fixed theme : optimus
D/WeatherTheme( 1814): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1814): 2 : quick cover state : opened : 0
D/Weather.Utils( 1814): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1814): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1814): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 7030K, 10% free 71222K/78532K, paused 29ms, total 29ms
,D/dalvikvm( 1492): GC_CONCURRENT freed 5523K, 9% free 60854K/66576K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 1492): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1492): GC_FOR_ALLOC freed 4867K, 9% free 61910K/67600K, paused 19ms, total 19ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager( 1492): Timeline: Activity_idle id: android.os.BinderProxy@4288f060 time:121009
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/UsbSettings( 2602): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
V/UsbSettings( 2602): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{430f94f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1} time:121022
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiController(  962): battery changed pluggedType: 2
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4904): DownloadService onCreate
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4904): in removeSpuriousFiles
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428ed198 on behalf of 4904
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428ee268 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428f0d40 on behalf of 4904
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/MobileConnectivityChangeReceiver( 4940): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4904): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4940): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5007): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5023): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5023): CONNECT : WIFI_CONNECT
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  962): battery changed pluggedType: 2
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GAV2    ( 5035): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 4711:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState,
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]NumberBadge.LGBroadCastBadge( 1492): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Killing 4294:com.android.vending/u0a50 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5256 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5256): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5256): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5256): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5256): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/dalvikvm( 5256): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5256): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x004f
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  962): battery changed pluggedType: 2
,D/Finsky  ( 5256): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5256): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5256): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5256): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5256): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5256): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5256): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5256): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5256): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5256): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5256): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5256): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5256): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 5256): VFY: replacing opcode 0x6e at 0x0049
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428f5ee0 on behalf of 5256
,D/Finsky  ( 5256): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5256): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5256): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5256): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5256): Total arena pages for JIT: 11
,I/dalvikvm( 5256): Total arena pages for JIT: 12
I/dalvikvm( 5256): Total arena pages for JIT: 13
,I/dalvikvm( 5256): Total arena pages for JIT: 14
,D/Finsky  ( 5256): [468] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5256): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  962): Killing 4835:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5256): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5256): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5256): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5256): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5256): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1549): GC_EXPLICIT freed 1155K, 29% free 17830K/24832K, paused 3ms+5ms, total 47ms
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5256): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5256): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5256): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5256): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5256): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.470444 Y: -0.399063 Z: 9.751205 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470444 .y:-0.399063 .z:9.751205
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.456299 Y: -0.383789 Z: 9.773911 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456299 .y:-0.383789 .z:9.773911
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442880041, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442880044, nextTick: 59988, mDrawingTime: 0
,D/WeatherService( 1814): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:48:0
,D/WeatherService( 1814): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1814): 2 : SDK version : 19
,D/WeatherQuickCover( 1814): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1814): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1814): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1814): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1814): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1814): 2 : This is isUpdating : false
,D/WeatherService( 1814): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1814): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1814): 2 : Map key string is -2
,D/lim     ( 1814): 2 : time = 13:48
,I/WeatherReflect( 1814): Model Name : LG-D802
,D/WeatherTheme( 1814): 2 : Different view - status_min_formatted : 47 != 48
,D/WeatherTheme( 1814): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1814): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1814): 2 : Fixed theme : optimus
,D/WeatherTheme( 1814): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1814): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:48:0
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/SlideAside( 3820): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
D/administrator(  962): Handling package changes for user 0
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5343 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5343): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Scheme: "mmsto"
,D/dalvikvm(  962): GC_CONCURRENT freed 2207K, 47% free 30677K/57592K, paused 4ms+6ms, total 85ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5343): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5343): MmsConfig.loadMmsSettings
,I/Babel   ( 5343): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/MediaCodecList( 5343): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/Babel   ( 5343): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5343): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5343): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5343): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5343): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5343): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5343): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5343): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5343): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5343): MmsConfig.loadFromResources
,E/Babel   ( 5343): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5343): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5343): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5343): [loadRssi] File not exist 
V/LGRssiData( 5343): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5343): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4091): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4091): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/TelephonyAutoProfiling( 5343): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5343): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5343): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4091): Event For Nothing, skip.
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5390 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1427): DISABLE
,D/HyLog   ( 5390): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5390): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5390): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  962): Killing 4870:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,D/LocationProviderProxy(  962): applying state to connected service
,I/SystemConfig( 5390): BUILD Country: EU
,I/SystemConfig( 5390): BUILD Operator: OPEN
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/SystemConfig( 5390): systemFeature RCS result false
,D/SystemConfig( 5390): refreshRcsSupport() :false
I/ActivityManager(  962): Killing 4779:com.test.thalitest/u0a304 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LocationProviderProxy(  962): applying state to connected service
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5406 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5406): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5406): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5406): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1158): GC_CONCURRENT freed 2867K, 11% free 25446K/28492K, paused 2ms+2ms, total 18ms
I/WindowState(  962): WIN DEATH: Window{45043030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  962): Client connection lost with reason: 4
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/[LGHome]EVENT( 1492): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{43defb38 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
D/WifiController(  962): battery changed pluggedType: 2
I/InputMethodManagerService(  962): IME STATUS OFF
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Binder  ( 1311): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1311): java.lang.NullPointerException
W/Binder  ( 1311): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1311): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1311): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1311): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 4779 uid 10304
,I/ActivityManager(  962): Killing 4940:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2678): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1877): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1877): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  962): Delaying start of: ServiceRecord{434564d0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1877): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2678): UpdateCorporaTask done [took 217 ms] updated apps [took 217 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1221): Disconnected process message: 10
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://173.194.44.37/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GAV4    ( 5343): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
,I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6905 usec
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/qcom_sensors_hal(  962): hal_acquire_resources
I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.458908 Y: -0.380539 Z: 9.750275 ,
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458908 .y:-0.380539 .z:9.750275
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21,
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.470734 Y: -0.382339 Z: 9.755325 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470734 .y:-0.382339 .z:9.755325
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0,
,I/Sensors (  664): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.471848 Y: -0.386124 Z: 9.766068 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471848 .y:-0.386124 .z:9.766068
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.474075 Y: -0.401749 Z: 9.761322 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.474075 .y:-0.401749 .z:9.761322
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.477753 Y: -0.394226 Z: 9.772156 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.477753 .y:-0.394226 .z:9.772156
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.472397 Y: -0.387939 Z: 9.767807 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472397 .y:-0.387939 .z:9.767807
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.469086 Y: -0.385925 Z: 9.787735 
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.469086 Y: -0.408081 Z: 9.804352 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.469086 .y:-0.385925 .z:9.787735
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@431caba8)
,D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1144): notifyScreenOnLocked
,D/KeyguardViewMediator( 1144): handleNotifyScreenOn
,D/KeyguardViewManager( 1144): onScreenTurnedOn()
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
,I/WindowManager(  962): No lock screen! windowToken=null
D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb7b8b450
D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2026): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428dcf88 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1814): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:48:12
,I/SlideAside( 3820): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1814): 2 : This is isUpdating : false
,D/WeatherAncestor( 1814): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:48:12
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/WeatherService( 1814): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1814): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1814): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1814): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1158): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 405ms
D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442892481, nextTick: 47550, mDrawingTime: 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442892528, nextTick: 47504, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1814): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:48:12
,D/WeatherService( 1814): 2 : ACTION screen on
,D/WeatherService( 1814): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/WeatherService( 1814): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:48:12
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,E/Parcel  (  685): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/GsmSST  ( 1452): Emergency Service
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1144): notifyScreenOffLocked
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,I/[LGHome]EVENT( 1492): [Launcher.java:894:onPause()]onPause
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  962): Vibrator off
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/[LGHome]EVENT( 1492): [Launcher.java:4955:onStop()]onStop
,D/WifiStateMachine(  962): handleScreenStateChanged: false
D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42cc31c0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
,D/KeyguardViewMediator( 1144): handleNotifyScreenOff
,D/KeyguardViewManager( 1144): onScreenTurnedOff()
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1158): clear
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,I/[LGHome]EVENT( 1492): [Launcher.java:1567:onReceive()]Screen Off
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,E/Parcel  (  685): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WeatherService( 1814): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:48:12
,D/WeatherService( 1814): 2 : ACTION screen off
D/WeatherService( 1814): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:48:12
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/NfcService( 1477): NFC-C OFF
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  664): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450442900228682275; DSPS: 4950830; Offset: 1450442749141340967
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigFetchService( 1877): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1877): running network task: configservice_periodic
,E/WakeLock( 1877): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1877): launchTask
,I/ConfigService( 1549): onCreate
,I/ConfigFetchService( 1877): service connected
,I/VacuumService( 1549): Vacuum at: now=1450442902356 tag=VacuumService
,D/ConfigFetchService( 1877): ConfigApi connection successful.
,D/Finsky  ( 5256): [468] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5256): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/ConfigFetchTask( 1877): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VmP2TMih_RGc47a1tm_PtliJ3XY0kg8SqGPWWzGPTFRK4srLottWFkBGutB_0Kzn6XVZizW2sdva9dB6dL6tNzlAV-IZmWWJ5Bs_g1NhDaqWHzOGiFExczGm3OVa49l6doK3r7wrLIcLad1sxVQSm5qtHZegdagYF6iVs2Pq_AymfHZ5TF4sZojCc6_aAReUUjMJCK
,I/GoogleURLConnFactory( 1877): Using platform SSLCertificateSocketFactory
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ConfigFetchTask( 1877): updating config table for com.google.android.gms
,I/ConfigFetchService( 1877): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1877): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1877): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1877): fetch service done; releasing wakelock
,I/ConfigFetchService( 1877): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1877): stopping self
,I/GoogleURLConnFactory( 1549): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1549): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1549): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1549): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1549): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1549): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1549): No account for auth token provided
,W/Uploader( 1549): No account for auth token provided
,W/Uploader( 1549):  no longer exists, so no auth token.
,W/Uploader( 1549): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/ConfigService( 1549): onDestroy
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450442920229589921; DSPS: 5606220; Offset: 1450442749141333086
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442940042, nextTick: 59988, mDrawingTime: 1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450442940044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450442940230510458; DSPS: 6261610; Offset: 1450442749141338095
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450442960231470464; DSPS: 6917002; Offset: 1450442749141321539
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450442980232306378; DSPS: 7572389; Offset: 1450442749141333478
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1464): GC_CONCURRENT freed 1539K, 7% free 25440K/27280K, paused 8ms+2ms, total 32ms
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443000050, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443000054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443000234572227; DSPS: 8227823; Offset: 1450442749141341026
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443020235021922; DSPS: 8883198; Offset: 1450442749141332958
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443040235907847; DSPS: 9538587; Offset: 1450442749141333873
,D/wpa_supplicant( 2026): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 6 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 7 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81],
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 fc:94:e3:11:35:3a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 fe:94:e3:11:35:3c]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11],
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443060042, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443060055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443060236418692; DSPS: 10193964; Offset: 1450442749141325919
,D/dalvikvm( 2666): GC_CONCURRENT freed 7759K, 32% free 16894K/24832K, paused 2ms+1ms, total 37ms
,D/dalvikvm( 2666): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443080237317215; DSPS: 10849353; Offset: 1450442749141339432
,I/LocationManagerService(  962): remove 430ffa48
D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2666): GC_CONCURRENT freed 1866K, 32% free 17075K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2666): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2666): GC_CONCURRENT freed 1855K, 31% free 17268K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2666): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2666): parseLastkmsg to dump
,D/dalvikvm( 2666): GC_CONCURRENT freed 1310K, 28% free 17901K/24832K, paused 3ms+2ms, total 36ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443100237775454; DSPS: 11504728; Offset: 1450442749141339908
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443120077, nextTick: 59953, mDrawingTime: 3
D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443120078, nextTick: 59955, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443120238691222; DSPS: 12160118; Offset: 1450442749141340148
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443140242554308; DSPS: 12815605; Offset: 1450442749141327502
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443160243452130; DSPS: 13470994; Offset: 1450442749141340314
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1549): GC_CONCURRENT freed 1820K, 28% free 18052K/24832K, paused 3ms+5ms, total 115ms
,D/dalvikvm( 1549): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1549): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1549): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1549): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1549): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1549): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1549): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1549): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1549): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x43300b10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/PlayEventLogger( 5256): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5256): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5256): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5256): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5256): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5256): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5256): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5256): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5256): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5256): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm(  962): GC_EXPLICIT freed 2613K, 47% free 30708K/57592K, paused 4ms+14ms, total 149ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443180047, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443180054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443180244368608; DSPS: 14126384; Offset: 1450442749141341265
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443200244822233; DSPS: 14781759; Offset: 1450442749141337126
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443220249758976; DSPS: 15437281; Offset: 1450442749141330021
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443240031, nextTick: 59975, mDrawingTime: 10
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443240049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443240250220174; DSPS: 16092656; Offset: 1450442749141333456
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2,
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443260251101601; DSPS: 16748045; Offset: 1450442749141329873
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443280251551668; DSPS: 17403419; Offset: 1450442749141352694
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443300024, nextTick: 59992, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443300056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443300253867563; DSPS: 18058855; Offset: 1450442749141349253
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443320254734276; DSPS: 18714244; Offset: 1450442749141330956
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443340255189950; DSPS: 19369619; Offset: 1450442749141328867
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443360026, nextTick: 59992, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443360058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443360257955143; DSPS: 20025069; Offset: 1450442749141347477
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443380258842708; DSPS: 20680458; Offset: 1450442749141350033
,I/ActivityManager(  962): Killing 4955:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Disconnect event
D/wpa_supplicant( 2026): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2026): wlan0: Deauthentication notification
D/wpa_supplicant( 2026): wlan0:  * reason 0
D/wpa_supplicant( 2026): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2026): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2026): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2026): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
,D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8f06d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
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
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/DhcpStateMachine(  962): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2026): wlan0: nl80211: scan request
,D/wpa_supplicant( 2026): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  962): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2026): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,E/Parcel  (  685): Reading a NULL string not supported here.
D/QCNEA   (  685): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  685): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  685): |CAC| updateNetCfgInfo
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC|                   Netconfig               
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  685): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  685): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  685): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  685): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  685): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  685): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| Received bssid= 
D/QCNEA   (  685): |CAC| net type = 3
V/QCNEA   (  685): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  685): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  685): |CAC| 	ssid           =NG700
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  685): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  685): |CAC| dispatchNetCfg: updating:0xb7cb98dc
,D/QCNEA   (  685): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6041 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,D/HyLog   ( 6041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6041): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  962): '
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  962): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  962): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x61f32fb0 clazz=0xb6600001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1549): Read error: ssl=0x63e79bd8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1549): SSL shutdown failed: ssl=0x63e79bd8: I/O error during system call, Broken pipe
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,I/PCSuite ( 6041): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6041): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6041): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6083 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 4994:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/DhcpStateMachine(  962): StoppedState
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6083): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6083): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6083): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 6083): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6083): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 6083): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6083): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6083): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6083): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6083): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6083): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6083): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 5007:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443400259762887; DSPS: 21335849; Offset: 1450442749141324167
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4689): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6113 uid=10052 gids={50052, 3003}
,W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2026): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2026): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 2026): nl80211: Survey data missing
D/wpa_supplicant( 2026): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 11 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 12 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 2026): wlan0: New scan results available
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2026): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2026): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2026): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2026): wlan0: 2: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-89 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 caps=0x511 level=-89
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 caps=0x511 level=-89
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2026): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c0:ff:d,4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2026): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2026): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8f085a8  current_ssid=0x0
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
,D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2026): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2026): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2026): RSN: PMKSA cache search - network_ctx=0xb8f085a8 try_opportunistic=0,
D/wpa_supplicant( 2026): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2026): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2026): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 2026): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2026): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2026): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2026): nl80211: Unsubscribe mgmt frames handle 0xb8f07590 (mode change)
D/wpa_supplicant( 2026): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8f07590,
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
,D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590,
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
,D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb8f07590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2026): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2026):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026):   * freq=2412
D/wpa_supplicant( 2026):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2026):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026):   * Auth Type 0
D/wpa_supplicant( 2026):   * WPA Versions 0x2
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 fc:94:e3:11:35:3a],
D/wpa_supplicant( 2026): nl80211: Connect request send successfully
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 fe:94:e3:11:35:3c]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
D/wpa_supplicant( 2026): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 2026): nl80211: Connect event
D/wpa_supplicant( 2026): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2026): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2026): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2026): wlan0: Association info event
D/wpa_supplicant( 2026): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2026): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): wlan0: freq=2412 MHz
D/wpa_supplicant( 2026): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
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
,D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2026): EAPOL: enable timer tick
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/HyLog   ( 6113): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6113): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6113): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 ...
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 2c 2d b5 49 9a 31 c4 46 d8 ff f9 ee 39 26 6a 92 86
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 ...
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2026): Get randomness: len=32 entropy=6
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/wpa_supplicant( 2026): WPA: Renewed SNonce - hexdump(len=32): cd 01 38 f4 b7 74 7a e7 de 40 c7 42 15 ef a2 c6 17 20 96 3a 9d f1 1e 51 c0 19 f3 60 63 bf ba 1f
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/wpa_supplicant( 2026): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): WPA: Nonce1 - hexdump(len=32): cd 01 38 f4 b7 74 7a e7 de 40 c7 42 15 ef a2 c6 17 20 96 3a 9d f1 1e 51 c0 19 f3 60 63 bf ba 1f
D/wpa_supplicant( 2026): WPA: Nonce2 - hexdump(len=32): 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 2c 2d b5 49 9a 31 c4 46 d8 ff f9 ee 39 26 6a 92 86
D/wpa_supplicant( 2026): WPA: PMK - hexdump(len=32): [REMOVED]
D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2026): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 5a e2 e0 65 88 52 34 39 b7 89 8b 0c f1 7b 97 62
,D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 cd 01 38 f4 b7 74 7a e7 de 40 c7 42 15 ef a2 ...
,D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 ...,
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
,D/wpa_supplicant( 2026): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 2c 2d b5 49 9a 31 c4 46 d8 ff f9 ee 39 26 6a 92 86
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 18 0d 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 7a 16 65 1c 05 17 1b 12 dc 36 30 18 86 a0 5b 0e
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 67 23 74 4f d2 72 13 b3 a1 c8 5c 14 af f6 d7 ...
D/wpa_supplicant( 2026): RSN: encrypted key data - hexdump(len=56): 7d a3 43 43 51 04 c6 9d ee ad e9 79 23 b6 a9 0f dd 08 84 15 71 c7 ea b6 5f 9f 06 bf d4 80 05 44 ...
D/wpa_supplicant( 2026): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 24 5e 9d 92 64 02 62 72 48 d5 a6 ba 4b 57 a9 4d
D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8f07c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2026): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2026): WPA: RSC - hexdump(len=6): 18 0d 00 00 00 00
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7e03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2026):    broadcast key
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiStateMachine(  962): handleMessage: X
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/wpa_supplicant( 2026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2026): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2026): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2026): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): EAPOL authentication completed successfully
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection established
,D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2026): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiNative-wlan0(  962):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  962): ssid=NG700
D/WifiNative-wlan0(  962): id=0
D/WifiNative-wlan0(  962): mode=station
D/WifiNative-wlan0(  962): pairwise_cipher=CCMP
D/WifiNative-wlan0(  962): group_cipher=CCMP
D/WifiNative-wlan0(  962): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  962): wpa_state=COMPLETED
D/WifiNative-wlan0(  962): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  962): address=34:fc:ef:de:0a:e2
V/LGRssiData( 6113): [loadRssi] File not exist 
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
V/LGRssiData( 6113): [loadRssi] File not exist 
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
V/TelephonyAutoProfiling( 6113): [loadFeatureFromXml] *** start feature loading from xml
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/BaseRuntimeLoader( 6113): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/BaseRuntimeLoader( 6113): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6113): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
W/BaseRuntimeLoader( 6113): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  962): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-17ms what=147462 obj=android.net.wifi.StateChangeResult@43143550 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): proce,ssMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@4341e768 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-11ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/MobileConnectivityChangeReceiver( 6113): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6113): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 6113): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6113): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6113): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 6113): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6113): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6144 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 5023:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6144): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  269): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 32ms
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 27ms
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  962): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326edd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326edd0 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6159 uid=10066 gids={50066, 4002, 3003, 1028}
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-12ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,I/ActivityManager(  962): Killing 5035:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-12ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
,D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  962): handleMessage: X
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
E/Parcel  (  685): Reading a NULL string not supported here.
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
,D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/HyLog   ( 6159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6159): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/WifiStateMachine(  962): handleMessage: X
,D/HyLog   ( 6159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
,E/Parcel  (  685): Reading a NULL string not supported here.
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
E/Parcel  (  685): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,I/ActivityManager(  962): Killing 5053:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6173 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,W/ActivityManager(  962): Failed to clear dns cache for: com.google.android.gms
,V/        (  264): RouteController
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 6173): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6173): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6173): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,D/LGDMSGCM( 6173): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/        (  264): RouteController
W/ContextImpl( 6173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6199 uid=10101 gids={50101, 1028, 1015, 3003}
,V/        (  264): RouteController
I/ActivityManager(  962): Killing 5343:com.google.android.talk/u0a77 (adj 15): empty #17
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/QCNEA   (  685): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  685): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  685): |CAC| updateNetCfgInfo
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC|                   Netconfig               
V/QCNEA   (  685): |CAC| *********************************************
V/QCNEA   (  685): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  685): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  685): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  685): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  685): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  685): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  685): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  685): |CAC| net type = 1
V/QCNEA   (  685): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  685): |CAC| Received ssid= NG700
V/QCNEA   (  685): |CAC| 	ssid           =NG700
V/QCNEA   (  685): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  685): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  685): |CAC| *********************************************
D/QCNEA   (  685): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  685): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  685): |CAC| dispatchNetCfg: updating:0xb7cb98dc
,D/QCNEA   (  685): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 6199): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6199): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6199): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1877): Checking schedule, now: 1450443402254 next: 1450442902738
,I/CheckinService( 1877): active receiver: enabled
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinService( 1877): Preparing to send checkin request
,I/EventLogService( 1877): Accumulating logs since 1450442870046
,I/NFS     ( 6199): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6199): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6199): intf.getDisplayName() = lo
I/Wireless_Storage( 6199): intf.getDisplayName() = sit0
I/Wireless_Storage( 6199): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6199): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6199): intf.getDisplayName() = wlan0
D/NFS     ( 6199): interface name:wlan0 name:wlan0
D/NFS     ( 6199): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 6199): interface name:wlan0 name:wlan0
D/NFS     ( 6199): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 6199): CONNECT : WIFI_CONNECT
,I/CheckinRequestBuilder( 1877): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6222 uid=10104 gids={50104, 3003, 1028, 1015}
E/ActivityThread( 1877): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6222): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 6222): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1877): awaiting user notification for token
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x45060e20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6242 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,V/WebViewChromium( 6222): Binding Chromium to the main looper Looper (main, tid 1) {4288c828}
D/HyLog   ( 6242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/chromium( 6222): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
D/HyLog   ( 6242): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/BrowserProcessMain( 6222): Initializing chromium process, renderers=0
,W/chromium( 6222): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,W/dalvikvm( 6242): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6242): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6242): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6242): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6242): VFY: replacing opcode 0x62 at 0x005e
,I/Adreno-EGL( 6222): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6222): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6222): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6222): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6222): Remote Branch: 
I/Adreno-EGL( 6222): Local Patches: 
I/Adreno-EGL( 6222): Reconstruct Branch: 
I/MultiDex( 6242): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6242): install
,I/MultiDex( 6242): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6242): loading existing secondary dex files
,I/MultiDex( 6242): load found 3 secondary dex files
,I/MultiDex( 6242): install done
,D/dalvikvm( 6242): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6242): VFY: unable to resolve instance field 61
,D/dalvikvm( 6242): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6242): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6242): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6242): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6242): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6242): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6242): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6242): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6242): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6242): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42894778
,D/dalvikvm( 6242): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42894778
,D/dalvikvm( 6242): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42894778, skipping init
,D/dalvikvm( 6242): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42894778
D/dalvikvm( 6242): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42894778
,V/JNIHelp ( 6242): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 6222): Starting up...
,D/dalvikvm( 6242): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42894778
,D/dalvikvm( 6242): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42894778
D/dalvikvm( 6242): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42894778
,D/dalvikvm( 6242): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42894778
,I/ActivityManager(  962): Killing 5390:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6083): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6083): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6083): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6083): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6083): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6083): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6041): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6041): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6083): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6083): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6083): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6083): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 6242): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1549): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1549): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1549): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1877): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 6242): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 6242): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6242): VFY: replacing opcode 0x6e at 0x000d
,D/WearableService( 3451): callingUid 10006, callindPid: 3451
,I/dalvikvm( 6242): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6242): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6242): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1877): Restart initialization of location
,E/MDM     ( 1427): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2079000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2079000
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=3372331597
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6242): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab2418
,D/dalvikvm( 6242): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab2418
,D/dalvikvm( 6242): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab2418, skipping init
,D/wpa_supplicant( 2026): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2026): EAPOL: disable timer tick
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 6242): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2916107351
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 6242): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/WifiStateMachine(  962): handleMessage: X
,D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6287): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6242): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6242): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 146ms
,I/Adreno-EGL( 6242): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6242): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6242): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6242): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6242): Remote Branch: 
I/Adreno-EGL( 6242): Local Patches: 
I/Adreno-EGL( 6242): Reconstruct Branch: 
,I/Adreno-EGL( 6242): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6242): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6242): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6242): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6242): Remote Branch: 
I/Adreno-EGL( 6242): Local Patches: 
I/Adreno-EGL( 6242): Reconstruct Branch: 
,I/Adreno-EGL( 6242): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6242): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6242): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6242): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6242): Remote Branch: 
I/Adreno-EGL( 6242): Local Patches: 
I/Adreno-EGL( 6242): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1877): Classify the device as Phone.
,V/NativeCrypto( 1877): SSL shutdown failed: ssl=0x6c8659e0: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1877): GC_CONCURRENT freed 1960K, 22% free 19575K/24832K, paused 2ms+3ms, total 36ms
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,V/NativeCrypto( 1877): SSL shutdown failed: ssl=0x6c8a1db0: I/O error during system call, Connection timed out
,I/CheckinTask( 1877): Sending checkin request (11587 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4091): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4091): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4091): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4091): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4091): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4904): DownloadService onCreate
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4689): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
,I/DownloadManager( 4904): in removeSpuriousFiles
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 6113): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6113): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428fa9a0 on behalf of 4904
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428fc850 on behalf of 4904
W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@428fe588 on behalf of 4904
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMSGCM( 6173): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 6199): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6199): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4904): DownloadService onDestroy
,W/ContextImpl( 6173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4904): DownloadService onCreate
,I/DownloadManager( 4904): in removeSpuriousFiles
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 6113): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6113): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 6173): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NFS     ( 6199): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6199): CONNECT : WIFI_CONNECT
,W/ContextImpl( 6173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm(  962): GC_EXPLICIT freed 2545K, 47% free 30609K/57592K, paused 7ms+9ms, total 133ms
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@42902ca8 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onStartCommand
,V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@429051e8 on behalf of 4904
,I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@42906310 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4091): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4091): isOpenOperator : true
,D/AppUp4:CustFacade( 4091): isPhone : true
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4091): begin check event
,I/AppUp4:CustModeStarterReceiver( 4091): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4904): DownloadService onCreate
,D/EAS     ( 4689): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6113): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6113): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6173): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6199): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6199): CONNECT : WIFI_CONNECT
,I/DownloadManager( 4904): in removeSpuriousFiles
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@4290a4f8 on behalf of 4904
,V/DownloadManager( 4904): DownloadService onStartCommand
V/DownloadManager( 4904): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4904): in trimDatabase
,V/DownloadManager( 4904): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@4290c8a0 on behalf of 4904
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4904): created cursor android.database.sqlite.SQLiteCursor@4290e060 on behalf of 4904
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 4904): DownloadService onDestroy
,I/CheckinRequestBuilder( 1877): Checkin reason type: 8 attempt count: 1
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3999): GC_FOR_ALLOC freed 374K, 2% free 37783K/38444K, paused 43ms, total 54ms
E/ActivityThread( 1877): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1877): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x441e69b0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1877): Classify the device as Phone.
,I/CheckinTask( 1877): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1877): Checking schedule, now: 1450443406833 next: 1451020802829
,I/CheckinService( 1877): active receiver: disabled
,I/CheckinService( 1877): Checking schedule, now: 1450443406864 next: 1451020802829
,I/CheckinService( 1877): active receiver: disabled
,D/GCM     ( 1549): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1549): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1549): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 6222): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 5256:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  962): Killing 5406:com.android.gallery3d/u0a27 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3820): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6428 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6428): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/MediaCodecList( 6428): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/Babel   ( 6428): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6428): MmsConfig.loadMmsSettings
,I/MediaCodecList( 6428): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6428): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6428): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 6428): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6428): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 6428): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6428): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6428): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6428): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/GmsNetworkLocationProvi( 1427): DISABLE
E/Babel   ( 6428): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6428): MmsConfig.loadFromResources
,E/Babel   ( 6428): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6428): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 6428): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationProviderProxy(  962): applying state to connected service
,D/LocationProviderProxy(  962): applying state to connected service
,D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4091): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4091): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 6428): [loadRssi] File not exist 
V/LGRssiData( 6428): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6428): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 4091): onReceive
,V/TelephonyAutoProfiling( 6428): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:CustFacade( 4091): Context : android.app.ReceiverRestrictedContext@428a0338
V/TelephonyAutoProfiling( 6428): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
D/AppUp4:CustFacade( 4091): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4091): isOpenOperator : true
D/AppUp4:CustFacade( 4091): isPhone : true
,V/TelephonyAutoProfiling( 6428): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 3040): start selecting data
,D/SIMObserver( 3040): simInfo1
,I/AppUp4:EulaManager( 4091): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4091): begin check event
D/AppUp4:Utils( 4091): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4091): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6475 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6475): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6475): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6475): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6475): BUILD Country: EU
,I/SystemConfig( 6475): BUILD Operator: OPEN
I/ActivityManager(  962): Killing 6041:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 6475): systemFeature RCS result false
,D/SystemConfig( 6475): refreshRcsSupport() :false
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6492 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6492): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6492): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6492): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 6083:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): Killing 4904:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2678): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6509 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6509): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6509): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6509): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6509): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 6509): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6509): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6509): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6509): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6509): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6509): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6509): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6509): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6509): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2678): UpdateCorporaTask done [took 231 ms] updated apps [took 231 ms] 
,W/Settings( 6509): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6509): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6509): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6509): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6509): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6509): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x0292
,I/dalvikvm( 6509): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6509): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 6509): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6509): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x001a
,I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6543 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/dalvikvm( 6509): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6509): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 6509): VFY: replacing opcode 0x6e at 0x0049
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6543): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6543): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6543): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Finsky  ( 6509): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6509): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  962): Killing 4689:com.lge.email/u0a24 (adj 15): empty #17
,D/PackageBroadcastService( 1877): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1877): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Icing   ( 1877): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6543): DownloadService onCreate
,I/DownloadManager( 6543): in removeSpuriousFiles
,V/DownloadManager( 6543): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6543): DownloadService onStartCommand
,V/DownloadManager( 6543): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6543): created cursor android.database.sqlite.SQLiteCursor@428d5c10 on behalf of 6543
,V/DownloadManager( 6543): created cursor android.database.sqlite.SQLiteCursor@428d7ec0 on behalf of 6543
,I/DownloadManager( 6543): in trimDatabase
,V/DownloadManager( 6543): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6543): created cursor android.database.sqlite.SQLiteCursor@428dcdf8 on behalf of 6543
,V/DownloadManager( 6543): DownloadService onDestroy
,V/DownloadManager( 6543): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6543): created cursor android.database.sqlite.SQLiteCursor@428e0570 on behalf of 6509
,D/Finsky  ( 6509): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6509): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6509): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6509): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6509): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6509): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm(  962): GC_EXPLICIT freed 2164K, 47% free 30672K/57592K, paused 5ms+15ms, total 170ms
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6509): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1549): GC_EXPLICIT freed 1302K, 28% free 18016K/24832K, paused 2ms+4ms, total 31ms
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6509): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6509): Total arena pages for JIT: 11
,I/dalvikvm( 6509): Total arena pages for JIT: 12
,I/dalvikvm( 6509): Total arena pages for JIT: 13
,I/dalvikvm( 6509): Total arena pages for JIT: 14
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
,W/Finsky  ( 6509): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6509): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6509): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6509): [1] DailyHygiene.reschedule: Scheduling new run in 84 minutes (failures=3)
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6428): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 6113:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c59170 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443420024, nextTick: 60001, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443420055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443420260756203; DSPS: 21991241; Offset: 1450442749141340920
,D/Finsky  ( 6509): [516] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6509): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443440261219811; DSPS: 22646616; Offset: 1450442749141346765
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443460262096035; DSPS: 23302005; Offset: 1450442749141337979
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443480043, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443480055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443480266191608; DSPS: 23957499; Offset: 1450442749141344196
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443500267097836; DSPS: 24612889; Offset: 1450442749141334897
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443520267554672; DSPS: 25268264; Offset: 1450442749141333969
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443540029, nextTick: 59993, mDrawingTime: 6
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443540063, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443540268015645; DSPS: 25923639; Offset: 1450442749141337179
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443560268941267; DSPS: 26579030; Offset: 1450442749141316756
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443580269388897; DSPS: 27234404; Offset: 1450442749141337140
,D/wpa_supplicant( 2026): wlan0: BSS: Remove id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 11 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 12 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 fc:94:e3:11:35:3a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 fe:94:e3:11:35:3c]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443600047, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443600050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443600269850209; DSPS: 27889779; Offset: 1450442749141340688
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443620270312903; DSPS: 28545154; Offset: 1450442749141345618
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443640282288489; DSPS: 29200907; Offset: 1450442749141327796
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443660048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443660051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443660283357758; DSPS: 29856302; Offset: 1450442749141328950
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443680283792695; DSPS: 30511676; Offset: 1450442749141336641
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443700293521403; DSPS: 31167355; Offset: 1450442749141330241
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x433bd328: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1549): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1549): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1549): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1549): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1549): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1549): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1549): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1549): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 6509): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6509): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6509): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6509): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6509): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6509): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6509): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6509): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6509): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6509): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443720033, nextTick: 59990, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443720040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443720294952028; DSPS: 31822762; Offset: 1450442749141326540
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443740295392443; DSPS: 32478136; Offset: 1450442749141339709
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443760295844111; DSPS: 33133511; Offset: 1450442749141333613,
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443780046, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443780053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443780296325806; DSPS: 33788887; Offset: 1450442749141327027
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443800297639637; DSPS: 34444290; Offset: 1450442749141328602
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443820298074966; DSPS: 35099664; Offset: 1450442749141336685
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443840047, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443840055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443840301922096; DSPS: 35755150; Offset: 1450442749141338600
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443860316242113; DSPS: 36410979; Offset: 1450442749141345873
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443880316670721; DSPS: 37066353; Offset: 1450442749141347235
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443900032, nextTick: 59999, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443900050, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443900317121199; DSPS: 37721728; Offset: 1450442749141339949
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443920318010944; DSPS: 38377117; Offset: 1450442749141344685
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443940318909721; DSPS: 39032507; Offset: 1450442749141327934
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443960053, nextTick: 59978, mDrawingTime: 1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450443960055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443960319389597; DSPS: 39687882; Offset: 1450442749141350047
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450443980320718924; DSPS: 40343286; Offset: 1450442749141336600
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444000321178496; DSPS: 40998661; Offset: 1450442749141338409
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444020040, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444020050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444020321643205; DSPS: 41654036; Offset: 1450442749141345354
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444040322948469; DSPS: 42309439; Offset: 1450442749141338362
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444060323407294; DSPS: 42964814; Offset: 1450442749141339423
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444080043, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444080053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444080324626957; DSPS: 43620214; Offset: 1450442749141338383
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444100325954825; DSPS: 44275618; Offset: 1450442749141323478
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444120326395305; DSPS: 44930992; Offset: 1450442749141336712
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444140042, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444140045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444140330823074; DSPS: 45586497; Offset: 1450442749141339432
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444160332175239; DSPS: 46241902; Offset: 1450442749141318306
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444180332610911; DSPS: 46897276; Offset: 1450442749141326732
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444200047, nextTick: 59975, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444200053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444200333089719; DSPS: 47552651; Offset: 1450442749141347776
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444220334030062; DSPS: 48208042; Offset: 1450442749141342074
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444240334477612; DSPS: 48863417; Offset: 1450442749141331861
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444260028, nextTick: 60003, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444260046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444260337948546; DSPS: 49518891; Offset: 1450442749141323791
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7405
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444280337519009; DSPS: 50174236; Offset: 1450442749141352017
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444300338413108; DSPS: 50829626; Offset: 1450442749141330589
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444320047, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444320050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444320338871569; DSPS: 51485001; Offset: 1450442749141331286
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444340340261609; DSPS: 52140407; Offset: 1450442749141317518
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444360341341762; DSPS: 52795802; Offset: 1450442749141329555
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444380048, nextTick: 59980, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444380051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444380342915803; DSPS: 53451213; Offset: 1450442749141347200
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444400344244609; DSPS: 54106617; Offset: 1450442749141333233
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444420344694584; DSPS: 54761992; Offset: 1450442749141325444
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444440042, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444440055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444440347462038; DSPS: 55417442; Offset: 1450442749141346316
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444460348793439; DSPS: 56072846; Offset: 1450442749141334943
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444480349250838; DSPS: 56728221; Offset: 1450442749141334579
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444500039, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444500042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444500349852850; DSPS: 57383601; Offset: 1450442749141326239
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444520362509489; DSPS: 58039375; Offset: 1450442749141348601
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444540363389101; DSPS: 58694764; Offset: 1450442749141343203
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444560054, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444560055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444560364346556; DSPS: 59350156; Offset: 1450442749141324096,
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,I/ProcessStatsService(  962): Prepared write state in 61ms
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-42-05.bin
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1549): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1549): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1549): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1549): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1549): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1877): Aggregate from 1450443402285 (log), 1450442209302 (data)
,D/GCM     ( 1549): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Auth    ( 1549): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444580365757125; DSPS: 60005562; Offset: 1450442749141330856
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444600367100294; DSPS: 60660966; Offset: 1450442749141331252
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444620035, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450444620042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444620367990025; DSPS: 61316355; Offset: 1450442749141335973
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444640369334941; DSPS: 61971759; Offset: 1450442749141338115
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450444660370230366; DSPS: 62627148; Offset: 1450442749141348531
,TIME-OUT KILL (timeout was 1800000ms)
```
