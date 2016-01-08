#### Test 5497026140aeaf4_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4618): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  965): Killing 3603:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 1 tasks}
D/dalvikvm( 1937): GC_CONCURRENT freed 1546K, 22% free 19428K/24832K, paused 3ms+7ms, total 55ms
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1937): fetch service done; releasing wakelock
I/ConfigFetchService( 1937): stopping self
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1206): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1206): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1937): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1937): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1937): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4670): 
D/AndroidRuntime( 4670): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4670): CheckJNI is OFF
D/dalvikvm( 4670): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4670): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4670): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4670): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4670): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4670): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
E/memtrack( 4670): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4670): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4670): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4670
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (117 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{43938b10 stackId=1, 2 tasks}
D/UsbSettingsControl( 2614): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2614): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3782): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 4670): Shutting down VM
D/dalvikvm( 4670): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 1ms
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4687 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4687): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/SlideAside( 3782): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3782): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4687): Binding Chromium to the background looper Looper (main, tid 1) {42f0f850}
I/chromium( 4687): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4687): Initializing chromium process, renderers=0
W/chromium( 4687): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4687): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4687): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4687): Remote Branch: 
I/Adreno-EGL( 4687): Local Patches: 
I/Adreno-EGL( 4687): Reconstruct Branch: 
I/dalvikvm( 4687): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4687): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4687): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4687): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4687): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4687): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4687): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4687): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4687): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4687): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4687): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4687): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4687): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4687): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4687): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4687): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4687): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4687): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4687): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4687): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4687): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4687): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4687): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4687): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4687): Enabling debug mode 0
,W/AwContents( 4687): nativeOnDraw failed; clearing to background color.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/AwContents( 4687): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  965): IME STATUS OFF
I/ActivityManager( 4687): Timeline: Activity_idle id: android.os.BinderProxy@42f10f30 time:109611
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +405ms
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/JsMessageQueue( 4687): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4687): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42f15818
,D/dalvikvm( 4687): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42f15818
D/jxcore_app_log( 4687): JniHelper::setJavaVM(0x41ec4808), pthread_self() = 1632526336
,D/JX-Cordova( 4687): jxcore cordova android initializing
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} time:109993
D/ActivityManager(  965): no-history finish of ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{4318b770 ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2614): [AUTORUN] onStop()
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4687): GC_CONCURRENT freed 2786K, 12% free 21865K/24832K, paused 3ms+1ms, total 50ms
,D/dalvikvm( 4687): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 113K, 12% free 21862K/24832K, paused 30ms, total 30ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 126K, 12% free 21882K/24832K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 23.634MB for 95956-byte allocation
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 179K, 13% free 21917K/24928K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 23.713MB for 143930-byte allocation
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 253K, 13% free 21964K/25072K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 23.829MB for 215890-byte allocation
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 367K, 13% free 22038K/25284K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 24.003MB for 323830-byte allocation
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 566K, 14% free 22159K/25604K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 24.276MB for 485740-byte allocation
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 862K, 15% free 22334K/26080K, paused 22ms, total 22ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 1282K, 14% free 22590K/26080K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 25.276MB for 1092904-byte allocation
,D/dalvikvm( 4687): GC_CONCURRENT freed 1847K, 16% free 22984K/27148K, paused 1ms+3ms, total 43ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 214K, 16% free 22894K/27148K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 26.094MB for 1639352-byte allocation
,D/dalvikvm( 4687): GC_CONCURRENT freed 2057K, 19% free 23534K/28752K, paused 1ms+6ms, total 62ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 955K, 19% free 23509K/28752K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 27.477MB for 2459024-byte allocation
,D/dalvikvm( 4687): GC_CONCURRENT freed 307K, 18% free 25849K/31156K, paused 2ms+2ms, total 40ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 4286K, 22% free 24537K/31156K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4687): Grow heap (frag case) to 29.653MB for 3688532-byte allocation
,D/dalvikvm( 4687): GC_CONCURRENT freed 353K, 20% free 28125K/34760K, paused 4ms+8ms, total 58ms
,D/dalvikvm( 4687): GC_FOR_ALLOC freed 3268K, 27% free 25484K/34760K, paused 24ms, total 25ms
,W/jxcore-log( 4687): Initializing JXcore engine
,W/jxcore-log( 4687): JXcore engine is ready
,D/dalvikvm( 4687): GC_CONCURRENT freed 329K, 20% free 28148K/34760K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4687): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4687): Starting JXcore engine
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/jxcore-log( 4687): Platform android
W/jxcore-log( 4687): 
,W/jxcore-log( 4687): Process ARCH arm
W/jxcore-log( 4687): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState,
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/jxcore-log( 4687): JXcore Cordova bridge is ready!
I/jxcore-log( 4687): 
W/jxcore-log( 4687): JXcore engine is started
I/chromium( 4687): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 4687): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4687): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/GAV2    ( 4618): Thread[GAThread,5,main]: No campaign data found.
I/jxcore-log( 4687): Toggling radios to true
I/jxcore-log( 4687): 
D/BluetoothManagerService(  965): Message: 20
D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@450c2910:true
D/BluetoothAdapter( 4687): enable(): BT is already enabled..!
D/WifiService(  965): New client listening to asynchronous messages
D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DISCONNECT
I/jxcore-log( 4687): Radios toggled
I/jxcore-log( 4687): 
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2024): TDLS: Tear down peers
D/wpa_supplicant( 2024): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  965): setWifiEnabled: true pid=4687, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  965): disconnect pid=4687, uid=10304
D/WifiService(  965): reconnect pid=4687, uid=10304
D/wpa_supplicant( 2024): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2024): wlan0: Deauthentication notification
D/wpa_supplicant( 2024): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2024): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2024): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2024): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2024): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2024): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8db9d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2024): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
W/Settings(  965): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2024): Fast associate: Old scan results
D/wpa_supplicant( 2024): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2024): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2024): wlan0: nl80211: scan request
D/wpa_supplicant( 2024): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  965):    returned true
D/wpa_supplicant( 2024): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2024): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/DhcpStateMachine(  965): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  965): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
D/QCNEA   (  544): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  544): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  544): |CAC| updateNetCfgInfo
V/QCNEA   (  544): |CAC| *********************************************
V/QCNEA   (  544): |CAC|                   Netconfig               
V/QCNEA   (  544): |CAC| *********************************************
V/QCNEA   (  544): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  544): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  544): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  544): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  544): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  544): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  544): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  544): |CAC| *********************************************
D/QCNEA   (  544): |CAC| Received bssid= 
D/QCNEA   (  544): |CAC| net type = 3
V/QCNEA   (  544): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  544): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  544): |CAC| 	ssid           =NG700
V/QCNEA   (  544): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  544): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  544): |CAC| *********************************************
D/QCNEA   (  544): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  544): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  544): |CAC| dispatchNetCfg: updating:0xb7bf38dc
D/QCNEA   (  544): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  965): hidePasspointNotification off =false
D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  264): RouteController
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
V/        (  264): RouteController
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4764 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
V/        (  264): RouteController
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/HyLog   ( 4764): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/HyLog   ( 4764): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4764): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
W/NetworkManagementService(  965): route cmd failed: 
W/NetworkManagementService(  965): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  965): '
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  965): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  965): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  965): android_net_utils_resetConnections in env=0x628c7410 clazz=0x6cc00001 iface=wlan0 mask=0x3
I/PCSuite ( 4764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4764): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QcConnectivityService(  965): resetConnections(wlan0, 3)
V/NativeCrypto( 1536): Read error: ssl=0x63e482a8: I/O error during system call, Connection timed out
V/NativeCrypto( 1536): SSL shutdown failed: ssl=0x63e482a8: I/O error during system call, Broken pipe
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.446854 Y: -0.424423 Z: 9.816315 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446854 .y:-0.424423 .z:9.816315
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4800 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  965): Killing 4184:com.google.android.talk/u0a77 (adj 15): empty #17
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
D/HyLog   ( 4800): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  965): Failed to clear dns cache for: com.google.android.talk
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
D/QRemote ( 4800): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4800): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4800): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4800): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4800): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4800): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4800): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4800): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4800): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 3946:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.452225 Y: -0.415848 Z: 9.816040 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.442230 Y: -0.432495 Z: 9.791626 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.452225 .y:-0.415848 .z:9.816040
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/DhcpStateMachine(  965): StoppedState
I/ConfigService( 1536): onDestroy
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2024): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2024): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2024): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2024): nl80211: Survey data missing
D/wpa_supplicant( 2024): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 7 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 8 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 9 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 10 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2024): wlan0: New scan results available
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2024): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2024): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2024): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2024): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2024): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2024): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2024): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[3] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[5] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[6] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2024): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2024): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2024): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
D/wpa_supplicant( 2024): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2024): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy polic,y: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2024): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2024): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8dbb5a8  current_ssid=0x0
D/wpa_supplicant( 2024): scard is not null..
D/wpa_supplicant( 2024): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
,D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2024): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2024): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2024): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2024): RSN: PMKSA cache search - network_ctx=0xb8dbb5a8 try_opportunistic=0
D/wpa_supplicant( 2024): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2024): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2024): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2024): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2024): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2024): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2024): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2024): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2024): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2024): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2024): nl80211: Unsubscribe mgmt frames handle 0xb8dba590 (mode change)
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 44:e9:dd:10:c0:ab]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:37:b7:9d:3e:73]
D/wpa_supplicant( 2024): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register ,frame match - hexdump(len=2): 04 0c
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 64:7c:34:b0:03:6e]
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb8dba590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 0a 11
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 44:e9:dd:10:c0:ad]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2024): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2024):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024):   * freq=2412
D/wpa_supplicant( 2024):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2024):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024):   * Auth Type 0
D/wpa_supplicant( 2024):   * WPA Versions 0x2
D/wpa_supplicant( 2024): nl80211: Connect request send successfully
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2024): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2024): nl80211: Connect event
D/wpa_supplicant( 2024): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2024): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2024): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2024): wlan0: Association info event
D/wpa_supplicant( 2024): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2024): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2024): wlan0: freq=2412 MHz
D/wpa_supplicant( 2024): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2024): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2024): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): scard is not null..
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2024): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2024): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2024): TDLS: Remove peers on association
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2024): EAPOL: enable timer tick
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
,D/dalvikvm( 1536): GC_EXPLICIT freed 1248K, 29% free 17833K/24832K, paused 5ms+4ms, total 41ms
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4056): onReceive
,D/AppUp4:CustFacade( 4056): Context : android.app.ReceiverRestrictedContext@42f2e2f0
D/AppUp4:CustFacade( 4056): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4056): isOpenOperator : true
D/AppUp4:CustFacade( 4056): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/SIMObserver( 2991): simInfo1
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,I/AppUp4:EulaManager( 4056): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4056): begin check event
,I/AppUp4:CustModeStarterReceiver( 4056): Event For GoodConnectivity
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2024): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 ...
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2024): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2024): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2024): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2024):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2024):   key_nonce - hexdump(len=32): b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 31 1f c0 11 1c 73 86 93 56 0b 8e fb be 06 77 4e f4
D/wpa_supplicant( 2024):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 ...
D/wpa_supplicant( 2024): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2024): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2024): Get randomness: len=32 entropy=11
D/EAS     ( 4601): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4601): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/wpa_supplicant( 2024): WPA: Renewed SNonce - hexdump(len=32): f1 19 c1 6f 5d 73 39 a6 de e0 51 8b d2 04 86 c8 d2 9c b6 f0 d3 2a cd d0 89 ba ee 6c a0 55 b0 82
D/wpa_supplicant( 2024): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): WPA: Nonce1 - hexdump(len=32): f1 19 c1 6f 5d 73 39 a6 de e0 51 8b d2 04 86 c8 d2 9c b6 f0 d3 2a cd d0 89 ba ee 6c a0 55 b0 82
D/wpa_supplicant( 2024): WPA: Nonce2 - hexdump(len=32): b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 31 1f c0 11 1c 73 86 93 56 0b 8e fb be 06 77 4e f4
D/wpa_supplicant( 2024): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2024): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2024): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2024): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2024): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): WPA: Derived Key MIC - hexdump(len=16): 88 61 1a 1b 5a c3 f1 a9 8f 2b d9 6b ad 52 10 26
D/wpa_supplicant( 2024): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 f1 19 c1 6f 5d 73 39 a6 de e0 51 8b d2 04 86 ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/eas_req ( 4601): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/wpa_supplicant( 2024): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RX EAPOL - hexdump(len=155):, 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 ...
D/wpa_supplicant( 2024): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2024): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2024): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2024): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2024):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2024):   key_nonce - hexdump(len=32): b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 31 1f c0 11 1c 73 86 93 56 0b 8e fb be 06 77 4e f4
D/wpa_supplicant( 2024):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_rsc - hexdump(len=8): 70 53 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_mic - hexdump(len=16): 4c 4c 0f 5b ec 08 cb b0 81 fd eb eb 82 3c 42 0a
D/wpa_supplicant( 2024): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 b0 f9 64 95 ee 34 e7 ab be 34 50 79 f7 c8 52 ...
D/wpa_supplicant( 2024): RSN: encrypted key data - hexdump(len=56): fd f0 e3 4a 33 57 10 29 ad 3e 92 b3 1f 6f eb c0 e3 52 79 e7 db cf c4 b5 4a fd a2 5a 29 6a d5 28 ...
D/wpa_supplicant( 2024): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2024): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2024): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2024): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 22 85 ...
D/wpa_supplicant( 2024): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2024): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2024): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): WPA: Derived Key MIC - hexdump(len=16): 36 d7 01 50 97 9c 76 b2 30 d9 4e 02 0a 19 47 16
D/wpa_supplicant( 2024): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2024): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8dbac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2024):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2024): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2024): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2024): WPA: RSC - hexdump(len=6): 70 53 00 00 00 00
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f0603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2024):    broadcast key
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
I/wpa_supplicant( 2024): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2024): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2024): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2024): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2024): EAPOL authentication completed successfully
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
I/LgeMiscReceiver( 4352): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4352): action = android.net.conn.CONNECTIVITY_CHANGE
D/WifiNative-wlan0(  965): doString: STATUS
I/LgeMiscReceiver( 4352): networkInfo.isConnected() = false
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2024): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
W/linker  ( 4601): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4601): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4601): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4601): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4601): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4601): register_HtmlEditor, Success
D/HtmlEditor( 4601): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4601): register_HtmlEditorTimer, Success
D/HtmlEditor( 4601): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4601): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4601): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4601): register_HtmlEditorFont, Success
D/HtmlEditor( 4601): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4601): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4601): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4601): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4601): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4601): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4601): JNI_OnLoad Success
I/HubEmail( 4601): JNI_OnLoad()
I/HubEmail( 4601): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4601): registerNatives()
I/HubEmail( 4601): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4601): registerNativeMethods()
I/HubEmail( 4601): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4601): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4843 uid=10052 gids={50052, 3003}
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  965): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-29ms what=147462 obj=android.net.wifi.StateChangeResult@4447e6a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@44a3f058 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-26ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 4843): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4843): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4843): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4843): [loadRssi] File not exist 
V/LGRssiData( 4843): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4843): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4843): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4843): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4843): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4843): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4843): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4843): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4860 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 4389:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4370d7b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4370d7b0 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4873 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  965): Killing 4522:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  965): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
E/Parcel  (  544): Reading a NULL string not supported here.
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): handleMessage: X
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
D/HyLog   ( 4873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4873): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  544): Reading a NULL string not supported here.
,E/Parcel  (  544): Reading a NULL string not supported here.
,E/Parcel  (  544): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
,D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
E/Parcel  (  544): Reading a NULL string not supported here.
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  544): Reading a NULL string not supported here.
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
E/Parcel  (  544): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  965): Killing 4555:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/        (  264): RouteController
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4889 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,V/        (  264): RouteController
,V/        (  264): RouteController
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/        (  264): RouteController
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
D/HyLog   ( 4889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGDMSGCM( 4889): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/        (  264): RouteController
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  544): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  544): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  544): |CAC| updateNetCfgInfo
V/QCNEA   (  544): |CAC| *********************************************
V/QCNEA   (  544): |CAC|                   Netconfig               
V/QCNEA   (  544): |CAC| *********************************************
,V/QCNEA   (  544): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  544): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  544): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  544): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  544): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  544): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  544): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  544): |CAC| *********************************************
D/QCNEA   (  544): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  544): |CAC| net type = 1
V/QCNEA   (  544): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  544): |CAC| Received ssid= NG700
V/QCNEA   (  544): |CAC| 	ssid           =NG700
V/QCNEA   (  544): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  544): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  544): |CAC| *********************************************
D/QCNEA   (  544): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  544): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  544): |CAC| dispatchNetCfg: updating:0xb7bf38dc
,D/QCNEA   (  544): |CAC| readCallback: read len:0, ret:-1, errno:11
I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4916 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  965): Killing 4585:com.lge.bnr/1000 (adj 15): empty #17
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
D/HyLog   ( 4916): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4916): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4916): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
I/CheckinService( 1937): Checking schedule, now: 1452278354828 next: 1452278299989
I/CheckinService( 1937): active receiver: enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/NFS     ( 4916): connectivityManager.getNetworkInfo = TYPE_WIFI
I/CheckinService( 1937): Preparing to send checkin request
,I/EventLogService( 1937): Accumulating logs since 1452278267346
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Wireless_Storage( 4916): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4916): intf.getDisplayName() = lo
,I/Wireless_Storage( 4916): intf.getDisplayName() = sit0
I/Wireless_Storage( 4916): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4916): intf.getDisplayName() = teql0
I/Wireless_Storage( 4916): intf.getDisplayName() = wlan0
D/NFS     ( 4916): interface name:wlan0 name:wlan0
D/NFS     ( 4916): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4916): interface name:wlan0 name:wlan0
D/NFS     ( 4916): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4916): CONNECT : WIFI_CONNECT
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1937): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4938 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 4230:com.android.contacts/u0a21 (adj 15): empty #17
,E/ActivityThread( 1937): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 20ms
,D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4938): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,W/GAV2    ( 4938): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm(  965): GC_EXPLICIT freed 23615K, 49% free 29779K/57860K, paused 3ms+7ms, total 174ms
,V/WebViewChromium( 4938): Binding Chromium to the main looper Looper (main, tid 1) {42f183b0}
,I/chromium( 4938): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4938): Initializing chromium process, renderers=0
,W/chromium( 4938): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4938): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4938): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4938): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4938): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4938): Remote Branch: 
I/Adreno-EGL( 4938): Local Patches: 
I/Adreno-EGL( 4938): Reconstruct Branch: 
,I/NSApplication( 4938): Starting up...
,I/ActivityManager(  965): Killing 4246:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 4800): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4800): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/QRemote ( 4800): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4800): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4800): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4800): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4800): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4800): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4800): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4800): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,W/CheckinRequestBuilder( 1937): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43a1b188: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4995 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4995): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4995): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4995): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4995): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4995): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4995): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4995): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4995): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4995): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4995): install
,I/MultiDex( 4995): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4995): loading existing secondary dex files
,I/MultiDex( 4995): load found 3 secondary dex files
,I/MultiDex( 4995): install done
,D/dalvikvm( 4995): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4995): VFY: unable to resolve instance field 61
,D/dalvikvm( 4995): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4995): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4995): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4995): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4995): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4995): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4995): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4995): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4995): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4995): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f135c0
D/dalvikvm( 4995): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f135c0
,D/dalvikvm( 4995): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f135c0, skipping init
D/dalvikvm( 4995): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f135c0
D/dalvikvm( 4995): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f135c0
,V/JNIHelp ( 4995): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,D/dalvikvm( 4995): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f135c0
,D/dalvikvm( 4995): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42f135c0
D/dalvikvm( 4995): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f135c0
,D/dalvikvm( 4995): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42f135c0
,I/ProviderInstaller( 4995): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1536): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1937): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1870): callingUid 10006, callindPid: 1870
,D/LocationInitializer( 1937): Restart initialization of location
,E/MDM     ( 1421): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4995): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4995): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4995): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4995): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4995): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4995): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dba000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1dba000
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
D/wpa_supplicant( 2024): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2024): EAPOL: disable timer tick
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=3831098539
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4995): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x431340d0
D/dalvikvm( 4995): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x431340d0
,D/dalvikvm( 4995): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x431340d0, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4995): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 5015): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4995): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4995): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 89ms
,I/Adreno-EGL( 4995): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4995): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4995): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4995): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4995): Remote Branch: 
I/Adreno-EGL( 4995): Local Patches: 
I/Adreno-EGL( 4995): Reconstruct Branch: 
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1445): getPreferredApnId: subscription=0
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=1959001121
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GCM     ( 1536): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4995): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4995): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4995): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4995): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4995): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4995): Remote Branch: 
I/Adreno-EGL( 4995): Local Patches: 
I/Adreno-EGL( 4995): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 4995): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4995): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4995): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4995): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4995): Remote Branch: 
I/Adreno-EGL( 4995): Local Patches: 
I/Adreno-EGL( 4995): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1937): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1937): Sending checkin request (11456 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1937): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1937): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x443f92b8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1937): awaiting user notification for token
,I/CheckinRequestBuilder( 1937): Classify the device as Phone.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/CheckinTask( 1937): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1937): Checking schedule, now: 1452278357164 next: 1452855753161
I/CheckinService( 1937): active receiver: disabled
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  544): Reading a NULL string not supported here.
,E/Parcel  (  544): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4056): onReceive
D/AppUp4:CustFacade( 4056): Context : android.app.ReceiverRestrictedContext@42f2e2f0
D/AppUp4:CustFacade( 4056): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4056): isOpenOperator : true
,D/AppUp4:CustFacade( 4056): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
I/AppUp4:EulaManager( 4056): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4056): begin check event
I/AppUp4:CustModeStarterReceiver( 4056): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4056): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4056): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4056): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4056): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4056): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 3135): DownloadService onCreate
,D/EAS     ( 4601): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4601): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4601): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4352): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4352): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4352): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4889): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 4916): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4916): CONNECT : WIFI_CONNECT
W/ContextImpl( 4889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/jxcore-log( 4687): Test app app.js loaded
I/jxcore-log( 4687): 
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Choreographer( 4687): Skipped 393 frames!  The application may be doing too much work on its main thread.
,I/DownloadManager( 3135): in removeSpuriousFiles
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fb12d0 on behalf of 3135
I/DownloadManager( 3135): in trimDatabase
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fb2820 on behalf of 3135
W/Settings( 4601): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/chromium( 4687): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 3135): DownloadService onStartCommand
V/DownloadManager( 3135): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fb49d0 on behalf of 3135
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 3135): DownloadService onDestroy
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4056): onReceive
,D/AppUp4:CustFacade( 4056): Context : android.app.ReceiverRestrictedContext@42f2e2f0
D/AppUp4:CustFacade( 4056): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4056): isOpenOperator : true
,D/AppUp4:CustFacade( 4056): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4056): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4056): begin check event
,I/AppUp4:CustModeStarterReceiver( 4056): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 3135): DownloadService onCreate
D/EAS     ( 4601): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 3135): in removeSpuriousFiles
D/EAS     ( 4601): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 3135): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fb9100 on behalf of 3135
,V/DownloadManager( 3135): DownloadService onStartCommand
,V/DownloadManager( 3135): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3135): in trimDatabase
,V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fbb858 on behalf of 3135
,V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fbc280 on behalf of 3135
I/LgeMiscReceiver( 4352): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4352): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4352): networkInfo.isConnected() = true
,D/PhoneState( 4352): setPdpRejectCasuse : false
,W/Settings( 4601): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3135): DownloadService onDestroy
,D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4889): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/NFS     ( 4916): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4916): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1206): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4056): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4056): onReceive
,D/AppUp4:CustFacade( 4056): Context : android.app.ReceiverRestrictedContext@42f2e2f0
D/AppUp4:CustFacade( 4056): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4056): isOpenOperator : true
,D/AppUp4:CustFacade( 4056): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4056): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4056): begin check event
,I/AppUp4:CustModeStarterReceiver( 4056): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4601): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 3135): DownloadService onCreate
,D/EAS     ( 4601): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4352): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4352): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4352): networkInfo.isConnected() = true
,D/PhoneState( 4352): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4843): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4843): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4601): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 3135): in removeSpuriousFiles
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fc08e0 on behalf of 3135
D/LGDMClient( 2877): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3135): in trimDatabase
V/DownloadManager( 3135): DownloadService onStartCommand
V/DownloadManager( 3135): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3135): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fc3e40 on behalf of 3135
V/DownloadManager( 3135): created cursor android.database.sqlite.SQLiteCursor@42fc4058 on behalf of 3135
D/LGDMSGCM( 4889): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2877): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2877): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4916): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4916): CONNECT : WIFI_CONNECT
V/DownloadManager( 3135): DownloadService onDestroy
E/LGDMClient( 2877): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2877): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2877): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2877): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1206): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1206): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/GAV2    ( 4938): Thread[GAThread,5,main]: No campaign data found.
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,D/WifiController(  965): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED,
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 4267): [408] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4267): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  965): Killing 4618:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.451279 Y: -0.445221 Z: 9.812439 
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.454605 Y: -0.436340 Z: 9.804657 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.451279 .y:-0.445221 .z:9.812439
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.454727 Y: -0.439194 Z: 9.802231 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454727 .y:-0.439194 .z:9.802231
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3782): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 3782): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  965): Handling package changes for user 0
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5158 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5158): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5158): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5158): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5158): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/Babel   ( 5158): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/MediaCodecList( 5158): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 5158): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5158): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5158): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5158): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5158): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5158): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5158): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5158): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5158): MmsConfig.loadFromResources
,E/Babel   ( 5158): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5158): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1421): DISABLE
,I/GCoreNlp( 1421): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm(  965): GC_EXPLICIT freed 3279K, 49% free 29810K/57860K, paused 2ms+8ms, total 95ms
,W/Settings( 5158): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5158): [loadRssi] File not exist 
V/LGRssiData( 5158): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5158): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5158): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5158): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5158): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4056): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4056): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4056): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4056): onReceive
,D/AppUp4:CustFacade( 4056): Context : android.app.ReceiverRestrictedContext@42f2e2f0
D/AppUp4:CustFacade( 4056): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4056): isOpenOperator : true
,D/AppUp4:CustFacade( 4056): isPhone : true
,I/LicenseContentProvider( 2991): start selecting data
,D/SIMObserver( 2991): simInfo1
,I/AppUp4:EulaManager( 4056): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4056): begin check event
D/AppUp4:Utils( 4056): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4056): Event For Nothing, skip.
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5209 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5209): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5209): BUILD Country: EU
,I/SystemConfig( 5209): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4764:com.lge.sync/1000 (adj 15): empty #17
,I/SystemConfig( 5209): systemFeature RCS result false
,D/SystemConfig( 5209): refreshRcsSupport() :false
I/ActivityManager(  965): Killing 4800:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5224 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5224): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5224): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5224): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 3135:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2682): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1937): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1937): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{450e7040 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1937): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1937): GC_CONCURRENT freed 1866K, 22% free 19553K/24832K, paused 3ms+2ms, total 30ms
,I/IcingCorporaProvider( 2682): UpdateCorporaTask done [took 225 ms] updated apps [took 225 ms] 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/HeadsetStateMachine( 1206): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/GAV4    ( 5158): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8891 usec
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.440552 Y: -0.416061 Z: 9.789566 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440552 .y:-0.416061 .z:9.789566
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.426071 Y: -0.425186 Z: 9.794479 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.426071 .y:-0.425186 .z:9.794479
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  523): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.430466 Y: -0.419586 Z: 9.812607 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.430466 .y:-0.419586 .z:9.812607
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.438248 Y: -0.418442 Z: 9.809967 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438248 .y:-0.418442 .z:9.809967
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.434952 Y: -0.435547 Z: 9.814163 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.434952 .y:-0.435547 .z:9.814163
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.440353 Y: -0.429031 Z: 9.817490 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440353 .y:-0.429031 .z:9.817490
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42f2e050)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8ca0450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.434677 Y: -0.423996 Z: 9.805786 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.434677 .y:-0.423996 .z:9.805786
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/WindowManager(  965): No lock screen! windowToken=null
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2024): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
,V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43a6ed50 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1849): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:39:37
,D/UpdateThreadPoolManager( 1849): 2 : This is isUpdating : false
,D/WeatherAncestor( 1849): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:39:37
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1849): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1849): 2 : shouldTimeTickRegistered : false
E/SlideAside( 3782): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
D/WeatherService( 1849): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
I/SlideAside( 3782): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.442078 Y: -0.419235 Z: 9.806168 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442078 .y:-0.419235 .z:9.806168
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
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
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.436157 Y: -0.427292 Z: 9.806564 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436157 .y:-0.427292 .z:9.806564
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
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
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 420ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278377772, nextTick: 22260, mDrawingTime: 0
D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278377838, nextTick: 22194, mDrawingTime: 0
D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/WeatherService( 1849): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:39:37
,D/WeatherService( 1849): 2 : ACTION screen on
,D/WeatherService( 1849): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1849): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:39:37
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
,E/Parcel  (  544): Reading a NULL string not supported here.
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1445): Emergency Service
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1445): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1445): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1445): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1445): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/PhoneApp( 1445): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
,V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  965): Vibrator off
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/UsbSettings( 2614): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
V/UsbSettings( 2614): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2614): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2614): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  965): CMD_SCREEN_OFF 
D/WifiController(  965): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{437fed58 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43938b10 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,I/[LGHome]EVENT( 1486): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
E/Parcel  (  544): Reading a NULL string not supported here.
,E/Parcel  (  544): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/WeatherService( 1849): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:39:38
D/WeatherService( 1849): 2 : ACTION screen off
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1445): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1445): Emergency Service
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1445): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/WeatherService( 1849): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:39:38
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1445): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1445): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1445): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
,V/PhoneApp( 1445): Action intent recieved:android.intent.action.SCREEN_OFF
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/NfcService( 1471): NFC-C OFF
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  523): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1445): getIsInUseVoLTE : false
,D/PhoneApp( 1445): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1536): Vacuum at: now=1452278386726 tag=VacuumService
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1536): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1536):  no longer exists, so no auth token.
,W/Uploader( 1536): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278395748534638; DSPS: 5289558; Offset: 1452278234324035127
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278400033, nextTick: 59999, mDrawingTime: 0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278400037, nextTick: 59995, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278415749689942; DSPS: 5944956; Offset: 1452278234324030763
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278435752087227; DSPS: 6600395; Offset: 1452278234324017159
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5419
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278455753744719; DSPS: 7255809; Offset: 1452278234324026702
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278460040, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1452278460047, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278475754182836; DSPS: 7911183; Offset: 1452278234324037573
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1206): Disconnected process message: 10
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1154): GC_CONCURRENT freed 2893K, 11% free 25449K/28520K, paused 24ms+3ms, total 102ms
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1452278495755606631; DSPS: 8566590; Offset: 1452278234324027042
,I/jxcore-log( 4687): --= Surplus to requirements =--
I/jxcore-log( 4687): 
,I/jxcore-log( 4687): ****TEST TOOK:  ms ****
I/jxcore-log( 4687): 
,I/jxcore-log( 4687): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4687): 
,D/AndroidRuntime( 5486): 
D/AndroidRuntime( 5486): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5486): CheckJNI is OFF
,D/dalvikvm( 5486): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5486): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5486): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5486): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5486): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5486): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5486): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5486): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5486): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  965): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  965): Killing 4687:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  965):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  965):   Force finishing activity ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
,D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{455c28c0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
,D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/WindowState(  965): WIN DEATH: Window{455de770 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  965): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1486): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1486): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1486): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1445): getIsInUseVoLTE : false,
,I/[LGHome]LGActivityUtil( 1486): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1486): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1486): [Launcher.java:894:onPause()]onPause
,D/WeatherAncestor( 1849): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:41:46
,D/UpdateThreadPoolManager( 1849): 2 : This is isUpdating : false
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/WeatherService( 1849): 2 : shouldTimeTickRegistered : false
,D/WeatherAncestor( 1849): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:41:46
,D/WeatherService( 1849): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
I/[LGHome]EVENT( 1486): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1486): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherService( 1849): 2 : shouldTimeTickRegistered : false
,I/InputMethodManagerService(  965): IME STATUS OFF
,W/Binder  ( 1307): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1307): java.lang.NullPointerException
W/Binder  ( 1307): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1307): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1307): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1307): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  965): Got RemoteException sending setActive(false) notification to pid 4687 uid 10304
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  965): Skipping PackageSetting{433e0b68 com.example.hello/10312} due to missing metadata
,I/ActivityManager(  965): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3782): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3782): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,D/dalvikvm( 1140): GC_CONCURRENT freed 4882K, 8% free 70489K/76096K, paused 3ms+4ms, total 41ms
,D/dalvikvm( 1140): WAIT_FOR_CONCURRENT_GC blocked 35ms
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/System.err( 2670): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2670): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,W/System.err( 2670): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2670): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2670): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2670): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 2670): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2670): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2670): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2670): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 2670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2670): 	at dalvik.system.NativeStart.main(Native Method)
D/AppUp4:Utils( 4056): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4056): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 4056):  isExcludedPackage  packagename = com.test.thalitest
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/GeofencerStateMachine( 1421): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 2682): GC_EXPLICIT freed 4101K, 28% free 17920K/24832K, paused 2ms+2ms, total 90ms
,D/AppUp4  ( 4056):  isExcludedPackage TRUE : com.test.thalitest
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1486): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/[LGHome]Launcher.Model( 1486): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/PackageManager(  965):   Scheme: "mms"
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  965): GC_EXPLICIT freed 1857K, 49% free 29928K/57860K, paused 2ms+8ms, total 112ms
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  965): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5517 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43311b50 u0 com.lge.launcher2/.Launcher t1} time:268138
D/administrator(  965): Handling package changes for user 0
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "mms"
,D/HyLog   ( 5517): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5517): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5517): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/[BNRAppListMgrReceiver]( 5517): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,D/BackupManagerService(  965): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  965): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  965): com.test.thalitest isn't inclued in dragdropPackageList
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/BackupManagerService(  965): removePackageParticipantsLocked: uid=10304 #1
,I/ActivityManager(  965): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5530 uid=10090 gids={50090}
,I/ActivityManager(  965): Killing 4601:com.lge.email/u0a24 (adj 15): empty #17
,D/HyLog   ( 5530): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5530): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5530): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/VoicemailCleanupService( 1822): Cleaning up data for package: com.test.thalitest
,D/dalvikvm(  965): GC_EXPLICIT freed 604K, 49% free 29838K/57860K, paused 4ms+21ms, total 213ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1486): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/LockScreenSettings( 5530): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]Launcher.Model( 1486): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher.Model( 1486): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1486): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1486): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1486): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
,I/ActivityManager(  965): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=5549 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/AndroidRuntime( 5486): Shutting down VM
D/dalvikvm( 5486): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
D/KeyguardModel( 1140): handleShortcutListChanged...
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/HyLog   ( 5549): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5549): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5549): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/KeyguardModel( 1140): handleShortcutListChanged...
I/ActivityManager(  965): Killing 4843:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/LGEmail ( 5549): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/dalvikvm( 1486): GC_FOR_ALLOC freed 6143K, 10% free 62128K/68668K, paused 17ms, total 17ms
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/LGEmail ( 5549): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:6.30.33]
,E/LGEmail ( 5549): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1486): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/LGEmail ( 5549): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,E/[LGHome]NumberBadge( 1486): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1486): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/ActivityManager(  965): Killing 4860:com.android.chrome/u0a63 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fa050 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1486): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]EVENT( 1486): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1486): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/PackageIntentReceiver( 2614): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2614): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2614): Delete mPackageMame : com.test.thalitest
,I/IcingCorporaProvider( 2682): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1486): Timeline: Activity_idle id: android.os.BinderProxy@42f13320 time:268489
,I/ActivityManager(  965): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5566 uid=10073 gids={50073, 3003, 1028, 1015}
,W/BaseRuntimeLoader( 5549): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5549): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5549): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5549): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/HyLog   ( 5566): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5566): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5566): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2682): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
,E/SQLiteDatabase( 5566): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5566): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5566): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5566): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5566): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5566): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5566): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5566): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5566): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 5566): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5566): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 5566): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 5566): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5566): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 5566): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5566): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5566): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 5566): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 5566): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5566): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 5566): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5566): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5566): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5566): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5566): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5566): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5566): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5566): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5566): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5566): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 5566): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 5566): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5566): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5566): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5566): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5566): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5566): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 5566): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5566): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 5566): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 5566): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5566): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5566): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5566): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5566): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 5566): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 5566): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5566): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 5566): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5566): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5566): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 5566): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5566): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5566): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 5566): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 5566): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5566): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 5566): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5566): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5566): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5566): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5566): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5566): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5566): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5566): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5566): 	at azE.a(Suppliers.java:125)
E/SQLiteDatabase( 5566): 	at ahj.run(AbstractDatabaseInstance.java:455)

```
