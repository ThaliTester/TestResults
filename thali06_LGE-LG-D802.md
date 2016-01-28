#### Test 573480789efee08_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/GAV2    ( 4597): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  963): Killing 3577:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43624840 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1966): GC_CONCURRENT freed 1665K, 22% free 19528K/24836K, paused 3ms+8ms, total 51ms
D/dalvikvm( 1966): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1966): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1966): Loaded CLD2 Version V2.0 - 20141016
I/ConfigFetchService( 1966): fetch service done; releasing wakelock
I/ConfigFetchService( 1966): stopping self
I/Icing   ( 1966): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4647): 
D/AndroidRuntime( 4647): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4647): CheckJNI is OFF
D/dalvikvm( 4647): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4647): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4647): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4647): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4647): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4647): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4647): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4647): failed to load memtrack module: -2
D/AndroidRuntime( 4647): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4647
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43624840 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (132 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  963): GC_FOR_ALLOC freed 24383K, 54% free 28007K/59884K, paused 117ms, total 117ms
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{43624840 stackId=1, 2 tasks}
D/AndroidRuntime( 4647): Shutting down VM
D/UsbSettingsControl( 2584): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2584): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3751): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4647): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43624840 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3751): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3751): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4665 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4665): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4665): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4665): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4665): Binding Chromium to the background looper Looper (main, tid 1) {42bc8740}
I/chromium( 4665): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4665): Initializing chromium process, renderers=0
W/chromium( 4665): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4665): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4665): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4665): Remote Branch: 
I/Adreno-EGL( 4665): Local Patches: 
I/Adreno-EGL( 4665): Reconstruct Branch: 
I/dalvikvm( 4665): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4665): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4665): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4665): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4665): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4665): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4665): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4665): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4665): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4665): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4665): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4665): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4665): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4665): Enabling debug mode 0
,W/AwContents( 4665): nativeOnDraw failed; clearing to background color.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,I/InputMethodManagerService(  963): IME STATUS OFF
W/AwContents( 4665): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +477ms
,I/ActivityManager( 4665): Timeline: Activity_idle id: android.os.BinderProxy@42bc9f10 time:108985
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/JsMessageQueue( 4665): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4665): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bcdff0
,D/dalvikvm( 4665): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bcdff0
,D/jxcore_app_log( 4665): JniHelper::setJavaVM(0x41b7e808), pthread_self() = 1632491320
,I/chromium( 4665): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3} time:109267
D/ActivityManager(  963): no-history finish of ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{4362ea80 ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,D/UsbSettings( 2584): [AUTORUN] onStop()
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,I/chromium( 4665): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4665): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4665): GC_CONCURRENT freed 2680K, 12% free 21973K/24836K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 338K, 10% free 22362K/24836K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.055MB for 42652-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 104K, 11% free 22369K/24880K, paused 23ms, total 24ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 125K, 11% free 22389K/24880K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.132MB for 95956-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 179K, 11% free 22424K/24976K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.212MB for 143930-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 254K, 11% free 22471K/25120K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.327MB for 215890-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 366K, 12% free 22545K/25332K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.502MB for 323830-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 566K, 12% free 22665K/25652K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.774MB for 485740-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 862K, 13% free 22841K/26128K, paused 26ms, total 26ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 1128K, 12% free 23083K/26128K, paused 27ms, total 27ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 203K, 12% free 23045K/26128K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 25.724MB for 1092904-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 1803K, 14% free 23492K/27196K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 159K, 14% free 23450K/27196K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 26.641MB for 1639352-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 1945K, 17% free 24022K/28800K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 993K, 17% free 23985K/28800K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 27.945MB for 2459024-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 2063K, 21% free 24777K/31204K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 4665): GC_CONCURRENT freed 2450K, 20% free 25015K/31204K, paused 2ms+4ms, total 37ms
,D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 30.124MB for 3688532-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 371K, 19% free 28470K/34808K, paused 2ms+8ms, total 48ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
D/dalvikvm( 4665): GC_FOR_ALLOC freed 4362K, 25% free 26146K/34808K, paused 28ms, total 28ms
W/jxcore-log( 4665): Initializing JXcore engine
W/jxcore-log( 4665): JXcore engine is ready
D/dalvikvm( 4665): GC_CONCURRENT freed 423K, 17% free 28950K/34808K, paused 1ms+1ms, total 30ms
D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 27ms
W/jxcore-log( 4665): Starting JXcore engine
D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/jxcore-log( 4665): Platform android
W/jxcore-log( 4665): 
W/jxcore-log( 4665): Process ARCH arm
W/jxcore-log( 4665): 
I/GAV2    ( 4597): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4665): JXcore Cordova bridge is ready!
I/jxcore-log( 4665): 
,W/jxcore-log( 4665): JXcore engine is started
,E/jxcore  ( 4665): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4665): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4665): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  963): Finishing activity token=Token{443d37d0 ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  963): GC_FOR_ALLOC freed 1143K, 51% free 29588K/59884K, paused 78ms, total 78ms
,W/PluginManager( 4665): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 90ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43624840 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1451): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1841): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:47:17
D/UpdateThreadPoolManager( 1841): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1841): 2 : quick cover state : opened : 0
,D/WeatherService( 1841): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1841): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1841): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1841): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1841): 2 : TimeTick Receiver Register
,I/[LGHome]EVENT( 1491): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherAncestor( 1841): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:47:17
,D/WeatherService( 1841): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1841): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1841): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1841): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1841): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1841): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1841): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/InputMethodManagerService(  963): IME STATUS OFF
W/IInputConnectionWrapper( 4665): showStatusIcon on inactive InputConnection
D/UpdateThreadPoolManager( 1841): 2 : This is isUpdating : false
D/WeatherService( 1841): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1841): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1841): 2 : Map key string is -2
D/lim     ( 1841): 2 : time = 12:47
I/WeatherReflect( 1841): Model Name : LG-D802
D/WeatherTheme( 1841): 2 : Different view - status_min_formatted : 45 != 47
D/WeatherTheme( 1841): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1841): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1841): 2 : Fixed theme : optimus
D/WeatherTheme( 1841): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1841): 2 : quick cover state : opened : 0
D/Weather.Utils( 1841): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1841): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1841): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1491): GC_CONCURRENT freed 5251K, 9% free 60778K/66212K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 6572K, 10% free 71276K/78832K, paused 32ms, total 36ms
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1491): GC_FOR_ALLOC freed 5107K, 9% free 62063K/68024K, paused 17ms, total 17ms
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@42bcded8 time:112314
,D/UsbSettings( 2584): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2584): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43676640 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  963): Killing 4143:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1} time:112386
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4665): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{454cc2b0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
,I/ConfigService( 1538): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.583450 Y: -0.336594 Z: 9.802643 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.583450 .y:-0.336594 .z:9.802643
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.579620 Y: -0.344177 Z: 9.806076 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579620 .y:-0.344177 .z:9.806076
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1491): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4227): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4227): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.562637 Y: -0.322052 Z: 9.810059 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.562637 .y:-0.322052 .z:9.810059
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.579285 Y: -0.316879 Z: 9.828949 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579285 .y:-0.316879 .z:9.828949
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1158): GC_CONCURRENT freed 2911K, 11% free 25448K/28540K, paused 29ms+2ms, total 83ms
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8431 usec
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.579239 Y: -0.330048 Z: 9.825394 
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.581451 Y: -0.311172 Z: 9.845383 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.579239 .y:-0.330048 .z:9.825394
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.579422 Y: -0.345459 Z: 9.805817 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579422 .y:-0.345459 .z:9.805817
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  477): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.585022 Y: -0.317612 Z: 9.836914 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.585022 .y:-0.317612 .z:9.836914
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.572983 Y: -0.316605 Z: 9.834351 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572983 .y:-0.316605 .z:9.834351
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.569992 Y: -0.311508 Z: 9.826660 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569992 .y:-0.311508 .z:9.826660
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.572937 Y: -0.318024 Z: 9.819672 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572937 .y:-0.318024 .z:9.819672
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43455700)
,D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1144): notifyScreenOnLocked
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.566803 Y: -0.320312 Z: 9.825165 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.566803 .y:-0.320312 .z:9.825165
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8d2e450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
D/KeyguardViewMediator( 1144): handleNotifyScreenOn
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewManager( 1144): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
I/WindowManager(  963): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2028): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,D/wpa_supplicant( 2028): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=132097
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  963): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2028): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2028): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  963): handleMessage: X
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{42c21320 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.574738 Y: -0.320709 Z: 9.823807 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.574738 .y:-0.320709 .z:9.823807
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/WeatherAncestor( 1841): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:47:44
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3751): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1841): 2 : This is isUpdating : false
,D/WeatherAncestor( 1841): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:47:44
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/WeatherService( 1841): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1841): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.586807 Y: -0.324539 Z: 9.822372 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586807 .y:-0.324539 .z:9.822372
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
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
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 413ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981664968, nextTick: 15063, mDrawingTime: 1
D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981665019, nextTick: 15014, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,D/WeatherService( 1841): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:45
D/WeatherService( 1841): 2 : ACTION screen on
,D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1841): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:45
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_ON
D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1144): notifyScreenOffLocked
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  963): hal_acquire_resources
I/[LGHome]EVENT( 1491): [Launcher.java:894:onPause()]onPause
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  963): Vibrator off
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
I/[LGHome]EVENT( 1491): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/KeyguardViewMediator( 1144): handleNotifyScreenOff
D/KeyguardViewManager( 1144): onScreenTurnedOff()
E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{433e5698 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  963): CMD_SCREEN_OFF 
,D/WifiController(  963): shouldWifiStayAwake TRUE
D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): handleMessage: X
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1158): clear
D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=2
D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/WeatherService( 1841): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:45
D/WeatherService( 1841): 2 : ACTION screen off
,D/WeatherService( 1841): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:45
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1476): NFC-C OFF
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_OFF
D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  477): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981680052, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981680055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981682728922659; DSPS: 5283606; Offset: 1453981521486063773
,I/GoogleURLConnFactory( 1538): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1538): No account for auth token provided
,D/dalvikvm( 1538): null clazz in OP_INSTANCE_OF, single-stepping
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538):  no longer exists, so no auth token.
,W/Uploader( 1538): No account for auth token provided
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981702730261817; DSPS: 5939010; Offset: 1453981521486060157
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981722731541393; DSPS: 6594412; Offset: 1453981521486057995
,I/EventLogService( 1966): Aggregate from 1453981554195 (log), 1453979920388 (data)
,D/wpa_supplicant( 2028): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 2 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:37:b7:9d:3e:73]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981740050, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981740055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981742732872271; DSPS: 7249815; Offset: 1453981521486076617
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981762734754972; DSPS: 7905237; Offset: 1453981521486067228
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981782736047464; DSPS: 8560639; Offset: 1453981521486077982
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981800032, nextTick: 59988, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981800041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981802737355894; DSPS: 9216042; Offset: 1453981521486074156
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981822738667813; DSPS: 9871445; Offset: 1453981521486073819
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981842739531607; DSPS: 10526833; Offset: 1453981521486083121
,D/dalvikvm( 2638): GC_CONCURRENT freed 7799K, 33% free 16762K/24836K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981860041, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981860055, nextTick: 59977, mDrawingTime: 0
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x4302e750: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4227): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4227): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4227): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4227): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4227): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4227): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4227): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4227): 	at dalvik.system.NativeStart.run(Native Method),
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4227): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4227): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981862740867537; DSPS: 11182237; Offset: 1453981521486076278
,I/LocationManagerService(  963): remove 42f9f1d8
,D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2638): GC_CONCURRENT freed 1573K, 31% free 17236K/24836K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2638): GC_CONCURRENT freed 1931K, 31% free 17352K/24836K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2638): GC_FOR_ALLOC freed 1356K, 30% free 17593K/24836K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2638): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981882742175238; DSPS: 11837640; Offset: 1453981521486071723
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981902742602418; DSPS: 12493014; Offset: 1453981521486071657
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981920033, nextTick: 59981, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981920058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981922743923088; DSPS: 13148417; Offset: 1453981521486080071
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981942744791883; DSPS: 13803806; Offset: 1453981521486063856
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981962746276042; DSPS: 14459214; Offset: 1453981521486083171
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981980045, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453981980055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453981982746716762; DSPS: 15114589; Offset: 1453981521486066128
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982002748021026; DSPS: 15769991; Offset: 1453981521486088653
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982022748882945; DSPS: 16425380; Offset: 1453981521486065563
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982040050, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982040055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982042750186896; DSPS: 17080783; Offset: 1453981521486057258
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Disconnect event
D/wpa_supplicant( 2028): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2028): wlan0: Deauthentication notification
D/wpa_supplicant( 2028): wlan0:  * reason 0
D/wpa_supplicant( 2028): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2028): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2028): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2028): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  963): handleMessage: E msg.what=147460
,D/WifiStateMachine(  963): processMsg: ConnectedState,
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState,
,D/WifiStateMachine(  963): Network connection lost
,D/WifiStateMachine(  963): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 1,
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85d4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  963): addressRemoved: 192.168.1.157/24 on wlan0 flags 128 scope 0
D/DhcpStateMachine(  963): RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= 
D/QCNEA   (  501): |CAC| net type = 3
V/QCNEA   (  501): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  501): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
,D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  963): hidePasspointNotification off =false
D/wpa_supplicant( 2028): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2028): wlan0: nl80211: scan request
D/wpa_supplicant( 2028): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2028): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  963): Attempting to switch to mobile
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
,I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5227 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5227): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PCSuite ( 5227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,D/PCSuite ( 5227): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/NetworkManagementService(  963): route cmd failed: 
W/NetworkManagementService(  963): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  963): '
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  963): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  963): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x61edbd98 clazz=0x62500001 iface=wlan0 mask=0x3
I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5270 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  963): Killing 3906:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
D/HyLog   ( 5270): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5270): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5270): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/NativeCrypto( 1538): Read error: ssl=0x64103f20: I/O error during system call, Connection timed out
V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x64103f20: I/O error during system call, Broken pipe
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/DhcpStateMachine(  963): StoppedState
,D/QRemote ( 5270): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5270): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5270): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5270): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 5270): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5270): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5270): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5270): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5270): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 3127:android.process.media/u0a23 (adj 15): empty #17
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2028): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2028): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2028): nl80211: Survey data missing
D/wpa_supplicant( 2028): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 3 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 4 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2028): wlan0: New scan results available
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2028): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2028): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2028): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2028): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2028): wlan0: 2: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-90 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2028): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2028): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2028): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2028): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85d65a8  current_ssid=0x0
D/wpa_supplicant( 2028): scard is not null..
D/wpa_suppl,icant( 2028): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2028): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2028): wlan0: Cancelling scan request
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2028): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2028): RSN: PMKSA cache search - network_ctx=0xb85d65a8 try_opportunistic=0
D/wpa_supplicant( 2028): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2028): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2028): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2028): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2028): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2028): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
,D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2028): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2028): nl80211: Unsubscribe mgmt frames handle 0xb85d5590 (mode change)
D/wpa_supplicant( 2028): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
,D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590,
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590,
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590,
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2028): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2028):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028):   * freq=2412
D/wpa_supplicant( 2028):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2028):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2028):   * Auth Type 0
D/wpa_supplicant( 2028):   * WPA Versions 0x2
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 00:37:b7:9d:3e:73]
,D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState,
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2028): nl80211: Connect request send successfully
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2028): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2028): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Connect event
D/wpa_supplicant( 2028): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2028): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2028): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2028): wlan0: Association info event
D/wpa_supplicant( 2028): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2028): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): wlan0: freq=2412 MHz
D/wpa_supplicant( 2028): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2028): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): scard is not null..
D/wpa_supplicant( 2028): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2028): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2028): TDLS: Remove peers on association
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2028): EAPOL: enable timer tick
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: Cancelling scan request
,D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d ...
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d c2 f8 76 89 3a 84 c3 43 b5 61 c6 85 01 8f cc 33 cf
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d ...
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2028): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2028): WPA: Renewed SNonce - hexdump(len=32): 53 d6 e6 03 39 ba 68 b1 22 06 19 88 a7 58 b9 a6 7c e7 2f dc 34 72 20 44 a6 90 01 49 49 1d 54 d3
,D/wpa_supplicant( 2028): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): WPA: Nonce1 - hexdump(len=32): 53 d6 e6 03 39 ba 68 b1 22 06 19 88 a7 58 b9 a6 7c e7 2f dc 34 72 20 44 a6 90 01 49 49 1d 54 d3
D/wpa_supplicant( 2028): WPA: Nonce2 - hexdump(len=32): 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d c2 f8 76 89 3a 84 c3 43 b5 61 c6 85 01 8f cc 33 cf
D/wpa_supplicant( 2028): WPA: PMK - hexdump(len=32): [REMOVED],
D/wpa_supplicant( 2028): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): 48 99 0c 49 76 ca 19 d7 55 3e 1a f5 50 b8 0a e3
,D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 53 d6 e6 03 39 ba 68 b1 22 06 19 88 a7 58 b9 ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d ...
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d c2 f8 76 89 3a 84 c3 43 b5 61 c6 85 01 8f cc 33 cf
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): eb fd 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): bb 17 1c 3a 22 25 4a 7b 7b 08 39 e5 5a 02 d2 67
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 21 fb 21 d9 31 87 2c 87 0d 70 64 0c 27 15 1d ...
D/wpa_supplicant( 2028): RSN: encrypted key data - hexdump(len=56): 5c 3a 96 88 2d 2b 89 a1 67 5e 3d af 92 4a 15 b4 98 bb 89 8a bb 67 6b ab 86 7a 72 7f 56 e6 c1 fa ...
D/wpa_supplicant( 2028): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 66 e2 ...
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): f2 f9 f1 45 8c 22 65 e6 d5 8e 4e e1 e7 ef 39 2b
D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2028): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85d5c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2028): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2028): WPA: RSC - hexdump(len=6): eb fd 00 00 00 00
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5e03a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2028):    broadcast key
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/wpa_supplicant( 2028): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2028): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2028): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): EAPOL authentication completed successfully
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  963): handleMessage: E msg.what=147459
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
,D/WifiNative-wlan0(  963): doString: STATUS
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2028): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@437523f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-33ms what=147462 obj=android.net.wifi.StateChangeResult@43616fa8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/DhcpStateMachine(  963): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): WaitBeforeStartState
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-33ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
,I/ActivityManager(  963): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5318 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5318): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  963):    returned null
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  963): addressUpdated: 192.168.1.157/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.157/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
,V/DownloadManager( 5318): DownloadService onCreate
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): DHCP successful
D/EAS     ( 4577): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4577): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
I/DownloadManager( 5318): in removeSpuriousFiles
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  963): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/eas_req ( 4577): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  963): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
,D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,V/DownloadManager( 5318): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c0ef70 on behalf of 5318
,D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/DownloadManager( 5318): in trimDatabase
V/DownloadManager( 5318): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c110c8 on behalf of 5318
,D/dalvikvm(  963): GC_CONCURRENT freed 2271K, 49% free 30603K/59884K, paused 5ms+6ms, total 107ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 70ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 68ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 69ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 70ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 70ms
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/DownloadManager( 5318): DownloadService onStartCommand
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
,E/Parcel  (  501): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/DownloadManager( 5318): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/linker  ( 4577): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
D/HtmlEditor( 4577): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4577): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4577): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
I/dalvikvm( 4577): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c134f8 on behalf of 5318
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/HtmlEditor( 4577): register_HtmlEditor, Success
,D/HtmlEditor( 4577): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4577): register_HtmlEditorTimer, Success
D/HtmlEditor( 4577): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,D/HtmlEditor( 4577): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4577): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4577): register_HtmlEditorFont, Success
,D/HtmlEditor( 4577): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4577): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4577): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4577): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4577): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4577): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4577): JNI_OnLoad Success
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,I/HubEmail( 4577): JNI_OnLoad()
,I/HubEmail( 4577): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4577): registerNatives()
I/HubEmail( 4577): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4577): registerNativeMethods()
,I/HubEmail( 4577): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5344 uid=10052 gids={50052, 3003}
W/Settings( 4577): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5318): DownloadService onDestroy
,V/        (  264): RouteController
D/HyLog   ( 5344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5344): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  963): Killing 4312:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/        (  264): RouteController
D/DhcpStateMachine(  963): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  264): RouteController
,V/        (  264): RouteController
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
V/LGRssiData( 5344): [loadRssi] File not exist 
V/LGRssiData( 5344): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5344): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 5344): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5344): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5344): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5344): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 5344): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5344): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5344): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 5344): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5344): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  264): RouteController
,E/PhoneMonitor( 5344): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5344): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5379 uid=10063 gids={50063, 3003, 1028, 1015}
,D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =192.168.1.157
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| net type = 1
V/QCNEA   (  501): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| Received ssid= NG700
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
,D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/ActivityManager(  963): Killing 4502:com.android.defcontainer/u0a4 (adj 15): empty #17
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/HyLog   ( 5379): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5379): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5379): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1966): Checking schedule, now: 1453982062452 next: 1453981587248
,I/CheckinService( 1966): active receiver: enabled
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1453981727277
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5394 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  963): Killing 4531:com.google.android.partnersetup/u0a9 (adj 15): empty #17
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/HyLog   ( 5394): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5394): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5394): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  963): Killing 4563:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5407 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5407): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5407): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5407): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5407): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5421 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 4193:com.android.contacts/u0a21 (adj 15): empty #17
,D/HyLog   ( 5421): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5421): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5421): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 5421): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5421): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5421): intf.getDisplayName() = lo
I/Wireless_Storage( 5421): intf.getDisplayName() = sit0
I/Wireless_Storage( 5421): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5421): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5421): intf.getDisplayName() = wlan0
D/NFS     ( 5421): interface name:wlan0 name:wlan0
,D/NFS     ( 5421): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5421): interface name:wlan0 name:wlan0
D/NFS     ( 5421): addr:192.168.1.157 broadcast:192.168.1.255
,I/Wireless_Storage( 5421): CONNECT : WIFI_CONNECT
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5433 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 4209:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,D/HyLog   ( 5433): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5433): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5433): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42fc7598: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982062750649597; DSPS: 17736158; Offset: 1453981521486062195
,W/GAV2    ( 5433): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5451 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24836K, paused 3ms+4ms, total 41ms
,W/dalvikvm( 5451): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5451): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5451): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5451): install
,I/MultiDex( 5451): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5451): loading existing secondary dex files
,I/MultiDex( 5451): load found 3 secondary dex files
,I/MultiDex( 5451): install done
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 5451): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5451): VFY: unable to resolve instance field 61
,D/dalvikvm( 5451): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 5451): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5451): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd9a50
,D/dalvikvm( 5451): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd9a50
,D/dalvikvm( 5451): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd9a50, skipping init
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd9a50
,D/dalvikvm( 5451): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd9a50
,V/JNIHelp ( 5451): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 2ms+3ms, total 29ms
,V/WebViewChromium( 5433): Binding Chromium to the main looper Looper (main, tid 1) {42bd27f8}
,I/chromium( 5433): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5433): Initializing chromium process, renderers=0
,W/chromium( 5433): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5433): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5433): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5433): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5433): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5433): Remote Branch: 
I/Adreno-EGL( 5433): Local Patches: 
I/Adreno-EGL( 5433): Reconstruct Branch: 
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd9a50
,D/dalvikvm( 5451): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42bd9a50
D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd9a50
,D/dalvikvm( 5451): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bd9a50
D/wpa_supplicant( 2028): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2028): EAPOL: disable timer tick
,I/NSApplication( 5433): Starting up...
,I/ActivityManager(  963): Killing 4597:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5270): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5270): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5270): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5270): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5270): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5270): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5227): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5227): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5270): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5270): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5270): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5270): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 5451): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1882): callingUid 10006, callindPid: 1882
,E/MDM     ( 1426): [61] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1966): Restart initialization of location
,I/dalvikvm( 5451): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5451): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5451): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5451): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5451): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5451): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
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
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3306760946
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 5451): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42da1d78
D/dalvikvm( 5451): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42da1d78
,D/dalvikvm( 5451): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42da1d78, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=1901714794
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 5451): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5451): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5498): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5451): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5451): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 111ms
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1966): SSL shutdown failed: ssl=0x63718eb0: I/O error during system call, Connection timed out
,I/CheckinTask( 1966): Sending checkin request (11471 bytes)
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.157
,V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4022): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4022): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4022): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5318): DownloadService onCreate
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4577): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5344): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5344): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5407): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5421): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5421): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 5318): in removeSpuriousFiles
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5318): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/Settings( 4577): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c19a18 on behalf of 5318
I/DownloadManager( 5318): in trimDatabase
V/DownloadManager( 5318): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5318): DownloadService onStartCommand
V/DownloadManager( 5318): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c1bb68 on behalf of 5318
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c1d040 on behalf of 5318
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5318): DownloadService onDestroy
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5318): DownloadService onCreate
,I/DownloadManager( 5318): in removeSpuriousFiles
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5318): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5318): DownloadService onStartCommand
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c22088 on behalf of 5318
,V/DownloadManager( 5318): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5318): in trimDatabase
,V/DownloadManager( 5318): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5344): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5344): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4577): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c24a60 on behalf of 5318
,V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c24848 on behalf of 5318
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5407): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5318): DownloadService onDestroy
,W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5421): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5421): CONNECT : WIFI_CONNECT
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/dalvikvm( 1966): GC_CONCURRENT freed 1860K, 22% free 19591K/24836K, paused 4ms+4ms, total 66ms
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1538): GC_CONCURRENT freed 1751K, 28% free 18064K/24836K, paused 6ms+4ms, total 37ms
,D/dalvikvm(  963): GC_EXPLICIT freed 1706K, 49% free 30552K/59884K, paused 4ms+10ms, total 165ms
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x433d47c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1453982066577 next: 1454559462572
,I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checking schedule, now: 1453982066623 next: 1454559462572
,I/CheckinService( 1966): active receiver: disabled
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1538): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5318): DownloadService onCreate
,D/EAS     ( 4577): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5344): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5344): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMSGCM( 5407): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 5318): in removeSpuriousFiles
V/DownloadManager( 5318): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c29090 on behalf of 5318
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5421): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5421): CONNECT : WIFI_CONNECT
W/Settings( 4577): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5318): DownloadService onStartCommand
I/DownloadManager( 5318): in trimDatabase
V/DownloadManager( 5318): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5318): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c2c790 on behalf of 5318
V/DownloadManager( 5318): created cursor android.database.sqlite.SQLiteCursor@42c2c2b0 on behalf of 5318
,V/DownloadManager( 5318): DownloadService onDestroy
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 5433): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  963): Killing 4227:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5640 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
D/administrator(  963): Handling package changes for user 0
,I/SlideAside( 3751): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5640): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5640): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5640): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5640): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5640): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5640): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5640): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5640): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5640): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5640): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5640): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5640): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5640): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5640): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5640): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5640): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5640): MmsConfig.loadFromResources
,E/Babel   ( 5640): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5640): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/GmsNetworkLocationProvi( 1426): DISABLE
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5640): [loadRssi] File not exist 
,V/LGRssiData( 5640): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5640): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5640): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5640): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5640): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4022): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4022): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): Event For Nothing, skip.
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5687 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5687): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  963): applying state to connected service
,D/LocationProviderProxy(  963): applying state to connected service
,I/SystemConfig( 5687): BUILD Country: EU
,I/SystemConfig( 5687): BUILD Operator: OPEN
I/ActivityManager(  963): Killing 5227:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 5687): systemFeature RCS result false
,D/SystemConfig( 5687): refreshRcsSupport() :false
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5705 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): Killing 5270:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5705): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  963): Killing 5318:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  963): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5721 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5721): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5721): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5721): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5721): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5721): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5721): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 5721): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5721): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5721): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5721): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5721): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5721): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5721): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5721): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5721): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5721): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x011e
,I/IcingCorporaProvider( 2653): UpdateCorporaTask done [took 314 ms] updated apps [took 314 ms] 
,I/dalvikvm( 5721): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5721): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5721): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5721): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5758 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 5721): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5721): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 5758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5758): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5721): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5721): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5721): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5721): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5721): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  963): Killing 4577:com.lge.email/u0a24 (adj 15): empty #17
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 5758): DownloadService onCreate
,I/DownloadManager( 5758): in removeSpuriousFiles
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c116e0 on behalf of 5758
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c11048 on behalf of 5721
,I/DownloadManager( 5758): in trimDatabase
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c141c8 on behalf of 5758
,V/DownloadManager( 5758): DownloadService onStartCommand
,V/DownloadManager( 5758): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 5721): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c176a8 on behalf of 5758
,D/Finsky  ( 5721): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/DownloadManager( 5758): DownloadService onDestroy
I/ActivityManager(  963): Killing 5344:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5721): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5721): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5721): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5721): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm(  963): GC_EXPLICIT freed 2101K, 49% free 30687K/59684K, paused 5ms+14ms, total 168ms
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5721): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5721): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 5721): Total arena pages for JIT: 11
,I/dalvikvm( 5721): Total arena pages for JIT: 12
I/dalvikvm( 5721): Total arena pages for JIT: 13
,I/dalvikvm( 5721): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5721): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5721): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5721): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5721): [1] DailyHygiene.reschedule: Scheduling new run in 82 minutes (failures=3)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 5640): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982082751578443; DSPS: 18391548; Offset: 1453981521486075514
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5721): [468] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5721): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982100049, nextTick: 59978, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982100054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982102752897446; DSPS: 19046951; Offset: 1453981521486082261
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982122754374366; DSPS: 19702360; Offset: 1453981521486063820
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982142755300399; DSPS: 20357750; Offset: 1453981521486074325
,I/ActivityManager(  963): Killing 5379:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982160052, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982160055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982162756215809; DSPS: 21013140; Offset: 1453981521486074208
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982182759593405; DSPS: 21668611; Offset: 1453981521486064353
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982202760034752; DSPS: 22323985; Offset: 1453981521486078454
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982220044, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982220056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982222761353442; DSPS: 22979388; Offset: 1453981521486084888
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982242762226871; DSPS: 23634777; Offset: 1453981521486073307
,D/wpa_supplicant( 2028): wlan0: BSS: Remove id 3 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 4 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982262762648427; DSPS: 24290151; Offset: 1453981521486067617
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982280044, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982280055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982282764208159; DSPS: 24945562; Offset: 1453981521486070952
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982302765297526; DSPS: 25600958; Offset: 1453981521486061687
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982322765735278; DSPS: 26256332; Offset: 1453981521486072193
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982340049, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982340056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982342766637146; DSPS: 26911721; Offset: 1453981521486089051
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982362767505733; DSPS: 27567110; Offset: 1453981521486072628
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43153db0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 5721): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5721): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5721): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5721): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5721): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5721): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5721): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5721): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5721): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5721): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982382768361298; DSPS: 28222498; Offset: 1453981521486073701
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982400044, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982400055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982402768812227; DSPS: 28877873; Offset: 1453981521486066866
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982422770157793; DSPS: 29533277; Offset: 1453981521486069659
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982442770587421; DSPS: 30188651; Offset: 1453981521486072041
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982460045, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982460047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982462771037256; DSPS: 30844026; Offset: 1453981521486064112
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982482771921572; DSPS: 31499415; Offset: 1453981521486063418
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Disconnect event
D/wpa_supplicant( 2028): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2028): wlan0: Deauthentication notification
D/wpa_supplicant( 2028): wlan0:  * reason 0
D/wpa_supplicant( 2028): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2028): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2028): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2028): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  963): handleMessage: E msg.what=147460,
D/WifiStateMachine(  963): processMsg: ConnectedState,
D/WifiStateMachine(  963): processMsg: L2ConnectedState,
D/WifiStateMachine(  963): processMsg: ConnectModeState,
,D/WifiStateMachine(  963): Network connection lost
,D/WifiStateMachine(  963): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  963): doBoolean: SET ps 1,
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85d4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2028): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  963): addressRemoved: 192.168.1.157/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/wpa_supplicant( 2028): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2028): wlan0: nl80211: scan request
,D/wpa_supplicant( 2028): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  963): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/wpa_supplicant( 2028): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: Scan trigger
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= 
D/QCNEA   (  501): |CAC| net type = 3
V/QCNEA   (  501): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  501): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  963): Attempting to switch to mobile
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131213
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): handleMessage: X
I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6221 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6221): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6221): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 6221): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6221): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6266 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 5394:com.lge.drmservice/u0a66 (adj 15): empty #17
,V/        (  264): RouteController
,W/NetworkManagementService(  963): route cmd failed: 
W/NetworkManagementService(  963): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  963): '
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  963): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  963): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x61edbd98 clazz=0xaa700001 iface=wlan0 mask=0x3
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
,V/NativeCrypto( 1538): Read error: ssl=0x5a2adb08: I/O error during system call, Connection timed out
,V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x5a2adb08: I/O error during system call, Broken pipe
,D/HyLog   ( 6266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6266): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6266): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  963): StoppedState
,D/QRemote ( 6266): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6266): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6266): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6266): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6266): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6266): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6266): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6266): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,I/QRemote ( 6266): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/ActivityManager(  963): Killing 5407:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2028): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2028): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2028): nl80211: Survey data missing
D/wpa_supplicant( 2028): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 5 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 7 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 8 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 9 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 10 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2028): wlan0: New scan results available
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2028): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2028): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2028): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2028): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2028): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): WPS: AP[3] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2028): wlan0:    skip - blackl,isted (count=1 limit=0)
D/wpa_supplicant( 2028): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 4: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-90 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-86 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2028): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps,
D/wpa_supplicant( 2028): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2028): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2028): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
,D/wpa_supplicant( 2028): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85d65a8  current_ssid=0x0
D/wpa_supplicant( 2028): scard is not null..,
,D/wpa_supplicant( 2028): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
,D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): TDLS: TDLS is allowed in the target BSS,
I/wpa_supplicant( 2028): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2028): wlan0: Cancelling scan request
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2028): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2028): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2028): RSN: PMKSA cache search - network_ctx=0xb85d65a8 try_opportunistic=0
D/wpa_supplicant( 2028): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2028): RSN: No PMKSA cache entry found,
D/wpa_supplicant( 2028): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2028): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 2028): wlan0: WPA: using PTK CCMP,
D/wpa_supplicant( 2028): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2028): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2028): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2028): nl80211: Unsubscribe mgmt frames handle 0xb85d5590 (mode change)
D/wpa_supplicant( 2028): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85d5590
,D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590,
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0d,
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
,D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2028): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2028):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028):   * freq=2412,
D/wpa_supplicant( 2028):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2028):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 38:f8:89:11:e9:11]
D/wpa_supplicant( 2028):   * Auth Type 0
D/wpa_supplicant( 2028):   * WPA Versions 0x2,
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:12:7f:81]
D/wpa_supplicant( 2028): nl80211: Connect request send successfully
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2028): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:37:b7:9d:3e:73]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 06:7c:34:12:7f:81]
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState,
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
D/wpa_supplicant( 2028): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2028): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
,D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Connect event
D/wpa_supplicant( 2028): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2028): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2028): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2028): wlan0: Association info event
D/wpa_supplicant( 2028): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2028): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): wlan0: freq=2412 MHz
D/wpa_supplicant( 2028): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2028): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): scard is not null..
D/wpa_supplicant( 2028): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2028): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2028): TDLS: Remove peers on association
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2028): EAPOL: enable timer tick
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: Cancelling scan request
,D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 ...
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 14 fc 78 ba 77 ea 52 42 af 6a cf 47 42 cb 08 7f 11
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 ...
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2028): Get randomness: len=32 entropy=8
D/wpa_supplicant( 2028): WPA: Renewed SNonce - hexdump(len=32): 1a 64 dd 8e d0 f7 d3 46 f8 ba 46 dd ad 24 7a 4f 56 a6 8f 77 4e 53 9a bf 5b fd e2 ea 89 f3 ef e6
D/wpa_supplicant( 2028): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): WPA: Nonce1 - hexdump(len=32): 1a 64 dd 8e d0 f7 d3 46 f8 ba 46 dd ad 24 7a 4f 56 a6 8f 77 4e 53 9a bf 5b fd e2 ea 89 f3 ef e6
D/wpa_supplicant( 2028): WPA: Nonce2 - hexdump(len=32): ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 14 fc 78 ba 77 ea 52 42 af 6a cf 47 42 cb 08 7f 11
D/wpa_supplicant( 2028): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2028): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): a2 c0 f7 a4 2c 1f c7 c5 93 a8 23 f6 c3 c2 8a bc
,D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 1a 64 dd 8e d0 f7 d3 46 f8 ba 46 dd ad 24 7a ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 ...
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 14 fc 78 ba 77 ea 52 42 af 6a cf 47 42 cb 08 7f 11
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): 01 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): 09 b7 e7 63 64 1d f4 48 32 33 4e f6 4f f1 b9 bf
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ab e8 53 14 f7 45 44 f0 1c b9 a0 e6 e0 d8 e5 ...
D/wpa_supplicant( 2028): RSN: encrypted key data - hexdump(len=56): 3d ab 55 72 c6 d2 dd 6c e6 8e 29 41 32 5b 31 35 38 bb 69 37 28 ce 97 b8 a1 72 4e 2b 31 c1 01 8b ...
D/wpa_supplicant( 2028): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 0d bc ...
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): b6 00 a4 c2 06 61 b8 35 02 ad f0 7b 42 63 6d a0
,D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2028): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85d5c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2028): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2028): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2028): WPA: RSC - hexdump(len=6): 01 00 00 00 00 00,
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5e03a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2028):    broadcast key,
I/wpa_supplicant( 2028): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2028): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=6
,D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2028): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATED,
,D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): EAPOL authentication completed successfully
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
,D/WifiNative-wlan0(  963): doString: STATUS
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2028): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/ActivityManager(  963): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6312 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  963): handleMessage: X
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/DhcpStateMachine(  963): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/DhcpStateMachine(  963): WaitBeforeStartState
D/WifiStateMachine(  963): ObtainingIpState{ when=-29ms what=147462 obj=android.net.wifi.StateChangeResult@44e8d670 target=com.android.internal.util.StateMachine$SmHandler }
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@44e9e838 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-26ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 4,2 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 6312): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6312): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6312): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LGEmail ( 6312): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  963):    returned null
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
,E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): addressUpdated: 192.168.1.157/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.157/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/LGEmail ( 6312): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
,D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  963): handleMessage: X
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  963): handleMessage: X
W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  963): handleMessage: X
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 6312): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6312): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6312): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6312): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/eas_req ( 6312): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/        (  264): RouteController
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
,V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =192.168.1.157
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| net type = 1
V/QCNEA   (  501): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| Received ssid= NG700
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
,D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,W/linker  ( 6312): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6348 uid=10052 gids={50052, 3003}
D/HtmlEditor( 6312): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6312): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/HtmlEditor( 6312): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 6312): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 6312): register_HtmlEditor, Success
D/HtmlEditor( 6312): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6312): register_HtmlEditorTimer, Success
D/HtmlEditor( 6312): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6312): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6312): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6312): register_HtmlEditorFont, Success
D/HtmlEditor( 6312): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6312): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6312): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6312): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6312): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6312): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 6312): JNI_OnLoad Success
I/HubEmail( 6312): JNI_OnLoad()
I/HubEmail( 6312): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6312): registerNatives()
I/HubEmail( 6312): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/HyLog   ( 6348): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 6312): registerNativeMethods()
D/HyLog   ( 6348): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6348): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 6312): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6312): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  963): Killing 5421:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,V/LGRssiData( 6348): [loadRssi] File not exist 
,V/LGRssiData( 6348): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6348): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 6348): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6348): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6348): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6348): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/MobileConnectivityChangeReceiver( 6348): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6348): onReceive CONNECTIVITY_CHANGE networkType=1
D/DhcpStateMachine(  963): DHCP request on wlan0
V/TelephonyAutoProfiling( 6348): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6348): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6348): [getValue] FEATURE key : vzw_roaming_state, value : null
D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6365 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 6348): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6348): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  963): Killing 5433:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6365): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1966): Checking schedule, now: 1453982493867 next: 1453982096572
,I/CheckinService( 1966): active receiver: enabled
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1453982062479
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6386 uid=10066 gids={50066, 4002, 3003, 1028}
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24836K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 16ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 16ms
,D/dalvikvm(  963): GC_EXPLICIT freed 2686K, 49% free 30630K/59684K, paused 4ms+10ms, total 141ms
,D/HyLog   ( 6386): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6386): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6386): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  963): Killing 4665:com.test.thalitest/u0a304 (adj 15): empty #17
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6400 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 6400): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6400): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6400): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/LGDMSGCM( 6400): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6414 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 5451:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 6414): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6414): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6414): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 6414): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm( 1538): GC_EXPLICIT freed 1570K, 28% free 17987K/24836K, paused 6ms+5ms, total 57ms
,I/Wireless_Storage( 6414): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6414): intf.getDisplayName() = lo
I/Wireless_Storage( 6414): intf.getDisplayName() = sit0
I/Wireless_Storage( 6414): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6414): intf.getDisplayName() = teql0
I/Wireless_Storage( 6414): intf.getDisplayName() = wlan0
,D/NFS     ( 6414): interface name:wlan0 name:wlan0
D/NFS     ( 6414): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6414): interface name:wlan0 name:wlan0
D/NFS     ( 6414): addr:192.168.1.157 broadcast:192.168.1.255
,I/Wireless_Storage( 6414): CONNECT : WIFI_CONNECT
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6426 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 5640:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6426): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6426): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6426): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6426): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x44ea38a8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6444 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6444): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6444): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6444): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6444): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6444): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6444): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6444): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6444): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6444): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6444): install
,I/MultiDex( 6444): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6444): loading existing secondary dex files
,I/MultiDex( 6444): load found 3 secondary dex files
,I/MultiDex( 6444): install done
,D/dalvikvm( 6444): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6444): VFY: unable to resolve instance field 61
,D/dalvikvm( 6444): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6444): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6444): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6444): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6444): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6444): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6444): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6444): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6444): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6444): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd25c8
D/dalvikvm( 6444): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd25c8
,D/dalvikvm( 6444): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd25c8, skipping init
,D/dalvikvm( 6444): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd25c8
D/dalvikvm( 6444): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd25c8
,V/JNIHelp ( 6444): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 6426): Binding Chromium to the main looper Looper (main, tid 1) {42bcaf10}
,I/chromium( 6426): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6426): Initializing chromium process, renderers=0
,D/wpa_supplicant( 2028): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2028): EAPOL: disable timer tick
,W/chromium( 6426): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6426): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6426): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6426): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6426): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6426): Remote Branch: 
I/Adreno-EGL( 6426): Local Patches: 
I/Adreno-EGL( 6426): Reconstruct Branch: 
,I/NSApplication( 6426): Starting up...
,I/ActivityManager(  963): Killing 5687:com.android.contacts/u0a21 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm( 6444): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd25c8
D/dalvikvm( 6444): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42bd25c8
D/dalvikvm( 6444): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd25c8
D/dalvikvm( 6444): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bd25c8
,I/ActivityManager(  963): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6478 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/HyLog   ( 6478): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6478): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6478): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ProviderInstaller( 6444): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 6444): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6444): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6444): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6444): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x0201
,D/dalvikvm( 6478): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bd2a80
,D/dalvikvm( 6478): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bd2a80
,D/jxcore_app_log( 6478): JniHelper::setJavaVM(0x41b7e808), pthread_self() = 1074188628
,E/JX-Cordova( 6478): JXcore wasn't initialized yet
,D/QRemote ( 6266): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6266): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6266): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6266): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6266): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6266): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,I/PCSuite ( 6221): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6266): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6266): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6266): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6266): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  963): Killing 5705:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/WearableService( 1882): callingUid 10006, callindPid: 1882
D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,E/MDM     ( 1426): [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/LocationInitializer( 1966): Restart initialization of location
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1354296036
D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6444): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42dba670
D/dalvikvm( 6444): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42dba670
,D/dalvikvm( 6444): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42dba670, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.157
V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6493
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6496
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6501
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6522
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1,
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3101968562
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 6444): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6444): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6533): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6444): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6444): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 105ms
,I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6444): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6444): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6444): Remote Branch: 
I/Adreno-EGL( 6444): Local Patches: 
I/Adreno-EGL( 6444): Reconstruct Branch: 
,I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6444): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6444): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6444): Remote Branch: 
I/Adreno-EGL( 6444): Local Patches: 
I/Adreno-EGL( 6444): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6444): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6444): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6444): Remote Branch: 
I/Adreno-EGL( 6444): Local Patches: 
I/Adreno-EGL( 6444): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,V/NativeCrypto( 1966): SSL shutdown failed: ssl=0x6d395f28: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1966): Sending checkin request (11468 bytes)
,D/GCM     ( 1538): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4022): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4022): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4022): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5758): DownloadService onCreate
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6312): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6348): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6348): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6400): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6414): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6414): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 5758): in removeSpuriousFiles
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c1f388 on behalf of 5758
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings( 6312): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5758): DownloadService onStartCommand
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/DownloadManager( 5758): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/DownloadManager( 5758): in trimDatabase
V/DownloadManager( 5758): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c22560 on behalf of 5758
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c21938 on behalf of 5758
I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,V/DownloadManager( 5758): DownloadService onDestroy
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5758): DownloadService onCreate
,I/DownloadManager( 5758): in removeSpuriousFiles
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c270a0 on behalf of 5758
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 6312): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 5758): in trimDatabase
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5758): DownloadService onStartCommand
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c28a28 on behalf of 5758
,V/DownloadManager( 5758): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c2a760 on behalf of 5758
I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
,W/Settings( 6312): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 6348): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6348): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5758): DownloadService onDestroy
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 3931): GC_FOR_ALLOC freed 383K, 2% free 37806K/38448K, paused 25ms, total 28ms
,D/LGDMSGCM( 6400): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 6400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6414): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6414): CONNECT : WIFI_CONNECT
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  963): GC_EXPLICIT freed 1479K, 49% free 30675K/59684K, paused 2ms+6ms, total 83ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42d1cc80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1966): Checking schedule, now: 1453982497242 next: 1454559893239
,I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checking schedule, now: 1453982497280 next: 1454559893239
,I/CheckinService( 1966): active receiver: disabled
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1966): GC_CONCURRENT freed 1932K, 22% free 19617K/24836K, paused 5ms+4ms, total 53ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5758): DownloadService onCreate
,D/EAS     ( 6312): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6348): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6348): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6400): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6414): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6414): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 5758): in removeSpuriousFiles
,V/DownloadManager( 5758): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
W/Settings( 6312): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c2eee8 on behalf of 5758
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5758): DownloadService onStartCommand
V/DownloadManager( 5758): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 5758): in trimDatabase
V/DownloadManager( 5758): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c31f20 on behalf of 5758
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 5758): created cursor android.database.sqlite.SQLiteCursor@42c32138 on behalf of 5758
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5758): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 6426): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  963): Killing 6221:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): Killing 5721:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982502773289830; DSPS: 32154820; Offset: 1453981521486058385
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3751): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  963): Handling package changes for user 0
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6652 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6652): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6652): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6652): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6652): MmsConfig.loadMmsSettings
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel   ( 6652): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6652): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6652): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6652): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,W/BaseRuntimeLoader( 6652): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6652): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/MediaCodecList( 6652): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 6652): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
W/BaseRuntimeLoader( 6652): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6652): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6652): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6652): MmsConfig.loadFromResources
E/Babel   ( 6652): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6652): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1426): DISABLE
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 6652): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6652): [loadRssi] File not exist 
,V/LGRssiData( 6652): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6652): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6652): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6652): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6652): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4022): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4022): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): Event For Nothing, skip.
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6700 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
D/LocationProviderProxy(  963): applying state to connected service
D/LocationProviderProxy(  963): applying state to connected service
,D/HyLog   ( 6700): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6700): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6700): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6700): BUILD Country: EU
,I/SystemConfig( 6700): BUILD Operator: OPEN
I/ActivityManager(  963): Killing 6266:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6716 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,I/SystemConfig( 6700): systemFeature RCS result false
,D/SystemConfig( 6700): refreshRcsSupport() :false
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): Killing 5758:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 6716): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6716): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6716): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): Killing 6312:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  963): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6732 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6732): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6732): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6732): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6732): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6732): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6732): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6732): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6732): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6732): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6732): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6732): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6732): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6732): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6732): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6732): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6732): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6732): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x011e
,I/IcingCorporaProvider( 2653): UpdateCorporaTask done [took 321 ms] updated apps [took 321 ms] 
,I/dalvikvm( 6732): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6732): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6732): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6732): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6766 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 6732): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6732): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 6766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6766): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6766): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6732): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6732): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6732): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6732): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6732): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6766): DownloadService onCreate
,I/DownloadManager( 6766): in removeSpuriousFiles
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6766): DownloadService onStartCommand
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c19588 on behalf of 6766
V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c1a780 on behalf of 6766
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c17f60 on behalf of 6732
,I/DownloadManager( 6766): in trimDatabase
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c1d618 on behalf of 6766
,V/DownloadManager( 6766): DownloadService onDestroy
,I/ActivityManager(  963): Killing 6348:com.google.android.setupwizard/u0a52 (adj 15): empty #17
D/Finsky  ( 6732): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6732): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6732): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6732): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6732): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6732): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6732): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  963): GC_EXPLICIT freed 2182K, 49% free 30753K/59684K, paused 4ms+14ms, total 151ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1538): GC_EXPLICIT freed 1308K, 28% free 17993K/24836K, paused 1ms+3ms, total 29ms
,W/Finsky  ( 6732): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6732): Total arena pages for JIT: 11
,I/dalvikvm( 6732): Total arena pages for JIT: 12
I/dalvikvm( 6732): Total arena pages for JIT: 13
,I/dalvikvm( 6732): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6732): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6732): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6732): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6732): [1] DailyHygiene.reschedule: Scheduling new run in 266 minutes (failures=4)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6652): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  963): Killing 6365:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982520049, nextTick: 59979, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982520052, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982522774170224; DSPS: 32810208; Offset: 1453981521486084287
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6732): [516] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6732): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982542774613941; DSPS: 33465583; Offset: 1453981521486070240
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982562775081267; DSPS: 34120958; Offset: 1453981521486079803
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982580050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982580055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982582775536486; DSPS: 34776333; Offset: 1453981521486077258
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982602775981010; DSPS: 35431708; Offset: 1453981521486064018
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982622776438557; DSPS: 36087082; Offset: 1453981521486094319
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982640045, nextTick: 59975, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982640055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982642776890757; DSPS: 36742457; Offset: 1453981521486088756
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982662777334711; DSPS: 37397832; Offset: 1453981521486074946
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/wpa_supplicant( 2028): wlan0: BSS: Remove id 5 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 7 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 8 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 9 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Remove id 10 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 64:7c:34:12:7f:81]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:37:b7:9d:3e:73]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982682778232895; DSPS: 38053221; Offset: 1453981521486088120
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982700049, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982700055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982702779162732; DSPS: 38708612; Offset: 1453981521486071912
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982722779601091; DSPS: 39363986; Offset: 1453981521486083025
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982742780449937; DSPS: 40019374; Offset: 1453981521486077379
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982760051, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982760055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982762780922609; DSPS: 40674750; Offset: 1453981521486061770
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Disconnect event
D/wpa_supplicant( 2028): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2028): wlan0: Deauthentication notification
D/wpa_supplicant( 2028): wlan0:  * reason 0
D/wpa_supplicant( 2028): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2028): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2028): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2028): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2028): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  963): handleMessage: E msg.what=147460
,D/WifiStateMachine(  963): processMsg: ConnectedState,
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState,
,D/WifiStateMachine(  963): Network connection lost
D/WifiStateMachine(  963): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85d4d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2028): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  963): addressRemoved: 192.168.1.157/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
D/wpa_supplicant( 2028): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2028): wlan0: nl80211: scan request
,D/wpa_supplicant( 2028): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  963): hidePasspointNotification off =false
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2028): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: Scan trigger
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= 
D/QCNEA   (  501): |CAC| net type = 3
V/QCNEA   (  501): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  501): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  963): Attempting to switch to mobile
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7065 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131213
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '96 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 96 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24836K, paused 2ms+3ms, total 72ms
,D/HyLog   ( 7065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7065): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 2ms+4ms, total 35ms
,I/PCSuite ( 7065): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7065): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7065): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,W/NetworkManagementService(  963): route cmd failed: 
W/NetworkManagementService(  963): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 route del src v6 2' failed with '400 99 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  963): '
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  963): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  963): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x61edbd98 clazz=0xf7500001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1538): Read error: ssl=0x5a2adb08: I/O error during system call, Connection timed out
,V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x5a2adb08: I/O error during system call, Broken pipe
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+3ms, total 26ms
,D/DhcpStateMachine(  963): StoppedState
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
,I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7111 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 6386:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7111): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7111): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7111): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 7111): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 7111): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 7111): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7111): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7111): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7111): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7111): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7111): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7111): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 6400:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2028): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2028): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2028): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2028): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2028): nl80211: Survey data missing
D/wpa_supplicant( 2028): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 11 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 12 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: BSS: Add new id 13 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2028): wlan0: New scan results available
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2028): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2028): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2028): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2028): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2028): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2028): wlan0: 2: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-89 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2028): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2028): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2028): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2028): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2028): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2028): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2028): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2028): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:,00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85d65a8  current_ssid=0x0
D/wpa_supplicant( 2028): scard is not null..
D/wpa_supplicant( 2028): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2028): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2028): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2028): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
,D/wpa_supplicant( 2028): wlan0: Cancelling scan request,
,D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2028): wlan0: WPA: clearing own WPA/RSN IE,
,D/wpa_supplicant( 2028): wlan0: Automatic auth_alg selection: 0x1,
,D/wpa_supplicant( 2028): RSN: PMKSA cache search - network_ctx=0xb85d65a8 try_opportunistic=0,
,D/wpa_supplicant( 2028): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2028): RSN: No PMKSA cache entry found,
,D/wpa_supplicant( 2028): wlan0: RSN: using IEEE 802.11i/D9.0
,D/wpa_supplicant( 2028): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2,
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2028): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2028): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2028): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2028): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2028): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2028): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2028): nl80211: Unsubscribe mgmt frames handle 0xb85d5590 (mode change)
,D/wpa_supplicant( 2028): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590,
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
,D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2028): nl80211: Register frame type=0xd0 nl_handle=0xb85d5590
D/wpa_supplicant( 2028): nl80211: Register frame match - hexdump(len=2): 0a 11
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:37:b7:9d:3e:73]
D/wpa_supplicant( 2028): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2028):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028):   * freq=2412
D/wpa_supplicant( 2028):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2028):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028):   * Auth Type 0
D/wpa_supplicant( 2028):   * WPA Versions 0x2
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2028): nl80211: Connect request send successfully
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2028): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/wpa_supplicant( 2028): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2028): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/Tethering(  963): MasterInitialState.processMessage what=3
D/wpa_supplicant( 2028): nl80211: Event message available
D/wpa_supplicant( 2028): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2028): nl80211: Connect event
D/wpa_supplicant( 2028): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2028): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2028): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2028): wlan0: Association info event
D/wpa_supplicant( 2028): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2028): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2028): wlan0: freq=2412 MHz
D/wpa_supplicant( 2028): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2028): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2028): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2028): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): scard is not null..
D/wpa_supplicant( 2028): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2028): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2028): TDLS: Remove peers on association
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2028): EAPOL: enable timer tick
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: Cancelling scan request
,D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,D/WifiStateMachine(  963): handleMessage: X
,W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b ...
D/wpa_supplicant( 2028): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b fb c0 ca 84 48 49 55 47 2c 7b 17 5a e1 1b 42 4b 53
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b ...
D/wpa_supplicant( 2028): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2028): Get randomness: len=32 entropy=4
,D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2028): WPA: Renewed SNonce - hexdump(len=32): 35 6f 64 c5 c1 78 c2 2d df be 2f 5b 55 ad 00 43 24 e6 c8 66 87 59 37 b7 69 8a dd fa 03 81 ec d8
D/wpa_supplicant( 2028): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): WPA: Nonce1 - hexdump(len=32): 35 6f 64 c5 c1 78 c2 2d df be 2f 5b 55 ad 00 43 24 e6 c8 66 87 59 37 b7 69 8a dd fa 03 81 ec d8
D/wpa_supplicant( 2028): WPA: Nonce2 - hexdump(len=32): 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b fb c0 ca 84 48 49 55 47 2c 7b 17 5a e1 1b 42 4b 53
D/wpa_supplicant( 2028): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2028): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): f0 93 77 78 55 7d 41 b9 f7 2c b4 6c 82 bb 6a d8
D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 35 6f 64 c5 c1 78 c2 2d df be 2f 5b 55 ad 00 ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/wpa_supplicant( 2028): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b ...
D/wpa_supplicant( 2028): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2028): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2028): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2028): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2028):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2028):   key_nonce - hexdump(len=32): 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b fb c0 ca 84 48 49 55 47 2c 7b 17 5a e1 1b 42 4b 53
D/wpa_supplicant( 2028):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_rsc - hexdump(len=8): da 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2028):   key_mic - hexdump(len=16): 88 c1 64 16 9c fa 03 9e 55 ab e8 fe a6 c1 ca fd
D/wpa_supplicant( 2028): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0d 4f 27 95 aa b8 cf c5 fb 48 1f 31 40 47 2b ...
D/wpa_supplicant( 2028): RSN: encrypted key data - hexdump(len=56): 82 c0 46 44 79 97 46 51 75 ec 2a fb 1d 39 01 2d 82 84 c4 8e fa a1 27 96 3b 10 7c 87 77 49 41 72 ...
D/wpa_supplicant( 2028): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2028): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2028): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 0d bc ...
D/wpa_supplicant( 2028): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2028): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2028): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): WPA: Derived Key MIC - hexdump(len=16): fc 77 cc 2c cc 18 2d 7a db cc c6 dc 10 47 bb a3
D/wpa_supplicant( 2028): WPA: TX EAPOL-Key - hexdump(len=99): 01 0,3 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2028): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85d5c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2028):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2028): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2028): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2028): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2028): WPA: RSC - hexdump(len=6): da 00 00 00 00 00
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5e03a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2028):    broadcast key
I/wpa_supplicant( 2028): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2028): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2028): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2028): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2028): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2028): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2028): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2028): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2028): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2028): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2028): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2028): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2028): EAPOL authentication completed successfully
D/wpa_supplicant( 2028): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2028): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2028): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
,D/WifiNative-wlan0(  963): doString: STATUS
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2028): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2028): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  963): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): WaitBeforeStartState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@444cecd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
,D/WifiStateMachine(  963): ObtainingIpState{ when=-38ms what=147462 obj=android.net.wifi.StateChangeResult@43486c90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-38ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
,I/ActivityManager(  963): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7154 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 7154): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7154): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7154): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d1b4b8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  963): addressUpdated: 192.168.1.157/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.157/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2028): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2028): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2028): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/LGEmail ( 7154): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2028): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2028): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2028): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
E/Parcel  (  501): Reading a NULL string not supported here.
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  963): handleMessage: X
W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): handleMessage: E msg.what=131092
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
,E/Parcel  (  501): Reading a NULL string not supported here.
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  501): Reading a NULL string not supported here.
E/Parcel  (  501): Reading a NULL string not supported here.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  501): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,D/LGEmail ( 7154): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 7154): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7154): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7154): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7154): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  501): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  501): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  501): |CAC| updateNetCfgInfo
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC|                   Netconfig               
V/QCNEA   (  501): |CAC| *********************************************
V/QCNEA   (  501): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  501): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  501): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  501): |CAC| 	NetConfig: ip4        =192.168.1.157
V/QCNEA   (  501): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  501): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  501): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| net type = 1
V/QCNEA   (  501): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  501): |CAC| Received ssid= NG700
V/QCNEA   (  501): |CAC| 	ssid           =NG700
V/QCNEA   (  501): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  501): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  501): |CAC| *********************************************
D/QCNEA   (  501): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  501): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  501): |CAC| dispatchNetCfg: updating:0xb86018dc
D/QCNEA   (  501): |CAC| readCallback: read len:0, ret:-1, errno:11
D/EAS     ( 7154): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 7154): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/eas_req ( 7154): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
,W/linker  ( 7154): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 7154): JNI_OnLoad
,D/HtmlAPI v1.36.23.33395.LG_apps_master( 7154): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 7154): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 7154): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 7154): register_HtmlEditor, Success
D/HtmlEditor( 7154): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7154): register_HtmlEditorTimer, Success
,D/HtmlEditor( 7154): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7154): register_HtmlEditorDownloader, Success
D/HtmlEditor( 7154): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7154): register_HtmlEditorFont, Success
,D/HtmlEditor( 7154): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7154): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 7154): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=7191 uid=10052 gids={50052, 3003}
D/HtmlEditor( 7154): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 7154): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/DhcpStateMachine(  963): DHCP request on wlan0
D/HtmlEditor( 7154): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 7154): JNI_OnLoad Success
D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/HubEmail( 7154): JNI_OnLoad()
,I/HubEmail( 7154): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7154): registerNatives()
I/HubEmail( 7154): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7154): registerNativeMethods()
,I/HubEmail( 7154): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,D/HyLog   ( 7191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7191): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Settings( 7154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  963): Killing 6414:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7191): [loadRssi] File not exist 
,V/LGRssiData( 7191): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7191): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 7191): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7191): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7191): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7191): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 7191): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7191): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 7191): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7191): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7191): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7214 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 6426:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,E/PhoneMonitor( 7191): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 7191): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/HyLog   ( 7214): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7214): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7214): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1966): Checking schedule, now: 1453982775511 next: 1453982527239
,I/CheckinService( 1966): active receiver: enabled
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1453982493905
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7242 uid=10066 gids={50066, 4002, 3003, 1028}
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 7242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7242): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  963): Killing 6478:com.test.thalitest/u0a304 (adj 15): empty #17
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7261 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7261): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7261): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7261): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 7261): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7275 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 6444:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7275): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 7275): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7275): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 7275): intf.getDisplayName() = lo
I/Wireless_Storage( 7275): intf.getDisplayName() = sit0
I/Wireless_Storage( 7275): intf.getDisplayName() = p2p0
I/Wireless_Storage( 7275): intf.getDisplayName() = teql0
I/Wireless_Storage( 7275): intf.getDisplayName() = wlan0
,D/NFS     ( 7275): interface name:wlan0 name:wlan0
D/NFS     ( 7275): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 7275): interface name:wlan0 name:wlan0
,D/NFS     ( 7275): addr:192.168.1.157 broadcast:192.168.1.255
,I/Wireless_Storage( 7275): CONNECT : WIFI_CONNECT
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7287 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 6652:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7287): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7287): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7287): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.157
V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 7287): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43879960: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7305 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/wpa_supplicant( 2028): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2028): EAPOL: disable timer tick
,D/dalvikvm(  963): GC_EXPLICIT freed 2616K, 49% free 30699K/59684K, paused 5ms+11ms, total 155ms
,D/HyLog   ( 7305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7305): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 7305): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7305): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 7305): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7305): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7305): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 7305): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7305): install
,I/MultiDex( 7305): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7305): loading existing secondary dex files
,I/MultiDex( 7305): load found 3 secondary dex files
,I/MultiDex( 7305): install done
,D/dalvikvm( 7305): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7305): VFY: unable to resolve instance field 61
,D/dalvikvm( 7305): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 7305): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7305): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7305): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 7305): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7305): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7305): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7305): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7305): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7305): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd71f0
D/dalvikvm( 7305): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd71f0
,D/dalvikvm( 7305): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd71f0, skipping init
,D/dalvikvm( 7305): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd71f0
D/dalvikvm( 7305): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd71f0
,V/JNIHelp ( 7305): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 7287): Binding Chromium to the main looper Looper (main, tid 1) {42bd0040}
,I/chromium( 7287): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/BrowserProcessMain( 7287): Initializing chromium process, renderers=0
,W/chromium( 7287): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/dalvikvm( 7305): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bd71f0
D/dalvikvm( 7305): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42bd71f0
D/dalvikvm( 7305): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bd71f0
,D/dalvikvm( 7305): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bd71f0
,I/Adreno-EGL( 7287): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7287): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7287): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7287): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7287): Remote Branch: 
I/Adreno-EGL( 7287): Local Patches: 
I/Adreno-EGL( 7287): Reconstruct Branch: 
,I/NSApplication( 7287): Starting up...
,I/ActivityManager(  963): Killing 6700:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ProviderInstaller( 7305): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  963): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=7341 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/HyLog   ( 7341): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7341): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7341): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,I/dalvikvm( 7305): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 7305): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7305): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7305): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 7305): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7305): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 7341): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bd76a8
,D/dalvikvm( 7341): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42bd76a8
D/jxcore_app_log( 7341): JniHelper::setJavaVM(0x41b7e808), pthread_self() = 1074188628
,E/JX-Cordova( 7341): JXcore wasn't initialized yet
,D/QRemote ( 7111): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7111): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7111): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7111): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7111): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7111): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 7065): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7065): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7111): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7111): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 7111): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7111): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  963): Killing 6716:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1de0000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/LocationInitializer( 1966): Restart initialization of location
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/WearableService( 1882): callingUid 10006, callindPid: 1882
,E/MDM     ( 1426): [74] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1014938222
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 7305): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42db1bb8
D/dalvikvm( 7305): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42db1bb8
,D/dalvikvm( 7305): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42db1bb8, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1183148675
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
,W/Settings( 7305): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 7305): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 7381): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 7305): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7305): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 98ms
,I/Adreno-EGL( 7305): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7305): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7305): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7305): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7305): Remote Branch: 
I/Adreno-EGL( 7305): Local Patches: 
I/Adreno-EGL( 7305): Reconstruct Branch: 
,I/Adreno-EGL( 7305): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7305): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7305): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7305): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7305): Remote Branch: 
I/Adreno-EGL( 7305): Local Patches: 
I/Adreno-EGL( 7305): Reconstruct Branch: 
,I/Adreno-EGL( 7305): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7305): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7305): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7305): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7305): Remote Branch: 
I/Adreno-EGL( 7305): Local Patches: 
I/Adreno-EGL( 7305): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1966): Sending checkin request (11469 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
,D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4022): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4022): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4022): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6766): DownloadService onCreate
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7154): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4331): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 7191): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7191): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7261): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 7154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 7275): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7275): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 7261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6766): in removeSpuriousFiles
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c241b8 on behalf of 6766
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 6766): in trimDatabase
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c25510 on behalf of 6766
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6766): DownloadService onStartCommand
V/DownloadManager( 6766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c27760 on behalf of 6766
,V/DownloadManager( 6766): DownloadService onDestroy
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6766): DownloadService onCreate
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 6766): in removeSpuriousFiles
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c2c0b0 on behalf of 6766
,I/DownloadManager( 6766): in trimDatabase
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c2d308 on behalf of 6766
,V/DownloadManager( 6766): DownloadService onStartCommand
I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
V/DownloadManager( 6766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 7191): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7191): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c2f4f8 on behalf of 6766
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6766): DownloadService onDestroy
,D/LGDMSGCM( 7261): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 7261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 7275): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7275): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6766): DownloadService onCreate
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7154): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4331): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4331): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4331): networkInfo.isConnected() = true
,D/PhoneState( 4331): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 7191): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7191): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7261): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7261): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7275): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7275): CONNECT : WIFI_CONNECT
,I/DownloadManager( 6766): in removeSpuriousFiles
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c33690 on behalf of 6766
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6766): DownloadService onStartCommand
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6766): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6766): in trimDatabase
,V/DownloadManager( 6766): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c36da0 on behalf of 6766
,V/DownloadManager( 6766): created cursor android.database.sqlite.SQLiteCursor@42c36b88 on behalf of 6766
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6766): DownloadService onDestroy
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x447fd868: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 9772K, 13% free 69466K/79604K, paused 50ms, total 55ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1453982780690 next: 1454560176686
,I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checking schedule, now: 1453982780742 next: 1454560176686
,I/CheckinService( 1966): active receiver: disabled
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GAV2    ( 7287): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1538): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ActivityManager(  963): Killing 6732:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  963): Killing 7065:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982782782361767; DSPS: 41330157; Offset: 1453981521486066601
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3751): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3751): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  963): Handling package changes for user 0
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7502 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "sms"
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24836K, paused 2ms+3ms, total 67ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+1ms, total 41ms
,W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+1ms, total 16ms
,D/HyLog   ( 7502): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7502): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7502): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 7502): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7502): MmsConfig.loadMmsSettings
I/Babel   ( 7502): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 7502): MmsConfig.loadFromDatabase
,I/MediaCodecList( 7502): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 7502): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 7502): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 7502): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/Settings( 7502): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 7502): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7502): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7502): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7502): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 7502): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7502): MmsConfig.loadFromResources
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/Babel   ( 7502): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7502): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,V/LGRssiData( 7502): [loadRssi] File not exist 
V/LGRssiData( 7502): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 7502): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4  ( 4022): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4022): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@42be7330
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
D/AppUp4:CustFacade( 4022): isPhone : true
,V/TelephonyAutoProfiling( 7502): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7502): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 7502): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 3782): start selecting data
,D/SIMObserver( 3782): simInfo1
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): Event For Nothing, skip.
,V/GmsNetworkLocationProvi( 1426): DISABLE
I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7550 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 7550): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7550): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7550): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  963): applying state to connected service
,D/LocationProviderProxy(  963): applying state to connected service
,D/dalvikvm(  963): GC_EXPLICIT freed 2425K, 49% free 30806K/59684K, paused 5ms+13ms, total 155ms
I/ActivityManager(  963): Killing 7111:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,I/SystemConfig( 7550): BUILD Country: EU
,I/SystemConfig( 7550): BUILD Operator: OPEN
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 7550): systemFeature RCS result false
,D/SystemConfig( 7550): refreshRcsSupport() :false
I/ActivityManager(  963): Killing 6766:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7568 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7568): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7568): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7568): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2653): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  963): Killing 7154:com.lge.email/u0a24 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  963): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7586 uid=10050 gids={50050, 3003, 1028, 1015}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 7586): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7586): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7586): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7586): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7586): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 1966): GC_CONCURRENT freed 2020K, 22% free 19579K/24836K, paused 4ms+11ms, total 69ms
,D/Finsky  ( 7586): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7586): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7586): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7586): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7586): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7586): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7586): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7586): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7586): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7586): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7586): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7586): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 7586): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7586): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7586): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7586): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2653): UpdateCorporaTask done [took 375 ms] updated apps [took 375 ms] 
,I/dalvikvm( 7586): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 7586): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7623 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 7623): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7623): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7623): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 7586): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7586): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7586): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 7586): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7586): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7623): DownloadService onCreate
,I/DownloadManager( 7623): in removeSpuriousFiles
,V/DownloadManager( 7623): DownloadService onStartCommand
,V/DownloadManager( 7623): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7623): created cursor android.database.sqlite.SQLiteCursor@42c10c88 on behalf of 7623
,V/DownloadManager( 7623): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7623): created cursor android.database.sqlite.SQLiteCursor@42c150a8 on behalf of 7586
,V/DownloadManager( 7623): DownloadService onDestroy
,V/DownloadManager( 7623): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7623): created cursor android.database.sqlite.SQLiteCursor@42c17910 on behalf of 7623
,I/DownloadManager( 7623): in trimDatabase
,V/DownloadManager( 7623): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/ActivityManager(  963): Killing 7191:com.google.android.setupwizard/u0a52 (adj 15): empty #17
V/DownloadManager( 7623): created cursor android.database.sqlite.SQLiteCursor@42c18f70 on behalf of 7623
D/Finsky  ( 7586): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/Finsky  ( 7586): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7586): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7586): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7586): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7586): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1538): GC_EXPLICIT freed 1165K, 28% free 18001K/24836K, paused 3ms+5ms, total 50ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 7586): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7586): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7586): Total arena pages for JIT: 11
,I/dalvikvm( 7586): Total arena pages for JIT: 12
,I/dalvikvm( 7586): Total arena pages for JIT: 13
,I/dalvikvm( 7586): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  963): Checking http://216.58.209.78/generate_204
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7586): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7586): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7586): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7586): [1] DailyHygiene.reschedule: Scheduling new run in 837 minutes (failures=5)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 7502): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  963): Killing 7214:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43003358 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982802783232394; DSPS: 41985545; Offset: 1453981521486082736
,D/Finsky  ( 7586): [564] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7586): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982820055, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1453982820057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982822785635680; DSPS: 42640984; Offset: 1453981521486075134
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1453982842786113231; DSPS: 43296360; Offset: 1453981521486064403
,TIME-OUT KILL (timeout was 1200000ms)
```
