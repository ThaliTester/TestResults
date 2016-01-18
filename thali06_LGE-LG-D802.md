#### Test 5615109370bee58_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1963): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1963): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1963): No vision deps
V/ConfigFetchTask( 1963): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U44KmJ4v6BxAeQg_FqihF21yeCDs_xa7reLVSAL31mCLigbSXJQdB_vQv6lGlBEa9D7BE55CydOM3HcvLvo4-nwL1ttOPdqsZ3L8ANaG957S01XGE8NO20VRP_a6H4U-7DGE5XKv5OJobEsJxCi93RmWFbi3pZ0S5xZM4ucmNOXpp9GGgG6cX_4NAtppRiArsByIRp
I/GoogleURLConnFactory( 1963): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1963): CP2 sync disabled
I/dalvikvm( 1963): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1963): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1963): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
,--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
W/GAV2    ( 4608): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  961): Killing 4082:com.google.android.gm/u0a68 (adj 15): empty #17
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1963): fetch service done; releasing wakelock
I/ConfigFetchService( 1963): stopping self
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1963): GC_CONCURRENT freed 1506K, 22% free 19476K/24832K, paused 3ms+4ms, total 33ms
D/AndroidRuntime( 4654): 
D/AndroidRuntime( 4654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4654): CheckJNI is OFF
D/dalvikvm( 4654): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4654): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4654): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4654): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4654): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4654): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4654): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4654): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1963): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4654): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4654
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (130 us)
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  961): GC_FOR_ALLOC freed 24249K, 54% free 27987K/59820K, paused 112ms, total 112ms
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  961): startService SlideAside
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{43267670 stackId=1, 2 tasks}
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4654): Shutting down VM
D/UsbSettingsControl( 2611): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2611): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4654): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 4061): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4684 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 4061): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4061): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4684): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4684): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4684): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1963): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4684): Binding Chromium to the background looper Looper (main, tid 1) {42885518}
I/chromium( 4684): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4684): Initializing chromium process, renderers=0
W/chromium( 4684): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4684): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4684): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4684): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4684): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4684): Remote Branch: 
I/Adreno-EGL( 4684): Local Patches: 
I/Adreno-EGL( 4684): Reconstruct Branch: 
I/dalvikvm( 4684): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4684): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4684): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4684): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4684): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4684): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4684): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4684): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4684): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4684): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4684): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4684): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4684): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4684): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4684): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4684): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4684): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4684): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4684): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4684): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/BaseRuntimeLoader( 4684): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4684): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4684): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4684): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4684): Enabling debug mode 0
W/AwContents( 4684): nativeOnDraw failed; clearing to background color.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/InputMethodManagerService(  961): IME STATUS OFF
W/AwContents( 4684): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +387ms
I/ActivityManager( 4684): Timeline: Activity_idle id: android.os.BinderProxy@42886dd8 time:119652
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/JsMessageQueue( 4684): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4684): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4288aeb8
D/dalvikvm( 4684): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4288aeb8
D/jxcore_app_log( 4684): JniHelper::setJavaVM(0x41753838), pthread_self() = 1631792280
D/JX-Cordova( 4684): jxcore cordova android initializing
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} time:120021
D/UsbSettings( 2611): [AUTORUN] onStop()
D/ActivityManager(  961): no-history finish of ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{42980720 ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4684): GC_CONCURRENT freed 2667K, 12% free 21985K/24832K, paused 1ms+4ms, total 50ms
,D/dalvikvm( 4684): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 326K, 10% free 22355K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.045MB for 42652-byte allocation
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 102K, 11% free 22362K/24876K, paused 23ms, total 23ms
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 125K, 11% free 22382K/24876K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.123MB for 95956-byte allocation
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 178K, 11% free 22417K/24972K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.203MB for 143930-byte allocation
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 251K, 11% free 22464K/25116K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.317MB for 215890-byte allocation
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 366K, 12% free 22538K/25328K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.493MB for 323830-byte allocation
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 564K, 12% free 22658K/25648K, paused 24ms, total 24ms
I/dalvikvm-heap( 4684): Grow heap (frag case) to 24.764MB for 485740-byte allocation
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 858K, 13% free 22835K/26124K, paused 24ms, total 24ms
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 1083K, 12% free 23071K/26124K, paused 24ms, total 24ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 238K, 12% free 23043K/26124K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 25.719MB for 1092904-byte allocation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4684): GC_CONCURRENT freed 1901K, 14% free 23498K/27192K, paused 1ms+5ms, total 44ms
,D/dalvikvm( 4684): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 26.684MB for 1639352-byte allocation
,D/dalvikvm( 4684): GC_CONCURRENT freed 2198K, 16% free 24207K/28796K, paused 1ms+5ms, total 56ms
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 781K, 17% free 23999K/28796K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 27.955MB for 2459024-byte allocation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,D/dalvikvm( 4684): GC_CONCURRENT freed 2266K, 21% free 24771K/31200K, paused 2ms+4ms, total 62ms
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 2258K, 20% free 24989K/31200K, paused 48ms, total 48ms
,I/dalvikvm-heap( 4684): Grow heap (frag case) to 30.094MB for 3688532-byte allocation
,D/dalvikvm( 4684): GC_CONCURRENT freed 2715K, 25% free 26110K/34804K, paused 2ms+3ms, total 35ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4684): GC_FOR_ALLOC freed 2002K, 25% free 26132K/34804K, paused 29ms, total 29ms
,W/jxcore-log( 4684): Initializing JXcore engine
W/jxcore-log( 4684): JXcore engine is ready
,D/dalvikvm( 4684): GC_CONCURRENT freed 416K, 17% free 28939K/34804K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4684): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4684): Starting JXcore engine
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4684): Platform android
W/jxcore-log( 4684): 
,W/jxcore-log( 4684): Process ARCH arm
W/jxcore-log( 4684): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4684): JXcore Cordova bridge is ready!
I/jxcore-log( 4684): 
,W/jxcore-log( 4684): JXcore engine is started
,I/chromium( 4684): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4684): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4684): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4684): Toggling radios to true
I/jxcore-log( 4684): 
,D/BluetoothManagerService(  961): Message: 20
,D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43255010:true
,D/BluetoothAdapter( 4684): enable(): BT is already enabled..!
D/WifiStateMachine(  961): handleMessage: E msg.what=131145
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DISCONNECT
D/WifiService(  961): New client listening to asynchronous messages
D/WifiService(  961): setWifiEnabled: true pid=4684, uid=10304
E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  961): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  961): disconnect pid=4684, uid=10304
,I/jxcore-log( 4684): Radios toggled
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): My device name is: LGE-LG-D802
I/jxcore-log( 4684): 
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2019): TDLS: Tear down peers
,D/wpa_supplicant( 2019): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  961): reconnect pid=4684, uid=10304
,D/wpa_supplicant( 2019): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2019): wlan0: Deauthentication notification
D/wpa_supplicant( 2019): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2019): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2019): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2019): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2019): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7386d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2019): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: ConnectedState
W/Settings(  961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131146
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiNative-wlan0(  961): doBoolean: RECONNECT
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2019): Fast associate: Old scan results
D/wpa_supplicant( 2019): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2019): wlan0: nl80211: scan request
D/wpa_supplicant( 2019): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): handleMessage: X
D/wpa_supplicant( 2019): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2019): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  961): handleMessage: E msg.what=147460
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection lost
D/WifiStateMachine(  961): Stopping DHCP and clearing IP
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  961): addressRemoved: 192.168.1.151/24 on wlan0 flags 128 scope 0
,D/DhcpStateMachine(  961): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  961): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
D/QCNEA   (  509): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  509): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  509): |CAC| updateNetCfgInfo
V/QCNEA   (  509): |CAC| *********************************************
V/QCNEA   (  509): |CAC|                   Netconfig               
V/QCNEA   (  509): |CAC| *********************************************
V/QCNEA   (  509): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  509): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  509): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  509): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  509): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  509): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  509): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  509): |CAC| *********************************************
D/QCNEA   (  509): |CAC| Received bssid= 
D/QCNEA   (  509): |CAC| net type = 3
V/QCNEA   (  509): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  509): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  509): |CAC| 	ssid           =NG700
V/QCNEA   (  509): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  509): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  509): |CAC| *********************************************
D/QCNEA   (  509): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  509): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  509): |CAC| dispatchNetCfg: updating:0xb74ee8dc
D/QCNEA   (  509): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  509): Reading a NULL string not supported here.
,E/Parcel  (  509): Reading a NULL string not supported here.
D/WifiHS20(  961): hidePasspointNotification off =false
,D/QcConnectivityService(  961): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
,D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): handleMessage: X
I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4733 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  961): Attempting to switch to mobile
D/QcConnectivityService(  961): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=1 connState=2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/        (  271): RouteController
V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiController(  961): battery changed pluggedType: 2
D/HyLog   ( 4733): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4733): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4733): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
I/PCSuite ( 4733): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/        (  271): RouteController
D/PCSuite ( 4733): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4733): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/NetworkManagementService(  961): route cmd failed: 
W/NetworkManagementService(  961): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  961): '
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  961): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  961): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  961): android_net_utils_resetConnections in env=0x6183c678 clazz=0x6c600001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  961): resetConnections(wlan0, 3)
V/NativeCrypto( 1531): Read error: ssl=0x60e83410: I/O error during system call, Connection timed out
,V/NativeCrypto( 1531): SSL shutdown failed: ssl=0x60e83410: I/O error during system call, Broken pipe
I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4769 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  961): Killing 4151:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 4769): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4769): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4769): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 4769): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4769): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4769): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4769): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4769): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4769): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4769): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4769): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4769): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  961): Killing 2128:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  961): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4608): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1531): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
,D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): handleMessage: X
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4684): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4035): onReceive
D/AppUp4:CustFacade( 4035): Context : android.app.ReceiverRestrictedContext@428a54e8
D/AppUp4:CustFacade( 4035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4035): isOpenOperator : true
,D/AppUp4:CustFacade( 4035): isPhone : true
,I/LicenseContentProvider( 3013): start selecting data
,D/SIMObserver( 3013): simInfo1
,I/AppUp4:EulaManager( 4035): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4035): begin check event
,I/AppUp4:CustModeStarterReceiver( 4035): Event For GoodConnectivity
,I/ActivityManager(  961): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4799 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.478699 Y: -0.420822 Z: 9.770233 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478699 .y:-0.420822 .z:9.770233
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/HyLog   ( 4799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4799): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2019): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2019): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2019): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 2019): nl80211: Survey data missing
D/wpa_supplicant( 2019): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2019): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): BSS: last_scan_res_used=5/32 last_scan_full=0
,D/wpa_supplicant( 2019): wlan0: New scan results available
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2019): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2019): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2019): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 2019): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2019): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2019): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2019): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73885a8  current_ssid=0x0
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2019): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2019): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2019): RSN: PMKSA cache search - network_ctx=0xb73885a8 try_opportunistic=0
D/wpa_supplicant( 2019): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2019): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2019): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2019): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2019): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2019): nl80211: Unsubscribe mgmt frames handle 0xb7387590 (mode change)
D/wpa_supplicant( 2019): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb7387590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2019): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2019):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019):   * freq=2412
D/wpa_supplicant( 2019):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2019):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019):   * Auth Type 0
,D/wpa_supplicant( 2019):   * WPA Versions 0x2
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/WifiStateMachine(  961): handleMessage: E msg.what=147461
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2019): nl80211: Connect request send successfully
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2019): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.469131 Y: -0.422455 Z: 9.769974 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469131 .y:-0.422455 .z:9.769974
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/DownloadManager( 4799): DownloadService onCreate
,I/DownloadManager( 4799): in removeSpuriousFiles
D/EAS     ( 4590): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4590): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4590): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4799): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428cc798 on behalf of 4799
,I/DownloadManager( 4799): in trimDatabase
V/DownloadManager( 4799): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4799): DownloadService onStartCommand
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428ced60 on behalf of 4799
,V/DownloadManager( 4799): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428d1380 on behalf of 4799
,I/LgeMiscReceiver( 4335): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4335): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4799): DownloadService onDestroy
,I/LgeMiscReceiver( 4335): networkInfo.isConnected() = false
W/linker  ( 4590): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4590): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4590): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4590): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4590): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4590): register_HtmlEditor, Success
D/HtmlEditor( 4590): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4590): register_HtmlEditorTimer, Success
D/HtmlEditor( 4590): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4590): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4590): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4590): register_HtmlEditorFont, Success
,D/HtmlEditor( 4590): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4590): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4590): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4590): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4590): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4590): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4590): JNI_OnLoad Success
,I/HubEmail( 4590): JNI_OnLoad()
I/HubEmail( 4590): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4590): registerNatives()
I/HubEmail( 4590): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4590): registerNativeMethods()
,I/HubEmail( 4590): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4590): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  961): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4834 uid=10052 gids={50052, 3003}
,I/ActivityManager(  961): Killing 3932:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/HyLog   ( 4834): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4834): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4834): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4834): [loadRssi] File not exist 
,V/LGRssiData( 4834): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4834): [loadFeatureFromXml] *** start feature loading from xml
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2019): nl80211: Connect event
D/wpa_supplicant( 2019): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2019): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2019): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2019): wlan0: Association info event
D/wpa_supplicant( 2019): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2019): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
W/BaseRuntimeLoader( 4834): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4834): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): wlan0: freq=2412 MHz
D/wpa_supplicant( 2019): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
W/BaseRuntimeLoader( 4834): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2019): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2019): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2019): TDLS: Remove peers on association
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
W/BaseRuntimeLoader( 4834): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2019): EAPOL: enable timer tick
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  961): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
V/TelephonyAutoProfiling( 4834): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=CONNECTING
V/TelephonyAutoProfiling( 4834): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4834): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/WifiStateMachine(  961): processMsg: ConnectModeState
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  961): handleMessage: X
W/WifiMonitor(  961): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/MobileConnectivityChangeReceiver( 4834): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4834): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4834): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4834): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.455704 Y: -0.419876 Z: 9.770691 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455704 .y:-0.419876 .z:9.770691
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ...
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ab da a7 c7 b9 d5 3c f3 6a c6 0f 57 95 c5 0c 67 89
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ...
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2019): Get randomness: len=32 entropy=6
D/wpa_supplicant( 2019): WPA: Renewed SNonce - hexdump(len=32): d7 a5 00 0d 31 bb 19 96 ba 2d 96 cf 10 30 35 92 fe 56 4b 0e 51 24 d3 7f c7 99 dd 82 5b 12 db 5a
D/wpa_supplicant( 2019): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): WPA: Nonce1 - hexdump(len=32): d7 a5 00 0d 31 bb 19 96 ba 2d 96 cf 10 30 35 92 fe 56 4b 0e 51 24 d3 7f c7 99 dd 82 5b 12 db 5a
D/wpa_supplicant( 2019): WPA: Nonce2 - hexdump(len=32): 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ab da a7 c7 b9 d5 3c f3 6a c6 0f 57 95 c5 0c 67 89
D/wpa_supplicant( 2019): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2019): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): 01 5d 2c b8 9a 03 be 79 2c 3d 45 7d 06 ca 8c 7e
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 d7 a5 00 0d 31 bb 19 96 ba 2d 96 cf 10 30 35 ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4847 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  961): Killing 4321:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ...
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ab da a7 c7 b9 d5 3c f3 6a c6 0f 57 95 c5 0c 67 89
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): ca 1d 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): 10 0b b5 b9 62 41 fa fa 30 72 3b df 21 4a 5b 8e
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 5b 05 4a a3 fe a8 aa ec dd 22 d3 f4 06 7a b1 ...
D/wpa_supplicant( 2019): RSN: encrypted key data - hexdump(len=56): d5 73 ab 7d bb c8 d4 04 81 72 01 b4 7d 82 97 cb b5 bc 81 26 5b 7f 56 68 1f a6 a6 aa bd 53 a6 83 ...
D/wpa_supplicant( 2019): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 2f c5 ...
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): 3d 8a 38 d1 19 91 ff 30 85 35 db d5 f9 70 e0 84
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7387c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/HyLog   ( 4847): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4847): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4847): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2019): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2019): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2019): WPA: RSC - hexdump(len=6): ca 1d 00 00 00 00
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f3803a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2019):    broadcast key
I/wpa_supplicant( 2019): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2019): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2019): EAP: EAP entering state DISABLED
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  961): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): EAPOL authentication completed successfully
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: DisconnectedState
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection established
D/WifiNative-wlan0(  961): doString: STATUS
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2019): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  961):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  961): ssid=NG700
D/WifiNative-wlan0(  961): id=0
D/WifiNative-wlan0(  961): mode=station
D/WifiNative-wlan0(  961): pairwise_cipher=CCMP
D/WifiNative-wlan0(  961): group_cipher=CCMP
D/WifiNative-wlan0(  961): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  961): wpa_state=COMPLETED
D/WifiNative-wlan0(  961): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  961): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  961): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  961): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  961): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  961): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  961): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ObtainingIpState
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
D/DhcpStateMachine(  961): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
D/DhcpStateMachine(  961): WaitBeforeStartState
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  961): handleMessage: X
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-9ms what=147462 ,obj=android.net.wifi.StateChangeResult@43bee6b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@43bef628 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): ObtainingIpState{ when=-6ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-4ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196612
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 1
E/Parcel  (  509): Reading a NULL string not supported here.
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
E/Parcel  (  509): Reading a NULL string not supported here.
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/jxcore-log( 4684): Test app app.js loaded
I/jxcore-log( 4684): 
I/Choreographer( 4684): Skipped 214 frames!  The application may be doing too much work on its main thread.
I/ActivityManager(  961): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4860 uid=10066 gids={50066, 4002, 3003, 1028}
I/chromium( 4684): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  961): Killing 4515:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2873): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  961): Killing 4548:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2873): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4874 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4874): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  961): doBoolean: SET ps 0
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
E/WifiStateMachine(  961): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
D/DhcpStateMachine(  961): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  961): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  961): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43108c20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43108c20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGDMSGCM( 4874): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/CommandListener(  271): Setting iface cfg
,D/WifiStateMachine(  961): addressUpdated: 192.168.1.151/24 on wlan0 flags 128 scope 0
,D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  961): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  961): handleMessage: X
W/ContextImpl( 4874): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4887 uid=10101 gids={50101, 1028, 1015, 3003}
D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-8ms what=131212 obj=192.168.1.151/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196613
,D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-8ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): DHCP successful
,D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  961): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState enter
,D/WifiStateMachine(  961): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/ActivityManager(  961): Killing 4577:com.lge.bnr/1000 (adj 15): empty #17
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/WifiController(  961): battery changed pluggedType: 2
,W/WifiStateTracker(  961): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  961): 
W/WifiStateTracker(  961):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  961):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  961): send additional Connectivity Action
D/WifiStateMachine(  961): handleMessage: E msg.what=135190
D/WifiStateMachine(  961): processMsg: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  961): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  961): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState enter
D/WifiStateMachine(  961): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/WifiStateMachine(  961): handleMessage: X
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  961): handleMessage: E msg.what=131092
D/WifiStateMachine(  961): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  961): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  509): Reading a NULL string not supported here.
,D/WifiStateMachine(  961): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiStateMachine(  961): transitionTo: destState=ConnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/HyLog   ( 4887): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4887): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4887): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QcConnectivityService(  961): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  961): GC_CONCURRENT freed 1195K, 51% free 29677K/59820K, paused 4ms+6ms, total 87ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 69ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 69ms
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 69ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 69ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 67ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 67ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 69ms
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
,E/Parcel  (  509): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=2 connState=1
,V/        (  271): RouteController
,I/NFS     ( 4887): connectivityManager.getNetworkInfo = TYPE_WIFI
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/Wireless_Storage( 4887): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4887): intf.getDisplayName() = lo
I/Wireless_Storage( 4887): intf.getDisplayName() = sit0
I/Wireless_Storage( 4887): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4887): intf.getDisplayName() = teql0
I/Wireless_Storage( 4887): intf.getDisplayName() = wlan0
D/NFS     ( 4887): interface name:wlan0 name:wlan0
,V/        (  271): RouteController
D/NFS     ( 4887): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4887): interface name:wlan0 name:wlan0
D/NFS     ( 4887): addr:192.168.1.151 broadcast:192.168.1.255
,I/Wireless_Storage( 4887): CONNECT : WIFI_CONNECT
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4911 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 4200:com.android.contacts/u0a21 (adj 15): empty #17
D/HyLog   ( 4911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4911): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/QCNEA   (  509): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  509): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  509): |CAC| updateNetCfgInfo
V/QCNEA   (  509): |CAC| *********************************************
V/QCNEA   (  509): |CAC|                   Netconfig               
V/QCNEA   (  509): |CAC| *********************************************
V/QCNEA   (  509): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  509): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  509): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  509): |CAC| 	NetConfig: ip4        =192.168.1.151
V/QCNEA   (  509): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  509): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  509): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  509): |CAC| *********************************************
D/QCNEA   (  509): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  509): |CAC| net type = 1
V/QCNEA   (  509): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  509): |CAC| Received ssid= NG700
V/QCNEA   (  509): |CAC| 	ssid           =NG700
V/QCNEA   (  509): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  509): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  509): |CAC| *********************************************
D/QCNEA   (  509): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  509): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  509): |CAC| dispatchNetCfg: updating:0xb74ee8dc
D/QCNEA   (  509): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
D/DhcpStateMachine(  961): DHCP request on wlan0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LgDhcpStateMachineHelper(  961): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1963): Checking schedule, now: 1453126641002 next: 1453126576148
,I/CheckinService( 1963): active receiver: enabled
,W/GAV2    ( 4911): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinService( 1963): Preparing to send checkin request
,I/EventLogService( 1963): Accumulating logs since 1453126543551
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1531): GC_EXPLICIT freed 1057K, 29% free 17818K/24832K, paused 1ms+4ms, total 27ms
,V/WebViewChromium( 4911): Binding Chromium to the main looper Looper (main, tid 1) {428903c0}
,I/chromium( 4911): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4911): Initializing chromium process, renderers=0
,W/chromium( 4911): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4911): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4911): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4911): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4911): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4911): Remote Branch: 
I/Adreno-EGL( 4911): Local Patches: 
I/Adreno-EGL( 4911): Reconstruct Branch: 
,I/NSApplication( 4911): Starting up...
,I/ActivityManager(  961): Killing 4216:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 4769): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4769): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4769): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/QRemote ( 4769): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4769): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4769): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4733): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4733): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4769): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
,D/QRemote ( 4769): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4769): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
W/CheckinRequestBuilder( 1963): awaiting user notification for token
,I/QRemote ( 4769): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x430c61f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  961): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4960 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4960): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+1ms, total 19ms
,W/dalvikvm( 4960): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4960): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4960): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4960): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4960): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4960): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4960): install
I/MultiDex( 4960): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,I/MultiDex( 4960): loading existing secondary dex files
,I/MultiDex( 4960): load found 3 secondary dex files
,I/MultiDex( 4960): install done
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/dalvikvm( 4960): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4960): VFY: unable to resolve instance field 61
,D/dalvikvm( 4960): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4960): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4960): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4960): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4960): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4960): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4960): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4960): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4960): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4960): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42897570
D/dalvikvm( 4960): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42897570
,D/dalvikvm( 4960): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42897570, skipping init
,D/dalvikvm( 4960): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42897570
D/dalvikvm( 4960): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42897570
,V/JNIHelp ( 4960): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4960): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42897570
,D/dalvikvm( 4960): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42897570
D/dalvikvm( 4960): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42897570
,D/dalvikvm( 4960): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42897570
,I/ProviderInstaller( 4960): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1531): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1963): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1872): callingUid 10006, callindPid: 1872
,D/LocationInitializer( 1963): Restart initialization of location
,E/MDM     ( 1424): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4960): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4960): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4960): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4960): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4960): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4960): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d45000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d45000
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
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=2628040943
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DhcpStateMachine(  961): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  961): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  961): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.151
V/LgDhcpStateMachineHelper(  961): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  961): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  961): RunningState
,D/dalvikvm( 4960): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a4d840
D/dalvikvm( 4960): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a4d840
,D/dalvikvm( 4960): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a4d840, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
D/wpa_supplicant( 2019): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2019): EAPOL: disable timer tick
,W/Settings( 4960): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4960): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4999): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4960): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4960): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 4960): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4960): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4960): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4960): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4960): Remote Branch: 
I/Adreno-EGL( 4960): Local Patches: 
I/Adreno-EGL( 4960): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/WifiStateMachine(  961): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
,D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.151/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): handleMessage: X
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  961): send additional Connectivity Action
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  961): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  961):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  961): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 4960): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4960): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4960): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4960): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4960): Remote Branch: 
I/Adreno-EGL( 4960): Local Patches: 
I/Adreno-EGL( 4960): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  961): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
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
D/WVCdm   (  277): PrepareKeyRequest: nonce=4274839455
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/dalvikvm( 4684): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4684): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4684): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4684): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4684): BLE advertisement is supported
I/jxcore-log( 4684): 
,I/Adreno-EGL( 4960): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4960): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4960): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4960): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4960): Remote Branch: 
I/Adreno-EGL( 4960): Local Patches: 
I/Adreno-EGL( 4960): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1963): Sending checkin request (11587 bytes)
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
D/GCM     ( 1531): Connected
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1531): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x42c1c108: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1963): awaiting user notification for token
I/CheckinRequestBuilder( 1963): Classify the device as Phone.
I/CheckinTask( 1963): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1963): Checking schedule, now: 1453126643280 next: 1453704039276
I/CheckinService( 1963): active receiver: disabled
D/GCM     ( 1531): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  509): Reading a NULL string not supported here.
,E/Parcel  (  509): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1158): GC_CONCURRENT freed 2906K, 11% free 25449K/28532K, paused 3ms+3ms, total 66ms
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4035): onReceive
D/AppUp4:CustFacade( 4035): Context : android.app.ReceiverRestrictedContext@428a54e8
D/AppUp4:CustFacade( 4035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4035): isOpenOperator : true
D/AppUp4:CustFacade( 4035): isPhone : true
I/LicenseContentProvider( 3013): start selecting data
D/SIMObserver( 3013): simInfo1
I/AppUp4:EulaManager( 4035): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4035): begin check event
I/AppUp4:CustModeStarterReceiver( 4035): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4035): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4035): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4035): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4035): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4035): handleAsyncCustNotification do not startCustService
V/DownloadManager( 4799): DownloadService onCreate
D/EAS     ( 4590): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4799): in removeSpuriousFiles
D/EAS     ( 4590): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4799): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4590): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4335): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428d73c8 on behalf of 4799
,I/LgeMiscReceiver( 4335): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4335): networkInfo.isConnected() = false
,I/DownloadManager( 4799): in trimDatabase
,V/DownloadManager( 4799): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MobileConnectivityChangeReceiver( 4834): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4834): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428d8dc0 on behalf of 4799
,W/Settings( 4590): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4799): DownloadService onStartCommand
V/DownloadManager( 4799): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2873): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428daf70 on behalf of 4799
,D/LGDMClient( 2873): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4874): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4799): DownloadService onDestroy
,I/LGDMClient( 2873): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4887): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4887): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4874): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2873): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2873): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2873): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2873): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4035): onReceive
D/AppUp4:CustFacade( 4035): Context : android.app.ReceiverRestrictedContext@428a54e8
D/AppUp4:CustFacade( 4035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4035): isOpenOperator : true
,D/AppUp4:CustFacade( 4035): isPhone : true
,I/LicenseContentProvider( 3013): start selecting data
,D/SIMObserver( 3013): simInfo1
,I/AppUp4:EulaManager( 4035): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4035): begin check event
,I/AppUp4:CustModeStarterReceiver( 4035): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4799): DownloadService onCreate
,I/DownloadManager( 4799): in removeSpuriousFiles
V/DownloadManager( 4799): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4590): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4590): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428df260 on behalf of 4799
,V/DownloadManager( 4799): DownloadService onStartCommand
,V/DownloadManager( 4799): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4335): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4335): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4335): networkInfo.isConnected() = true
,D/PhoneState( 4335): setPdpRejectCasuse : false
W/Settings( 4590): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428e1bd0 on behalf of 4799
,I/DownloadManager( 4799): in trimDatabase
,V/DownloadManager( 4799): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MobileConnectivityChangeReceiver( 4834): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4834): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428e3468 on behalf of 4799
,V/DownloadManager( 4799): DownloadService onDestroy
,D/LGDMClient( 2873): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2873): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4874): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2873): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4887): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4887): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4874): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2873): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2873): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2873): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2873): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4035): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4035): onReceive
,D/AppUp4:CustFacade( 4035): Context : android.app.ReceiverRestrictedContext@428a54e8
,D/AppUp4:CustFacade( 4035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4035): isOpenOperator : true
,D/AppUp4:CustFacade( 4035): isPhone : true
,I/LicenseContentProvider( 3013): start selecting data
,D/SIMObserver( 3013): simInfo1
,I/AppUp4:EulaManager( 4035): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4035): begin check event
,I/AppUp4:CustModeStarterReceiver( 4035): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/EAS     ( 4590): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EAS     ( 4590): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4799): DownloadService onCreate
I/DownloadManager( 4799): in removeSpuriousFiles
V/DownloadManager( 4799): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm(  961): GC_EXPLICIT freed 2259K, 51% free 29719K/59820K, paused 3ms+6ms, total 84ms
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428e73a8 on behalf of 4799
,I/LgeMiscReceiver( 4335): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4335): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4335): networkInfo.isConnected() = true
,D/PhoneState( 4335): setPdpRejectCasuse : false
I/DownloadManager( 4799): in trimDatabase
V/DownloadManager( 4799): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4799): DownloadService onStartCommand
,V/DownloadManager( 4799): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428e8cd8 on behalf of 4799
,W/Settings( 4590): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4834): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/DownloadManager( 4799): created cursor android.database.sqlite.SQLiteCursor@428ea568 on behalf of 4799
,D/MobileConnectivityChangeReceiver( 4834): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4799): DownloadService onDestroy
,D/LGDMClient( 2873): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2873): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4874): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2873): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4887): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4887): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4874): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2873): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2873): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2873): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2873): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  961): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  961): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 4911): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  961): Killing 4608:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/Finsky  ( 4233): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4233): [1] 5.onFinished: Installation state replication succeeded.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  961): Handling package changes for user 0
,I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  961):   Scheme: "smsto"
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5119 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 4061): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/SlideAside( 4061): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5119): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5119): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5119): MmsConfig.loadMmsSettings
I/Babel   ( 5119): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5119): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5119): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5119): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5119): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5119): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5119): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5119): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5119): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5119): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5119): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5119): MmsConfig.loadFromResources
,E/Babel   ( 5119): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5119): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5119): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5119): [loadRssi] File not exist 
V/LGRssiData( 5119): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5119): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5119): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5119): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5119): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4035): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4035): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4035): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4035): onReceive
D/AppUp4:CustFacade( 4035): Context : android.app.ReceiverRestrictedContext@428a54e8
D/AppUp4:CustFacade( 4035): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4035): isOpenOperator : true
,D/AppUp4:CustFacade( 4035): isPhone : true
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/LicenseContentProvider( 3013): start selecting data
,D/SIMObserver( 3013): simInfo1
,I/AppUp4:EulaManager( 4035): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4035): begin check event
D/AppUp4:Utils( 4035): [getPackageName] uri : package:com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4035): Event For Nothing, skip.
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5169 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5169): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5169): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5169): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Killing 4733:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 5169): BUILD Country: EU
,I/SystemConfig( 5169): BUILD Operator: OPEN
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  961): Killing 4769:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5185 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,I/SystemConfig( 5169): systemFeature RCS result false
,D/SystemConfig( 5169): refreshRcsSupport() :false
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5185): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Killing 4799:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,D/LocationProviderProxy(  961): applying state to connected service
,D/LocationProviderProxy(  961): applying state to connected service
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  961): Delaying start of: ServiceRecord{445f4d60 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1963): GC_CONCURRENT freed 1946K, 22% free 19553K/24832K, paused 1ms+4ms, total 33ms
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 217 ms] updated apps [took 217 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
,I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9073 usec
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.473297 Y: -0.427505 Z: 9.771118 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473297 .y:-0.427505 .z:9.771118
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.466125 Y: -0.427444 Z: 9.769852 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466125 .y:-0.427444 .z:9.769852
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  464): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.465988 Y: -0.430481 Z: 9.777039 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465988 .y:-0.430481 .z:9.777039
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.475296 Y: -0.432343 Z: 9.774292 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475296 .y:-0.432343 .z:9.774292
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.462570 Y: -0.431564 Z: 9.763977 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462570 .y:-0.431564 .z:9.763977
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.454559 Y: -0.420197 Z: 9.764862 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454559 .y:-0.420197 .z:9.764862
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@447a0fd8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  961): No lock screen! windowToken=null
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb87be450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.460815 Y: -0.415756 Z: 9.767487 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460815 .y:-0.415756 .z:9.767487
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
,D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131127
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=132097
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
,D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  961): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2019): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
,V/voice   (  277): voice_set_parameters: enter: screen_state=on
,V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428d9de8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherAncestor( 1835): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:17:33
,E/SlideAside( 4061): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 4061): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherAncestor( 1835): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:17:33
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.478195 Y: -0.419708 Z: 9.777985 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478195 .y:-0.419708 .z:9.777985
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.472672 Y: -0.422836 Z: 9.768066 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472672 .y:-0.422836 .z:9.768066
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/qdlights( 1158): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126653678, nextTick: 26355, mDrawingTime: 0
D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126653724, nextTick: 26308, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:17:33
,D/WeatherService( 1835): 2 : ACTION screen on
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
,E/Parcel  (  509): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:17:33
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_ON
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.476791 Y: -0.429535 Z: 9.772720 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.476791 .y:-0.429535 .z:9.772720
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/LGImmersionVibrator(  961): Vibrator off
D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/UsbSettings( 2611): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/UsbSettings( 2611): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2611): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2611): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
,D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
,D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  961): CMD_SCREEN_OFF 
,D/WifiController(  961): shouldWifiStayAwake TRUE
E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1158): clear
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{42d1a4f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267670 stackId=1, 1 tasks}
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): handleMessage: X
D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:17:33
D/WeatherService( 1835): 2 : ACTION screen off
,D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:17:33
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
E/Parcel  (  509): Reading a NULL string not supported here.
,E/Parcel  (  509): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  961): Checking http://216.58.209.46/generate_204
D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2,
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  961): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  961): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  961): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  961): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/QcConnectivityService(  961): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  464): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,I/GAV4    ( 5119): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/VacuumService( 1531): Vacuum at: now=1453126663185 tag=VacuumService
,I/GoogleURLConnFactory( 1531): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1531): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1531):  no longer exists, so no auth token.
,W/Uploader( 1531): No account for auth token provided
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126671654221670; DSPS: 5284635; Offset: 1453126510379960196
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126680043, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126680056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126691656768745; DSPS: 5940078; Offset: 1453126510379974312
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126711659197435; DSPS: 6595518; Offset: 1453126510379961596
,D/wpa_supplicant( 2019): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126731662280241; DSPS: 7250979; Offset: 1453126510379962126
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126740036, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453126740046, nextTick: 59974, mDrawingTime: 4
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126751664654920; DSPS: 7906417; Offset: 1453126510379956434
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126771666693870; DSPS: 8561844; Offset: 1453126510379950706
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453126791668921467; DSPS: 9217277; Offset: 1453126510379950520
,I/jxcore-log( 4684): --= Surplus to requirements =--
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): ****TEST TOOK:  ms ****
I/jxcore-log( 4684): 
,I/jxcore-log( 4684): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4684): 
,D/AndroidRuntime( 5428): 
D/AndroidRuntime( 5428): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5428): CheckJNI is OFF
,D/dalvikvm( 5428): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5428): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5428): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5428): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5428): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5428): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5428): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5428): failed to load memtrack module: -2
,D/AndroidRuntime( 5428): Calling main entry com.android.commands.pm.Pm
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  961): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  961): Killing 4684:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  961):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  961):   Force finishing activity ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3 f}
,D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d42300 stackId=0, 1 tasks}
,I/WindowState(  961): WIN DEATH: Window{43b48e78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  961): Client connection lost with reason: 4,
,W/PackageSettings(  961): Skipping PackageSetting{42d6d6f8 com.example.hello/10312} due to missing metadata
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d42300 stackId=0, 1 tasks}
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43d21ed0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d42300 stackId=0, 1 tasks}
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/ActivityManager(  961): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d42300 stackId=0, 1 tasks}
,D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/dalvikvm( 2681): GC_EXPLICIT freed 4104K, 28% free 17919K/24832K, paused 3ms+2ms, total 43ms
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,D/AppUp4:Utils( 4035): [getPackageName] uri : package:com.test.thalitest
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
,W/System.err( 2668): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,E/SlideAside( 4061): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,D/AppUp4  ( 4035): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  961): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5446 uid=10090 gids={50090}
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  961): getAssistContextExtras failed: no resumed activity
I/SlideAside( 4061): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/AppUp4  ( 4035):  isExcludedPackage  packagename = com.test.thalitest
W/System.err( 2668): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2668): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2668): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2668): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2668): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2668): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2668): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2668): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2668): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2668): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2668): 	at dalvik.system.NativeStart.main(Native Method)
,D/AppUp4  ( 4035):  isExcludedPackage TRUE : com.test.thalitest
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  961): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5470 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,W/ActivityManager(  961): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 5446): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5446): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5446): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  961): GC_EXPLICIT freed 2975K, 49% free 30042K/58772K, paused 5ms+16ms, total 209ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 50ms
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
,I/LockScreenSettings( 5446): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
D/HyLog   ( 5470): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5470): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5470): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1142): createShortcutInfo...
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1142): createShortcutInfo...
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/KeyguardModel( 1142): createShortcutInfo...
D/administrator(  961): Handling package changes for user 0
,D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,W/Binder  ( 1315): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1315): java.lang.NullPointerException
W/Binder  ( 1315): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1315): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1315): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1315): 	at dalvik.system.NativeStart.run(Native Method)
,D/[BNRAppListMgrReceiver]( 5470): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/InputMethodManagerService(  961): IME STATUS OFF
,W/InputMethodManagerService(  961): Got RemoteException sending setActive(false) notification to pid 4684 uid 10304
D/KeyguardModel( 1142): handleShortcutListChanged...
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,I/ActivityManager(  961): Killing 4590:com.lge.email/u0a24 (adj 15): empty #17
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): handleShortcutListChanged...
I/ActivityManager(  961): Killing 4834:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,D/dalvikvm( 1489): GC_CONCURRENT freed 5143K, 9% free 60456K/65780K, paused 2ms+7ms, total 49ms
W/BroadcastQueue(  961): Exception when sending broadcast to ComponentInfo{com.lge.email/com.lge.email.receiver.PackageChangeReceiver}
W/BroadcastQueue(  961): android.os.DeadObjectException
W/BroadcastQueue(  961): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  961): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:814)
W/BroadcastQueue(  961): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:239)
W/BroadcastQueue(  961): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:895)
W/BroadcastQueue(  961): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14216)
W/BroadcastQueue(  961): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:387)
W/BroadcastQueue(  961): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2168)
W/BroadcastQueue(  961): 	at android.os.Binder.execTransact(Binder.java:407)
W/BroadcastQueue(  961): 	at dalvik.system.NativeStart.run(Native Method)
,D/VoicemailCleanupService( 1815): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  961): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5488 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/ActivityManager(  961): Process com.lge.email (pid 4590) has died and restarted (pid 5488).
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d42300 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5488): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5488): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5488): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BackupManagerService(  961): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  961): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  961): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  961): removePackageParticipantsLocked: uid=10304 #1
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/LGEmail ( 5488): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42cd56e0 u0 com.lge.launcher2/.Launcher t1} time:282894
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm(  961): GC_EXPLICIT freed 628K, 50% free 29935K/58772K, paused 3ms+12ms, total 221ms
,D/LGEmail ( 5488): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1142): GC_CONCURRENT freed 8026K, 11% free 70347K/78560K, paused 3ms+8ms, total 51ms
,D/dalvikvm( 1142): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/AndroidRuntime( 5428): Shutting down VM
,D/dalvikvm( 5428): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
W/BaseRuntimeLoader( 5488): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
W/BaseRuntimeLoader( 5488): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/BaseRuntimeLoader( 5488): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,W/BaseRuntimeLoader( 5488): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/PackageChangeReceiver( 5488): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/PackageIntentReceiver( 2611): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/HideNavigationAppsReceiver( 2611): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2611): Delete mPackageMame : com.test.thalitest
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/ActivityManager(  961): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5510 uid=10073 gids={50073, 3003, 1028, 1015}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5510): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5510): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5510): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@4288c0e0 time:283133
,D/dalvikvm( 1531): GC_CONCURRENT freed 1718K, 28% free 18027K/24832K, paused 3ms+5ms, total 38ms

```
