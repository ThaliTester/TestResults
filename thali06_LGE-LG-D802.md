#### Test 539786633aa3ea0_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1223): Disconnected process message: 10
--------- beginning of /dev/log/system
D/WifiController(  962): battery changed pluggedType: 2
W/GAV2    ( 4532): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EulaProviderUpdateObserver( 3012): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 3012): uri : package:com.test.thalitest
,D/PackageBroadcastService( 1898): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1898): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1898): Loading module APK com.google.android.play.games
I/ActivityManager(  962): Delaying start of: ServiceRecord{44f53868 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ConfigFetchService( 1898): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1898): launchTask
W/dalvikvm( 1898): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1898): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1898): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1898): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WzF8ypjjcpaJ215GnKKnyGcIOZVMR4xM5GNOsi2OmCEoT21pusyMUuHCaDFuizaWJoiuhKz0W7BNSldLwb44TMxUE-EH7yAFm7u58Hu8o8pC9cZUFwwuqc1SgvFzrdRVFeEViLOoHWR69GmWuR9nOjXoYvDkm9StUSpaKgyTdXqLLUHvtJ8qikG9LXJnye-krQ60Oe
D/ChimeraCfgMgr( 1898): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1898): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
I/GoogleURLConnFactory( 1898): Using platform SSLCertificateSocketFactory
D/Vision  ( 1898): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1898): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1898): CP2 sync disabled
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
I/dalvikvm( 1898): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1898): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1898): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
W/GAV2    ( 4532): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
I/ActivityManager(  962): Killing 4018:com.google.android.gm/u0a68 (adj 15): empty #17
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1898): Using Auth Proxy for data requests.
D/AndroidRuntime( 4575): 
D/AndroidRuntime( 4575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4575): CheckJNI is OFF
D/dalvikvm( 4575): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4575): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4575): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4575): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4575): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4575): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4575): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4575): failed to load memtrack module: -2
I/ConfigFetchService( 1898): fetch service done; releasing wakelock
I/ConfigFetchService( 1898): stopping self
D/AndroidRuntime( 4575): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4575
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
D/dalvikvm( 1898): GC_CONCURRENT freed 1543K, 22% free 19418K/24832K, paused 4ms+6ms, total 60ms
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{433196d0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2599): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2599): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4575): Shutting down VM
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4575): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 6ms
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4597 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3989): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3989): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3989): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Icing   ( 1898): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4597): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Icing   ( 1898): Loaded CLD2 Version V2.0 - 20141016
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/WebViewChromium( 4597): Binding Chromium to the background looper Looper (main, tid 1) {4289b160}
I/chromium( 4597): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4597): Initializing chromium process, renderers=0
D/ChimeraCfgMgr( 1898): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1898): Module APK com.google.android.play.games already loaded
W/chromium( 4597): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4597): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4597): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4597): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4597): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4597): Remote Branch: 
I/Adreno-EGL( 4597): Local Patches: 
I/Adreno-EGL( 4597): Reconstruct Branch: 
I/Icing   ( 1898): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/dalvikvm( 4597): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4597): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4597): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4597): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4597): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4597): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4597): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4597): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4597): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4597): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4597): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4597): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4597): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4597): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4597): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4597): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4597): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4597): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4597): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4597): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4597): Enabling debug mode 0
W/AwContents( 4597): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +347ms
W/AwContents( 4597): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/ActivityManager( 4597): Timeline: Activity_idle id: android.os.BinderProxy@4289c840 time:109868
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4597): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4597): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a0920
D/dalvikvm( 4597): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a0920
D/jxcore_app_log( 4597): JniHelper::setJavaVM(0x41760838), pthread_self() = 1632395312
D/JX-Cordova( 4597): jxcore cordova android initializing
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3} time:110267
D/ActivityManager(  962): no-history finish of ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{4336b9e8 ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2599): [AUTORUN] onStop()
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4597): GC_CONCURRENT freed 2826K, 13% free 21826K/24832K, paused 2ms+1ms, total 46ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 192K, 13% free 21834K/24832K, paused 27ms, total 27ms
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 188K, 12% free 21862K/24832K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 23.664MB for 146998-byte allocation
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 258K, 13% free 21910K/24976K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 23.781MB for 220492-byte allocation
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 375K, 13% free 21986K/25192K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 23.959MB for 330734-byte allocation
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 581K, 14% free 22110K/25516K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 24.239MB for 496096-byte allocation
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 882K, 15% free 22288K/26004K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 24.650MB for 744140-byte allocation
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 1306K, 16% free 22549K/26732K, paused 25ms, total 25ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/HeadsetStateMachine( 1223): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,D/dalvikvm( 4597): GC_CONCURRENT freed 1672K, 15% free 22924K/26732K, paused 1ms+2ms, total 30ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 409K, 15% free 22890K/26732K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 26.125MB for 1674304-byte allocation
,D/dalvikvm( 4597): GC_CONCURRENT freed 1958K, 18% free 23492K/28368K, paused 2ms+2ms, total 51ms
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 1180K, 18% free 23524K/28368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 27.541MB for 2511452-byte allocation
,D/dalvikvm( 4597): GC_CONCURRENT freed 1934K, 22% free 24285K/30824K, paused 1ms+2ms, total 34ms
,D/dalvikvm( 4597): GC_CONCURRENT freed 2404K, 21% free 24488K/30824K, paused 1ms+4ms, total 39ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4597): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 609K, 22% free 24243K/30824K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4597): Grow heap (frag case) to 29.441MB for 3767174-byte allocation
,D/dalvikvm( 4597): GC_CONCURRENT freed 2718K, 27% free 25465K/34504K, paused 1ms+2ms, total 34ms
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 389K, 27% free 25477K/34504K, paused 26ms, total 26ms
,W/jxcore-log( 4597): Initializing JXcore engine
,W/jxcore-log( 4597): JXcore engine is ready
,D/dalvikvm( 4597): GC_FOR_ALLOC freed 3004K, 27% free 25463K/34504K, paused 22ms, total 23ms
,W/jxcore-log( 4597): Starting JXcore engine
,D/dalvikvm( 4597): GC_CONCURRENT freed 2K, 27% free 25490K/34504K, paused 2ms+1ms, total 32ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,W/jxcore-log( 4597): Platform android
W/jxcore-log( 4597): 
,W/jxcore-log( 4597): Process ARCH arm
W/jxcore-log( 4597): 
,I/jxcore-log( 4597): JXcore Cordova bridge is ready!
I/jxcore-log( 4597): 
,W/jxcore-log( 4597): JXcore engine is started
,I/chromium( 4597): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4597): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4597): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4597): Toggling radios to true
I/jxcore-log( 4597): 
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4452fdb0:true
,D/BluetoothAdapter( 4597): enable(): BT is already enabled..!
D/WifiService(  962): New client listening to asynchronous messages
,D/WifiStateMachine(  962): handleMessage: E msg.what=131145
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doBoolean: DISCONNECT
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2021): TDLS: Tear down peers
,D/wpa_supplicant( 2021): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4597): Radios toggled
I/jxcore-log( 4597): 
D/WifiService(  962): setWifiEnabled: true pid=4597, uid=10304
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  962): disconnect pid=4597, uid=10304
D/WifiService(  962): reconnect pid=4597, uid=10304
,D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2021): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7c5ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131146
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiNative-wlan0(  962): doBoolean: RECONNECT
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2021): Fast associate: Old scan results
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/DhcpStateMachine(  962): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= 
D/QCNEA   (  596): |CAC| net type = 3
V/QCNEA   (  596): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  596): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
,D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  962): hidePasspointNotification off =false
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
,D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
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
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4655 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/QcConnectivityService(  962): Attempting to switch to mobile
,D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4655): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4655): I : /data/font/config/dfactpre.dat, No such file or directory (2)
V/        (  264): RouteController
D/HyLog   ( 4655): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
D/PCSuite ( 4655): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/NetworkManagementService(  962): route cmd failed: 
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x619b4108 clazz=0x6c200001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1555): Read error: ssl=0x63a24840: I/O error during system call, Connection timed out
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4693 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  962): Killing 4102:com.google.android.talk/u0a77 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,V/NativeCrypto( 1555): SSL shutdown failed: ssl=0x63a24840: I/O error during system call, Broken pipe
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HyLog   ( 4693): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4693): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4693): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 4693): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4693): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4693): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4693): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4693): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4693): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4693): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4693): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4693): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 3888:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  962): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.482727 Y: -0.405823 Z: 9.762680 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.482727 .y:-0.405823 .z:9.762680
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.484848 Y: -0.405380 Z: 9.758163 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.484848 .y:-0.405380 .z:9.758163
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
I/ActivityManager(  962): Killing 2139:android.process.media/u0a23 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
I/GAV2    ( 4532): Thread[GAThread,5,main]: No campaign data found.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/ConfigService( 1555): onDestroy
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4597): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): my name is : LGE-LG-D802_PT8182
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): attempting to connect to test coordinator
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): check test folder
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): found test : ./testFindPeers.js
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): found test : ./testReConnect.js
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): found test : ./testSendData.js
I/jxcore-log( 4597): 
,I/jxcore-log( 4597): Test app app.js loaded
I/jxcore-log( 4597): 
,I/Choreographer( 4597): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4597): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4597): 
,I/chromium( 4597): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445340034, nextTick: 59997, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445340035, nextTick: 59998, mDrawingTime: 0
,I/jxcore-log( 4597): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4597): 
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  962): MasterInitialState.processMessage what=3
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
,D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7c5c5a8  current_ssid=0x0
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
D/wpa_supplicant( 2021): WPA: RSN IE i,n EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2021): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2021): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb7c5c5a8 try_opportunistic=0
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
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb7c5b590 (mode change)
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
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
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 5b f9 a6 73 7a d5 61 de ee a1 7a b3 76 6a 10 97 4b
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2021): Get randomness: len=32 entropy=7
D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): ee 3a e9 8a 0d a5 dc 3d 1e f5 7c 73 b3 2c 26 2a 93 5c 7e a5 1d 98 ad 4c 27 1e 4f ec 07 db 97 3a
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): ee 3a e9 8a 0d a5 dc 3d 1e f5 7c 73 b3 2c 26 2a 93 5c 7e a5 1d 98 ad 4c 27 1e 4f ec 07 db 97 3a
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 5b f9 a6 73 7a d5 61 de ee a1 7a b3 76 6a 10 97 4b
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 3f eb ed 04 97 27 6d 6b e3 bc 82 75 94 9d c9 5a
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 ee 3a e9 8a 0d a5 dc 3d 1e f5 7c 73 b3 2c 26 ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 5b f9 a6 73 7a d5 61 de ee a1 7a b3 76 6a 10 97 4b
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): a8 15 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 25 1c 60 37 d1 dc 9d 62 0e 1b 4d 4c df 98 60 4c
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 f0 63 0b 3a d5 c0 9c 54 0a ee e6 60 f2 5e b2 ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): 6d 88 9f f8 29 2e 2d 52 ac b5 0c 68 18 56 ab f9 64 aa 2a 23 30 88 27 3d d7 1a 4c 67 62 52 1f 98 ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): b3 10 14 96 85 71 9d 04 22 e8 4d d6 1d 6b 5c d5
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7c5bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): a8 15 00 00 00 00
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6edc03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    broadcast key
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2021): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection established
D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,I/ActivityManager(  962): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4740 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
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
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@43cbd560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@441cc370 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState,
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-11ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2021): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 3ms+3ms, total 33ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 23ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 22ms
,V/DownloadManager( 4740): DownloadService onCreate
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4740): in removeSpuriousFiles
,D/eas_req ( 4509): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428e17b0 on behalf of 4740
,W/linker  ( 4509): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4509): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4509): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4509): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/DownloadManager( 4740): in trimDatabase
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/dalvikvm( 4509): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4509): register_HtmlEditor, Success
,D/HtmlEditor( 4509): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4509): register_HtmlEditorTimer, Success
D/HtmlEditor( 4509): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4509): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4509): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4509): register_HtmlEditorFont, Success
D/HtmlEditor( 4509): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4509): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4509): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428e3020 on behalf of 4740
,D/HtmlEditor( 4509): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4509): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4509): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4509): JNI_OnLoad Success
,I/HubEmail( 4509): JNI_OnLoad()
I/HubEmail( 4509): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4509): registerNatives()
I/HubEmail( 4509): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4509): registerNativeMethods()
,I/HubEmail( 4509): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  962): doBoolean: SET ps 0
W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
V/DownloadManager( 4740): DownloadService onStartCommand
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428e5450 on behalf of 4740
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4764 uid=10052 gids={50052, 3003}
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  962): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
V/DownloadManager( 4740): DownloadService onDestroy
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
,I/ActivityManager(  962): Killing 4262:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4764): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4764): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4764): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
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
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/Parcel  (  596): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
,D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/MobileConnectivityChangeReceiver( 4764): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/LGRssiData( 4764): [loadRssi] File not exist 
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
V/LGRssiData( 4764): [loadRssi] File not exist 
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/TelephonyAutoProfiling( 4764): [loadFeatureFromXml] *** start feature loading from xml
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/BaseRuntimeLoader( 4764): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
W/BaseRuntimeLoader( 4764): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,W/BaseRuntimeLoader( 4764): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4764): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Parcel  (  596): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 4764): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4764): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4764): [getValue] FEATURE key : vzw_roaming_state, value : null
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
D/MobileConnectivityChangeReceiver( 4764): onReceive CONNECTIVITY_CHANGE networkType=1
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4780 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4434:com.android.defcontainer/u0a4 (adj 15): empty #17
E/PhoneMonitor( 4764): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4764): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4780): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4780): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4780): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1898): Checking schedule, now: 1450445341202 next: 1450445286455
,I/CheckinService( 1898): active receiver: enabled
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/        (  264): RouteController
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/        (  264): RouteController
,V/        (  264): RouteController
D/WifiController(  962): battery changed pluggedType: 2
,V/        (  264): RouteController
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinService( 1898): Preparing to send checkin request
,I/EventLogService( 1898): Accumulating logs since 1450445253831
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| net type = 1
V/QCNEA   (  596): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| Received ssid= NG700
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  962): GC_EXPLICIT freed 23881K, 49% free 29744K/57588K, paused 4ms+8ms, total 126ms
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4817 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4817): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Killing 4468:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4835 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/dalvikvm( 1555): GC_EXPLICIT freed 1186K, 29% free 17817K/24832K, paused 1ms+4ms, total 30ms
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4864 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 4497:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4864): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4864): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4864): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4864): intf.getDisplayName() = lo
I/Wireless_Storage( 4864): intf.getDisplayName() = sit0
I/Wireless_Storage( 4864): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4864): intf.getDisplayName() = teql0
I/Wireless_Storage( 4864): intf.getDisplayName() = wlan0
D/NFS     ( 4864): interface name:wlan0 name:wlan0
D/NFS     ( 4864): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4864): interface name:wlan0 name:wlan0
D/NFS     ( 4864): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4864): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4876 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4152:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4876): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4876): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1898): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x42af0b68: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4894 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4894): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4894): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4894): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4894): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4894): VFY: replacing opcode 0x60 at 0x000b
,V/WebViewChromium( 4876): Binding Chromium to the main looper Looper (main, tid 1) {42898ed0}
,I/chromium( 4876): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
D/dalvikvm( 4894): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4894): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4894): VFY: replacing opcode 0x62 at 0x005e
,I/BrowserProcessMain( 4876): Initializing chromium process, renderers=0
I/MultiDex( 4894): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4894): install
,I/MultiDex( 4894): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4894): loading existing secondary dex files
,I/MultiDex( 4894): load found 3 secondary dex files
,W/chromium( 4876): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/MultiDex( 4894): install done
,I/Adreno-EGL( 4876): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4876): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4876): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4876): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4876): Remote Branch: 
I/Adreno-EGL( 4876): Local Patches: 
I/Adreno-EGL( 4876): Reconstruct Branch: 
,D/dalvikvm( 4894): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4894): VFY: unable to resolve instance field 61
D/dalvikvm( 4894): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4894): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4894): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4894): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4894): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4894): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4894): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4894): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4894): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4894): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0558
,D/dalvikvm( 4894): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0558
,D/dalvikvm( 4894): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0558, skipping init
,D/dalvikvm( 4894): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0558
,D/dalvikvm( 4894): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0558
,V/JNIHelp ( 4894): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,I/NSApplication( 4876): Starting up...
,I/ActivityManager(  962): Killing 4172:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/jxcore-log( 4597): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4597): 
,D/dalvikvm( 4894): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0558
D/dalvikvm( 4894): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a0558
D/dalvikvm( 4894): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0558
,D/dalvikvm( 4894): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a0558
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4693): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4693): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4693): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4693): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4693): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4693): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4693): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4693): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4693): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4693): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4894): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1555): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1555): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1898): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1754): callingUid 10006, callindPid: 1754
,D/LocationInitializer( 1898): Restart initialization of location
,E/MDM     ( 1424): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4894): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4894): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4894): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4894): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4894): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4894): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  270): CdmEngine::OpenSession
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
D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=3877520368
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4894): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a62ca8
D/dalvikvm( 4894): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a62ca8
,D/dalvikvm( 4894): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a62ca8, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4894): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=3134391498
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4894): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4938): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 4894): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4894): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4894): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4894): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4894): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4894): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4894): Remote Branch: 
I/Adreno-EGL( 4894): Local Patches: 
I/Adreno-EGL( 4894): Reconstruct Branch: 
,I/Adreno-EGL( 4894): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4894): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4894): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4894): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4894): Remote Branch: 
I/Adreno-EGL( 4894): Local Patches: 
I/Adreno-EGL( 4894): Reconstruct Branch: 
,I/Adreno-EGL( 4894): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4894): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4894): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4894): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4894): Remote Branch: 
I/Adreno-EGL( 4894): Local Patches: 
I/Adreno-EGL( 4894): Reconstruct Branch: 
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
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1898): Sending checkin request (11595 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x42b9cab8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1898): awaiting user notification for token
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
,I/CheckinTask( 1898): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1898): Checking schedule, now: 1450445343868 next: 1451022739861
,I/CheckinService( 1898): active receiver: disabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3732): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3732): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3732): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3732): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3732): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4740): DownloadService onCreate
D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/GCM     ( 1555): Connected
I/DownloadManager( 4740): in removeSpuriousFiles
D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4509): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428eb228 on behalf of 4740
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/DownloadManager( 4740): in trimDatabase
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428ecc20 on behalf of 4740
I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4740): DownloadService onStartCommand
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4764): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4764): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428eee50 on behalf of 4740
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/GCM     ( 1555): Message class com.google.f.a.a.p
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 4740): DownloadService onDestroy
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4864): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4864): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4740): DownloadService onCreate
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4740): in removeSpuriousFiles
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
D/PhoneState( 4284): setPdpRejectCasuse : false
,V/DownloadManager( 4740): DownloadService onStartCommand
,W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4764): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4764): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428f3d38 on behalf of 4740
I/DownloadManager( 4740): in trimDatabase
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428f64f8 on behalf of 4740
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428f6710 on behalf of 4740
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4740): DownloadService onDestroy
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/dalvikvm( 4597): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4597): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4597): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4597): Shutting down VM
,W/dalvikvm( 4597): threadid=1: thread exiting with uncaught exception (group=0x4185be48)
E/AndroidRuntime( 4597): FATAL EXCEPTION: main
E/AndroidRuntime( 4597): Process: com.test.thalitest, PID: 4597
E/AndroidRuntime( 4597): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4597): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4597): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4597): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4597): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4597): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4597): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4597): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4597): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4597): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4597): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4597): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4597): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4597): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4597): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4597): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4597): 	at dalvik.system.NativeStart.main(Native Method)
,D/dalvikvm(  962): GC_EXPLICIT freed 2012K, 49% free 29634K/57588K, paused 2ms+7ms, total 87ms
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ActivityManager(  962):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f}
,I/NFS     ( 4864): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4864): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): Activity pause timeout for ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433196d0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  962): moveHomeStack:
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherAncestor( 1821): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:29:5
,D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1821): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1821): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1821): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1821): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:29:5
,D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1821): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1821): 2 : Map key string is -2
D/lim     ( 1821): 2 : time = 14:29
,I/WeatherReflect( 1821): Model Name : LG-D802
D/WeatherTheme( 1821): 2 : Different view - status_min_formatted : 27 != 29
D/WeatherTheme( 1821): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1821): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1821): 2 : Fixed theme : optimus
,D/WeatherTheme( 1821): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 6922K, 10% free 70962K/78536K, paused 37ms, total 37ms
,D/dalvikvm( 1489): GC_CONCURRENT freed 5519K, 9% free 60854K/66556K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 23ms
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 4872K, 9% free 61906K/67424K, paused 20ms, total 20ms
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42898f50 time:120655
,D/UsbSettings( 2599): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2599): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2599): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2599): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42cf7c50 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1} time:120717
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
,D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4740): DownloadService onCreate
D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4740): in removeSpuriousFiles
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428fad78 on behalf of 4740
,I/DownloadManager( 4740): in trimDatabase
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428fc420 on behalf of 4740
I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
,D/PhoneState( 4284): setPdpRejectCasuse : false
,W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4740): DownloadService onStartCommand
,D/MobileConnectivityChangeReceiver( 4764): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4764): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@428fe920 on behalf of 4740
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4740): DownloadService onDestroy
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 4864): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4864): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4876): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  962): Killing 4532:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  962): Killing 4655:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): Killing 4189:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  962): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5086 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5086): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5086): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5086): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5086): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5086): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5086): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5086): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5086): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5086): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5086): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5086): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5086): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5086): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5086): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5086): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5086): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5086): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5086): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5086): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5086): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42903ac0 on behalf of 5086
,I/dalvikvm( 5086): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5086): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5086): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5086): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5086): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5086): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5086): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5086): Total arena pages for JIT: 11
,I/dalvikvm( 5086): Total arena pages for JIT: 12
I/dalvikvm( 5086): Total arena pages for JIT: 13
,I/dalvikvm( 5086): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5086): [447] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5086): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  962): Killing 4693:com.lge.qremote/u0a96 (adj 15): empty #17
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/Finsky  ( 5086): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5086): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5086): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5086): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5086): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1555): GC_EXPLICIT freed 1273K, 29% free 17816K/24832K, paused 2ms+3ms, total 25ms
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5086): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5086): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5086): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5086): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5086): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.481049 Y: -0.406982 Z: 9.754608 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.481049 .y:-0.406982 .z:9.754608
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.478455 Y: -0.407089 Z: 9.761063 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478455 .y:-0.407089 .z:9.761063
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3989): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3989): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5165 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 5165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  962): GC_CONCURRENT freed 2222K, 47% free 30710K/57588K, paused 4ms+7ms, total 91ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 52ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 52ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 52ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 52ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 53ms
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5165): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5165): MmsConfig.loadMmsSettings
,I/Babel   ( 5165): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5165): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5165): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5165): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5165): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5165): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5165): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5165): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5165): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5165): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5165): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5165): MmsConfig.loadFromResources
,E/Babel   ( 5165): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5165): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5165): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/LGRssiData( 5165): [loadRssi] File not exist 
V/LGRssiData( 5165): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5165): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5165): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5165): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5165): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 3732): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3732): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5213 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5213): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5213): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5213): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  962): applying state to connected service
,D/LocationProviderProxy(  962): applying state to connected service
,I/SystemConfig( 5213): BUILD Country: EU
,I/SystemConfig( 5213): BUILD Operator: OPEN
I/ActivityManager(  962): Killing 4597:com.test.thalitest/u0a304 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5230 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  962): Killing 4764:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/SystemConfig( 5213): systemFeature RCS result false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/SystemConfig( 5213): refreshRcsSupport() :false
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 5230): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5230): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5230): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 16ms
I/WindowState(  962): WIN DEATH: Window{43d21468 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiService(  962): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/Binder  ( 1324): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1324): java.lang.NullPointerException
W/Binder  ( 1324): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1324): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1324): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1324): 	at dalvik.system.NativeStart.run(Native Method)
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{43cd9708 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
I/InputMethodManagerService(  962): IME STATUS OFF
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 4597 uid 10304
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 18ms
,I/IcingCorporaProvider( 2673): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  962): Killing 4780:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1898): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1898): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  962): Delaying start of: ServiceRecord{43409050 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1898): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1898): GC_CONCURRENT freed 1838K, 22% free 19556K/24832K, paused 4ms+3ms, total 35ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/IcingCorporaProvider( 2673): UpdateCorporaTask done [took 225 ms] updated apps [took 225 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  962): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5165): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6701 usec
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.470276 Y: -0.387756 Z: 9.765854 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470276 .y:-0.387756 .z:9.765854
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.484146 Y: -0.395538 Z: 9.766907 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.484146 .y:-0.395538 .z:9.766907
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  321): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.484299 Y: -0.397537 Z: 9.755524 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.484299 .y:-0.397537 .z:9.755524
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.469986 Y: -0.393646 Z: 9.759995 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469986 .y:-0.393646 .z:9.759995
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.466980 Y: -0.393250 Z: 9.765762 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466980 .y:-0.393250 .z:9.765762
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.477386 Y: -0.381439 Z: 9.765945 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.477386 .y:-0.381439 .z:9.765945
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4451afd8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.488846 Y: -0.390198 Z: 9.755585 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.488846 .y:-0.390198 .z:9.755585
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8199450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  962): No lock screen! windowToken=null
,E/SlideAside( 3989): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2021): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433c1748 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1821): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:29:23
,I/SlideAside( 3989): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,D/WeatherAncestor( 1821): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:29:23
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1821): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
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
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 397ms
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
E/BatteryObserver( 1158): usb Uevent not necessary.
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/WifiController(  962): battery changed pluggedType: 2
D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445364098, nextTick: 35933, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445364157, nextTick: 35875, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.477921 Y: -0.395309 Z: 9.782913 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.477921 .y:-0.395309 .z:9.782913
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:29:24
D/WeatherService( 1821): 2 : ACTION screen on
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:29:24
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.493591 Y: -0.416000 Z: 9.773697 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.493591 .y:-0.416000 .z:9.773697
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  962): Vibrator off
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{431df118 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1158): RESTART MSG
,D/VolumeVibrator( 1158): clear
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/WifiStateMachine(  962): handleMessage: X
E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:29:24
,D/WeatherService( 1821): 2 : ACTION screen off
D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:29:24
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  321): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Diskstats( 1898): User is not opted-in to Usage & Diagnostics.
,D/Procstats( 1898): User is not opted-in to Usage & Diagnostics.
,D/Finsky  ( 5086): [447] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5086): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445381693112378; DSPS: 5277529; Offset: 1450445220635708814
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/PerfProfileCollectorService( 1898): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1898): removeStateFiles() called
D/PerfProfileCollectorService( 1898): User is not opt-in to Usage & Diagnostics.
,D/Netstats( 1898): User is not opted-in to Usage & Diagnostics.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445400041, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445400056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445401693559830; DSPS: 5932904; Offset: 1450445220635698502
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445421694653886; DSPS: 6588300; Offset: 1450445220635693926
,D/wpa_supplicant( 2021): wlan0: BSS: Remove id 5 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 fe:94:e3:11:35:3c]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445441695115255; DSPS: 7243675; Offset: 1450445220635697531
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445460034, nextTick: 59967, mDrawingTime: 11,
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445460055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445461695571660; DSPS: 7899050; Offset: 1450445220635696172
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445481696025802; DSPS: 8554425; Offset: 1450445220635692551
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445501704698264; DSPS: 9210069; Offset: 1450445220635698020
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445520022, nextTick: 60003, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445520055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445521706062953; DSPS: 9865474; Offset: 1450445220635689418
,D/wpa_supplicant( 2021): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11],
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81],
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445541707420287; DSPS: 10520878; Offset: 1450445220635703979
,D/dalvikvm( 2661): GC_CONCURRENT freed 7764K, 32% free 16888K/24832K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 2661): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445561708803170; DSPS: 11176284; Offset: 1450445220635683053
,D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/LocationManagerService(  962): remove 4340a168
,D/dalvikvm( 2661): GC_CONCURRENT freed 1763K, 31% free 17173K/24832K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 2661): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2661): GC_CONCURRENT freed 1909K, 31% free 17268K/24832K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2661): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Mlt MonitorService( 2661): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445580028, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445580057, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445581710224695; DSPS: 11831690; Offset: 1450445220635700770
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445601711555242; DSPS: 12487094; Offset: 1450445220635688543
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445621712895584; DSPS: 13142498; Offset: 1450445220635686112
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445640035, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445640044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445641714815548; DSPS: 13797921; Offset: 1450445220635683468
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  962): GC_EXPLICIT freed 2000K, 47% free 30701K/57588K, paused 5ms+12ms, total 173ms
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x43c9fff8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1555): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1555): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1555): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1555): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5086): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5086): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5086): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5086): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5086): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445661716195803; DSPS: 14453326; Offset: 1450445220635690432
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445681717101233; DSPS: 15108716; Offset: 1450445220635680335
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445700046, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445700049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445701718052995; DSPS: 15764107; Offset: 1450445220635686052
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445721719374586; DSPS: 16419510; Offset: 1450445220635695387
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445741720274510; DSPS: 17074900; Offset: 1450445220635679784
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445760034, nextTick: 59993, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445760037, nextTick: 59994, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445761721205198; DSPS: 17730290; Offset: 1450445220635694945
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445781722532131; DSPS: 18385694; Offset: 1450445220635679104
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445801723430276; DSPS: 19041083; Offset: 1450445220635692239
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445820038, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445820047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445821724848408; DSPS: 19696489; Offset: 1450445220635706563
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445841726229209; DSPS: 20351895; Offset: 1450445220635683555
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445861727582834; DSPS: 21007299; Offset: 1450445220635694407
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445880035, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445880044, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445881728520292; DSPS: 21662690; Offset: 1450445220635685820
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445901729858114; DSPS: 22318094; Offset: 1450445220635680868
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445921730764233; DSPS: 22973483; Offset: 1450445220635701978
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445940035, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450445940037, nextTick: 59994, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445941732116109; DSPS: 23628888; Offset: 1450445220635680563
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445961733453387; DSPS: 24284292; Offset: 1450445220635675067
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450445981734947720; DSPS: 24939700; Offset: 1450445220635704556
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Disconnect event
D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 0
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2021): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2021): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  962): handleMessage: E msg.what=147460,
,D/WifiStateMachine(  962): processMsg: ConnectedState,
D/WifiStateMachine(  962): processMsg: L2ConnectedState,
,D/WifiStateMachine(  962): processMsg: ConnectModeState,
D/WifiStateMachine(  962): Network connection lost,
,D/WifiStateMachine(  962): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7c5ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5,
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
,D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
,D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiNative-wlan0(  962):    returned true
,D/DhcpStateMachine(  962): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/WifiHS20(  962): hidePasspointNotification off =false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= 
D/QCNEA   (  596): |CAC| net type = 3
V/QCNEA   (  596): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  596): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
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
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5972 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5972): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5972): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5972): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 5972): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x619b4108 clazz=0xb3d00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,D/PCSuite ( 5972): [StartReceiver][getUpdateNecessity]update = false
V/NativeCrypto( 1555): Read error: ssl=0x638f5dc8: I/O error during system call, Connection timed out
,D/PCSuite ( 5972): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1555): SSL shutdown failed: ssl=0x638f5dc8: I/O error during system call, Broken pipe
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6015 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 4817:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/DhcpStateMachine(  962): StoppedState
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6015): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6015): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6015): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 6015): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6015): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6015): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6015): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6015): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6015): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6015): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,I/VacuumService( 1555): Vacuum at: now=1450445985802 tag=VacuumService
,D/QRemote ( 6015): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6015): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,I/ActivityManager(  962): Killing 4835:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/SocketClient(  264): write error (Broken pipe)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 7 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2021): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2021): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2021): wlan0: 2: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-89 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2021): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7c5c5a8  current_ssid=0x0
D/wpa_supplicant( 2021): scard is ,not null..
D/wpa_supplicant( 2021): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2021): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2021): wlan0: Cancelling scan request,
,D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2021): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb7c5c5a8 try_opportunistic=0
D/wpa_supplicant( 2021): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2021): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2021): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 2021): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2021): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2021): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2021): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb7c5b590 (mode change)
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7c5b590,
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
,D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
,D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590,
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590,
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2021): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2021):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021):   * freq=2412
D/wpa_supplicant( 2021):   * SSID - hexdump(len=5): 4e 47 37 30 30
,D/wpa_supplicant( 2021):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2021):   * Auth Type 0
D/wpa_supplicant( 2021):   * WPA Versions 0x2
D/wpa_supplicant( 2021): nl80211: Connect request send successfully
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2021): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  962): handleMessage: X,
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X,
D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2021): nl80211: Event message available
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
,D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 f0 73 b1 10 91 c6 ba e4 07 cc bc b6 34 bd e7 8f 1a
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2021): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): 5c ba 3e 56 ea 1e ab 2d ac 97 de 6e 82 a7 a7 46 a7 83 79 97 2b 8a 8d 60 7c 23 ce d0 bb 22 06 86
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): 5c ba 3e 56 ea 1e ab 2d ac 97 de 6e 82 a7 a7 46 a7 83 79 97 2b 8a 8d 60 7c 23 ce d0 bb 22 06 86
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 f0 73 b1 10 91 c6 ba e4 07 cc bc b6 34 bd e7 8f 1a
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 61 6e 4f 8b 00 79 9f b9 fe df a3 ab 21 99 5d 53
,D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 5c ba 3e 56 ea 1e ab 2d ac 97 de 6e 82 a7 a7 ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :false
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 f0 73 b1 10 91 c6 ba e4 07 cc bc b6 34 bd e7 8f 1a
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): ed 17 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 83 6d 8c 32 a5 d2 1c 65 04 63 55 47 9f b5 29 cb
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 51 b7 75 ca 4c 7f 8d 33 40 23 ba 7a 3d af c6 ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): ac 85 0b e4 09 51 79 d2 5f bb 3c bc df b9 d4 d1 41 95 ee a5 11 03 5a 1c 8a 10 9b 46 de 4d 16 a3 ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): a6 c1 55 ee 70 ea f1 2a 67 45 59 e8 b5 20 fc 06
,D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7c5bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16),
,D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): ed 17 00 00 00 00
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6edc03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    broadcast key
I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2021): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state SUCCESS,
D/wpa_supplicant( 2021): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
,D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X,
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): Network connection established
,D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
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
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/LicenseContentProvider( 3012): start selecting data
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/SIMObserver( 3012): simInfo1
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@4308d560 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@4339d190 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-18ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
D/DhcpStateMachine(  962): StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive, 38)
D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4509): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
,W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6067 uid=10052 gids={50052, 3003}
,D/HyLog   ( 6067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6067): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/MobileConnectivityChangeReceiver( 6067): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiNative-wlan0(  962):    returned null
,E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/MobileConnectivityChangeReceiver( 6067): onReceive CONNECTIVITY_CHANGE networkType=1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,V/LGRssiData( 6067): [loadRssi] File not exist 
V/LGRssiData( 6067): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6067): [loadFeatureFromXml] *** start feature loading from xml
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
W/BaseRuntimeLoader( 6067): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6067): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/CommandListener(  264): Setting iface cfg
W/BaseRuntimeLoader( 6067): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6067): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  962): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
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
V/TelephonyAutoProfiling( 6067): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
V/TelephonyAutoProfiling( 6067): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6067): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
E/PhoneMonitor( 6067): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6067): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6082 uid=10063 gids={50063, 3003, 1028, 1015}
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/ActivityManager(  962): Killing 4864:com.lge.wireless_storage/u0a101 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
,D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  596): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: X
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/HyLog   ( 6082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6082): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6104 uid=10066 gids={50066, 4002, 3003, 1028}
,V/        (  264): RouteController
I/ActivityManager(  962): Killing 4876:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 6104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6104): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
,V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| net type = 1
V/QCNEA   (  596): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| Received ssid= NG700
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
,D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  962): Killing 4894:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6124 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/DhcpStateMachine(  962): DHCP request on wlan0
I/CheckinService( 1898): Checking schedule, now: 1450445989230 next: 1450445373861
,I/CheckinService( 1898): active receiver: enabled
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/HyLog   ( 6124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6124): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1898): Preparing to send checkin request
,I/EventLogService( 1898): Accumulating logs since 1450445341373
,D/LGDMSGCM( 6124): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6146 uid=10101 gids={50101, 1028, 1015, 3003}
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6146): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6146): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6146): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6146): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6146): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6146): intf.getDisplayName() = lo
I/Wireless_Storage( 6146): intf.getDisplayName() = sit0
I/Wireless_Storage( 6146): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 6146): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6146): intf.getDisplayName() = wlan0
D/NFS     ( 6146): interface name:wlan0 name:wlan0
D/NFS     ( 6146): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6146): interface name:wlan0 name:wlan0
D/NFS     ( 6146): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 6146): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6158 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 5165:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6158): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 6158): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x44eda3f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1898): awaiting user notification for token
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6178 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6178): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6178): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6178): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6178): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6178): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6178): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6178): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6178): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6178): install
,I/MultiDex( 6178): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6178): loading existing secondary dex files
,I/MultiDex( 6178): load found 3 secondary dex files
,I/MultiDex( 6178): install done
,V/WebViewChromium( 6158): Binding Chromium to the main looper Looper (main, tid 1) {4289b750}
,I/chromium( 6158): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6158): Initializing chromium process, renderers=0
D/dalvikvm( 6178): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6178): VFY: unable to resolve instance field 61
,D/dalvikvm( 6178): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6178): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6178): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6178): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6178): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6178): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6178): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6178): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6178): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6178): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2900
,D/dalvikvm( 6178): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2900
,D/dalvikvm( 6178): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2900, skipping init
,D/dalvikvm( 6178): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2900
,D/dalvikvm( 6178): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2900
,V/JNIHelp ( 6178): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Adreno-EGL( 6158): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6158): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6158): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6158): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6158): Remote Branch: 
I/Adreno-EGL( 6158): Local Patches: 
I/Adreno-EGL( 6158): Reconstruct Branch: 
,W/chromium( 6158): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NSApplication( 6158): Starting up...
,I/ActivityManager(  962): Killing 5213:com.android.contacts/u0a21 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6178): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2900
,D/dalvikvm( 6178): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a2900
D/dalvikvm( 6178): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2900
,D/dalvikvm( 6178): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a2900
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6015): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6015): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6015): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6015): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6015): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6015): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5972): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5972): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6015): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6015): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6015): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6015): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 6178): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1555): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1555): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1898): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
,D/WearableService( 1754): callingUid 10006, callindPid: 1754
,E/MDM     ( 1424): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1898): Restart initialization of location
,I/dalvikvm( 6178): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6178): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6178): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6178): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 6178): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6178): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=1731128870
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6178): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6df78
,D/dalvikvm( 6178): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6df78
,D/dalvikvm( 6178): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a6df78, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 6178): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,D/WifiStateMachine(  962): handleMessage: X
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
W/ProcessCpuTracker(  962): Skipping unknown process pid 6053
W/ProcessCpuTracker(  962): Skipping unknown process pid 6054
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
W/ProcessCpuTracker(  962): Skipping unknown process pid 6058
W/ProcessCpuTracker(  962): Skipping unknown process pid 6061
W/ProcessCpuTracker(  962): Skipping unknown process pid 6170
,W/ProcessCpuTracker(  962): Skipping unknown process pid 6216
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=2965258280
D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,D/dalvikvm(  962): GC_EXPLICIT freed 3013K, 47% free 30593K/57588K, paused 11ms+11ms, total 166ms
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/dalvikvm( 6178): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6254): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 6178): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6178): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 92ms
,I/Adreno-EGL( 6178): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6178): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6178): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6178): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6178): Remote Branch: 
I/Adreno-EGL( 6178): Local Patches: 
I/Adreno-EGL( 6178): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6178): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6178): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6178): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6178): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6178): Remote Branch: 
I/Adreno-EGL( 6178): Local Patches: 
I/Adreno-EGL( 6178): Reconstruct Branch: 
,I/Adreno-EGL( 6178): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6178): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6178): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6178): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6178): Remote Branch: 
I/Adreno-EGL( 6178): Local Patches: 
I/Adreno-EGL( 6178): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
,V/NativeCrypto( 1898): SSL shutdown failed: ssl=0x6b936338: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/NativeCrypto( 1898): SSL shutdown failed: ssl=0x6bc13918: I/O error during system call, Connection timed out
,I/CheckinTask( 1898): Sending checkin request (11596 bytes)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
,D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3732): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3732): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3732): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3732): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3732): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4740): DownloadService onCreate
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4509): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6067): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6067): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4740): in removeSpuriousFiles
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42908580 on behalf of 4740
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4740): in trimDatabase
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42909fb8 on behalf of 4740
D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4740): DownloadService onStartCommand
W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMSGCM( 6124): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@4290c168 on behalf of 4740
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6146): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6146): CONNECT : WIFI_CONNECT
E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4740): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4740): DownloadService onCreate
,I/DownloadManager( 4740): in removeSpuriousFiles
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42910888 on behalf of 4740
D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4740): DownloadService onStartCommand
V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4740): in trimDatabase
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42913810 on behalf of 4740
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42913a28 on behalf of 4740
,V/DownloadManager( 4740): DownloadService onDestroy
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
,D/PhoneState( 4284): setPdpRejectCasuse : false
,W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6067): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6067): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6124): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6146): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6146): CONNECT : WIFI_CONNECT
E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1555): GC_CONCURRENT freed 1867K, 29% free 17870K/24832K, paused 3ms+3ms, total 36ms
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/CheckinRequestBuilder( 1898): awaiting user notification for token
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x441d8a10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1898): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1898): Checking schedule, now: 1450445992737 next: 1451023388732
,I/CheckinService( 1898): active receiver: disabled
,I/CheckinService( 1898): Checking schedule, now: 1450445992778 next: 1451023388732
,I/CheckinService( 1898): active receiver: disabled
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4740): DownloadService onCreate
,D/EAS     ( 4509): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
,D/PhoneState( 4284): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6067): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6067): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6124): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6146): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6146): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4740): in removeSpuriousFiles
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4740): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 4509): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42918058 on behalf of 4740
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4740): DownloadService onStartCommand
,I/DownloadManager( 4740): in trimDatabase
,V/DownloadManager( 4740): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4740): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@42919ec8 on behalf of 4740
,D/dalvikvm( 3876): GC_FOR_ALLOC freed 373K, 2% free 37940K/38604K, paused 44ms, total 44ms
,V/DownloadManager( 4740): created cursor android.database.sqlite.SQLiteCursor@4291bb98 on behalf of 4740
,V/DownloadManager( 4740): DownloadService onDestroy
,I/GoogleURLConnFactory( 1555): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1555): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1555): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1555): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 6158): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/ActivityManager(  962): Killing 5086:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  962): Killing 5230:com.android.gallery3d/u0a27 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,W/Uploader( 1555): No account for auth token provided
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,W/Uploader( 1555):  no longer exists, so no auth token.
,W/Uploader( 1555): No account for auth token provided
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3989): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3989): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6371 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 6371): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6371): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6371): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/Babel   ( 6371): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6371): MmsConfig.loadMmsSettings
,I/MediaCodecList( 6371): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6371): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6371): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 6371): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 6371): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6371): MmsConfig.loadFromDatabase
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 6371): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6371): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6371): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6371): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6371): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6371): MmsConfig.loadFromResources
,E/Babel   ( 6371): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6371): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6371): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationProviderProxy(  962): applying state to connected service
,D/LocationProviderProxy(  962): applying state to connected service
,V/LGRssiData( 6371): [loadRssi] File not exist 
V/LGRssiData( 6371): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6371): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6371): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6371): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6371): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3732): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3732): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6420 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6420): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6420): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6420): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+5ms, total 44ms
,I/SystemConfig( 6420): BUILD Country: EU
,I/SystemConfig( 6420): BUILD Operator: OPEN
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 35ms
I/ActivityManager(  962): Killing 5972:com.lge.sync/1000 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6445 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446000036, nextTick: 59996, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446000037, nextTick: 59996, mDrawingTime: 0
,I/SystemConfig( 6420): systemFeature RCS result false
,D/SystemConfig( 6420): refreshRcsSupport() :false
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  962): Killing 6015:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6445): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6445): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6445): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 4740:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2673): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6463 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6463): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6463): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6463): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1898): GC_CONCURRENT freed 1919K, 22% free 19586K/24832K, paused 5ms+6ms, total 65ms
,D/dalvikvm(  962): GC_EXPLICIT freed 2283K, 47% free 30687K/57588K, paused 5ms+13ms, total 152ms
,I/dalvikvm( 6463): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6463): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6463): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6463): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6463): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x004f
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 6463): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6463): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6463): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6463): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6463): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6463): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6463): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6463): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,I/IcingCorporaProvider( 2673): UpdateCorporaTask done [took 498 ms] updated apps [took 498 ms] 
W/dalvikvm( 6463): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x011e
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6463): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6463): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6463): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6463): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 6463): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6463): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6509 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6509): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6509): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6509): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6463): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6463): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6463): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6463): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6463): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1898): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1898): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1898): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6509): DownloadService onCreate
,I/DownloadManager( 6509): in removeSpuriousFiles
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428daa18 on behalf of 6463
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6509): DownloadService onStartCommand
V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428dcc10 on behalf of 6509
,V/DownloadManager( 6509): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6509): in trimDatabase
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428dfe30 on behalf of 6509
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428e03f8 on behalf of 6509
,D/Finsky  ( 6463): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6509): DownloadService onDestroy
,D/Finsky  ( 6463): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  962): Killing 4509:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6463): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6463): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6463): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6463): VFY: replacing opcode 0x62 at 0x0037
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446001740116588; DSPS: 25595230; Offset: 1450445220635685436
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6463): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6463): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6463): Total arena pages for JIT: 11
,I/dalvikvm( 6463): Total arena pages for JIT: 12
I/dalvikvm( 6463): Total arena pages for JIT: 13
,I/dalvikvm( 6463): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1555): GC_CONCURRENT freed 1794K, 28% free 18054K/24832K, paused 3ms+5ms, total 53ms
,W/Finsky  ( 6463): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6463): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6463): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6463): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6371): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 6067:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6463): [495] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6463): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446021741482543; DSPS: 26250635; Offset: 1450445220635678100
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446041742393898; DSPS: 26906024; Offset: 1450445220635704445
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446060033, nextTick: 59997, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446060036, nextTick: 59996, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446061742959279; DSPS: 27561403; Offset: 1450445220635689992
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446081744311061; DSPS: 28216807; Offset: 1450445220635699001
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446101745217031; DSPS: 28872197; Offset: 1450445220635689444
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446120032, nextTick: 59998, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446120035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446121746635256; DSPS: 29527603; Offset: 1450445220635703860
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446141747968637; DSPS: 30183007; Offset: 1450445220635694468
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446161748850261; DSPS: 30838396; Offset: 1450445220635691082
,D/wpa_supplicant( 2021): wlan0: BSS: Remove id 7 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446180048, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446180057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446181749961321; DSPS: 31493793; Offset: 1450445220635672991
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446201751324341; DSPS: 32149197; Offset: 1450445220635693238
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446221751767009; DSPS: 32804572; Offset: 1450445220635678142
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446240042, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446240055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446241752715674; DSPS: 33459963; Offset: 1450445220635680762
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446261754733761; DSPS: 34115389; Offset: 1450445220635684689
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446281755176593; DSPS: 34770763; Offset: 1450445220635700275
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446300034, nextTick: 59982, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446300044, nextTick: 59988, mDrawingTime: 0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x433a1718: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1555): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1555): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1555): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1555): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6463): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6463): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6463): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6463): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6463): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6463): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6463): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6463): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6463): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6463): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446301756539911; DSPS: 35426168; Offset: 1450445220635690302
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446321757916735; DSPS: 36081573; Offset: 1450445220635693835
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446341758855589; DSPS: 36736964; Offset: 1450445220635686644
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446360027, nextTick: 60001, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446360048, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446361759771741; DSPS: 37392354; Offset: 1450445220635687269
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446381761075875; DSPS: 38047757; Offset: 1450445220635679147
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446401761530145; DSPS: 38703131; Offset: 1450445220635706171
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Disconnect event
D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 0
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2021): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2021): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147460,
D/WifiStateMachine(  962): processMsg: ConnectedState,
D/WifiStateMachine(  962): processMsg: L2ConnectedState,
D/WifiStateMachine(  962): processMsg: ConnectModeState,
,D/WifiStateMachine(  962): Network connection lost,
,D/WifiStateMachine(  962): Stopping DHCP and clearing IP,
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7c5ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  962): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/DhcpStateMachine(  962): RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 0
,D/WifiHS20(  962): hidePasspointNotification off =false
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= 
D/QCNEA   (  596): |CAC| net type = 3
V/QCNEA   (  596): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  596): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
,D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11,
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  962): Attempting to switch to mobile
,D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6937 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
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
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '96 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 96 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 6937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6937): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 6937): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
D/PCSuite ( 6937): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6937): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 route del src v6 2' failed with '400 99 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x619b4108 clazz=0xfae00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6975 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 6082:com.android.chrome/u0a63 (adj 15): empty #17
,V/NativeCrypto( 1555): Read error: ssl=0x639ecc58: I/O error during system call, Connection timed out
,V/NativeCrypto( 1555): SSL shutdown failed: ssl=0x639ecc58: I/O error during system call, Broken pipe
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6975): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  962): StoppedState
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 6975): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 6975): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6975): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6975): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6975): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6975): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6975): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6975): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6975): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 6104:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/SocketClient(  264): write error (Broken pipe)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446420050, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446420055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446421766232529; DSPS: 39358646; Offset: 1450445220635678330
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
,D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,I/LicenseContentProvider( 3012): start selecting data
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2021): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2021): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2021): wlan0: 2: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-88 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2021): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7c5c5a8  current_ssid=0x0
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: [Events.c:1455]Request assoc,iation: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
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
D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb7c5c5a8 try_opportunistic=0
D/wpa_supplicant( 2021): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2021): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2021): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2021): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2021): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb7c5b590 (mode change)
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7c5b590
,D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590,
,D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
,D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb7c5b590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2021): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2021):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021):   * freq=2412
D/wpa_supplicant( 2021):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2021):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021):   * Auth Type 0
D/wpa_supplicant( 2021):   * WPA Versions 0x2
D/wpa_supplicant( 2021): nl80211: Connect request send successfully
,D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE ,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  962): handleMessage: E msg.what=147461,
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/SIMObserver( 3012): simInfo1
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
,D/wpa_supplicant( 2021): nl80211: Event message available
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 98 d9 f3 cf 7f 61 70 44 53 de 0d 76 1c cd 0c f3 f3
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2021): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): 84 84 5f 11 49 1e 4b 98 35 bb 21 47 36 79 e5 82 d7 25 03 10 4e 4e 7c e1 01 f6 18 b6 a9 50 f7 88
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): 84 84 5f 11 49 1e 4b 98 35 bb 21 47 36 79 e5 82 d7 25 03 10 4e 4e 7c e1 01 f6 18 b6 a9 50 f7 88
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 98 d9 f3 cf 7f 61 70 44 53 de 0d 76 1c cd 0c f3 f3
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 09 1f 38 ce 1f ed a5 45 ab 0c 3a 5e 19 ac ca a7
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 84 84 5f 11 49 1e 4b 98 35 bb 21 47 36 79 e5 ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 98 d9 f3 cf 7f 61 70 44 53 de 0d 76 1c cd 0c f3 f3
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 9e 19 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): eb 26 eb 9d ec d9 27 d9 a6 ef 97 78 f7 b1 87 fd
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 33 97 6f a3 0b 14 c3 0c ca e4 70 73 98 ad e2 ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): c1 8f 74 3e e5 75 e7 94 2c 62 95 c4 d7 24 0a d7 92 7a 7e 8f 0b 6b b8 67 05 cd d8 04 ae 2b 07 e2 ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 12 23 41 a2 78 cd 3b fd b1 1b b0 a0 e9 a6 52 aa
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7c5bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): 9e 19 00 00 00 00
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6edc03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    broadcast key
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/WifiStateMachine(  962): handleMessage: X
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection established
D/WifiNative-wlan0(  962): doString: STATUS
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7019 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@44a50ff0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/DhcpStateMachine(  962): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: X
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  962): ObtainingIpState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@446ded78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 7019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7019): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  962): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd248 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): DHCP successful
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,E/Parcel  (  596): Reading a NULL string not supported here.
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/dalvikvm(  962): GC_EXPLICIT freed 2372K, 47% free 30642K/57588K, paused 4ms+11ms, total 156ms
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
I/LGEmail ( 7019): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
,D/LGEmail ( 7019): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7019): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| net type = 1
V/QCNEA   (  596): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| Received ssid= NG700
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8c438dc
D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
,W/linker  ( 7019): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 7019): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 7019): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 7019): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 7019): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 7019): register_HtmlEditor, Success
,D/HtmlEditor( 7019): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7019): register_HtmlEditorTimer, Success
D/HtmlEditor( 7019): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7019): register_HtmlEditorDownloader, Success
D/HtmlEditor( 7019): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7019): register_HtmlEditorFont, Success
,D/HtmlEditor( 7019): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7019): register_HtmlEditorDrawText, Success
D/HtmlEditor( 7019): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7019): register_HtmlEditorDrawImage, Success
,D/HtmlEditor( 7019): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7019): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 7019): JNI_OnLoad Success
I/HubEmail( 7019): JNI_OnLoad()
,I/HubEmail( 7019): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7019): registerNatives()
I/HubEmail( 7019): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7019): registerNativeMethods()
,I/HubEmail( 7019): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 7019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=7079 uid=10052 gids={50052, 3003}
,D/HyLog   ( 7079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7079): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): Killing 6124:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7079): [loadRssi] File not exist 
,V/LGRssiData( 7079): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7079): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 7079): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7079): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7079): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 7079): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 7079): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 7079): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 7079): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7079): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7079): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7094 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 6146:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,E/PhoneMonitor( 7079): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 7079): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1898): Checking schedule, now: 1450446422401 next: 1450446022732
,I/CheckinService( 1898): active receiver: enabled
,I/CheckinService( 1898): Preparing to send checkin request
I/EventLogService( 1898): Accumulating logs since 1450445989279
D/HyLog   ( 7094): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7094): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7094): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7108 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 7108): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7108): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7108): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 6158:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7121 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7121): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7121): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7121): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 7121): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7134 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 6178:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,D/HyLog   ( 7134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7134): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 17ms
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,I/NFS     ( 7134): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Wireless_Storage( 7134): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 7134): intf.getDisplayName() = lo
I/Wireless_Storage( 7134): intf.getDisplayName() = sit0
I/Wireless_Storage( 7134): intf.getDisplayName() = p2p0
I/Wireless_Storage( 7134): intf.getDisplayName() = teql0
,I/Wireless_Storage( 7134): intf.getDisplayName() = wlan0
D/NFS     ( 7134): interface name:wlan0 name:wlan0
D/NFS     ( 7134): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 7134): interface name:wlan0 name:wlan0
D/NFS     ( 7134): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 7134): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7147 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 6371:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7147): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7147): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7147): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4334da28: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1898): awaiting user notification for token
,W/GAV2    ( 7147): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7165 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 7165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 7165): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7165): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 7165): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7165): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7165): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 7165): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7165): install
,I/MultiDex( 7165): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7165): loading existing secondary dex files
,I/MultiDex( 7165): load found 3 secondary dex files
,I/MultiDex( 7165): install done
,D/dalvikvm( 7165): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7165): VFY: unable to resolve instance field 61
,D/dalvikvm( 7165): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 7165): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7165): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7165): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 7165): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7165): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7165): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7165): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7165): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7165): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289b358
D/dalvikvm( 7165): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289b358
,D/dalvikvm( 7165): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289b358, skipping init
,D/dalvikvm( 7165): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289b358
D/dalvikvm( 7165): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289b358
,V/JNIHelp ( 7165): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
,D/dalvikvm( 7165): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289b358
,D/dalvikvm( 7165): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4289b358
D/dalvikvm( 7165): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289b358
,D/dalvikvm( 7165): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4289b358
,V/WebViewChromium( 7147): Binding Chromium to the main looper Looper (main, tid 1) {42893c90}
,I/ProviderInstaller( 7165): Installed default security provider GmsCore_OpenSSL
,I/chromium( 7147): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7147): Initializing chromium process, renderers=0
,I/dalvikvm( 7165): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 7165): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7165): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7165): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 7165): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7165): VFY: replacing opcode 0x6e at 0x0201
,W/chromium( 7147): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7147): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7147): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7147): Remote Branch: 
I/Adreno-EGL( 7147): Local Patches: 
I/Adreno-EGL( 7147): Reconstruct Branch: 
,I/NSApplication( 7147): Starting up...
,I/ActivityManager(  962): Killing 6420:com.android.contacts/u0a21 (adj 15): empty #17
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb214f000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/QRemote ( 6975): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6975): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/QRemote ( 6975): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,I/QRemote ( 6975): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/QRemote ( 6975): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6975): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6937): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/PCSuite ( 6937): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6975): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6975): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6975): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6975): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/AuthorizationBluetoothService( 1555): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1555): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1898): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=476430696
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/WearableService( 1754): callingUid 10006, callindPid: 1754
,E/MDM     ( 1424): [71] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1898): Restart initialization of location
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,D/dalvikvm( 7165): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5abe0
D/dalvikvm( 7165): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5abe0
,D/dalvikvm( 7165): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5abe0, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 7165): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=612943208
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7021
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7022
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7037
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7039
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7048
,W/ProcessCpuTracker(  962): Skipping unknown process pid 7230
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  962): handleMessage: X
,D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 7165): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 7246): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 7165): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7165): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 98ms
,I/Adreno-EGL( 7165): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7165): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7165): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7165): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7165): Remote Branch: 
I/Adreno-EGL( 7165): Local Patches: 
I/Adreno-EGL( 7165): Reconstruct Branch: 
,I/Adreno-EGL( 7165): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7165): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7165): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7165): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7165): Remote Branch: 
I/Adreno-EGL( 7165): Local Patches: 
I/Adreno-EGL( 7165): Reconstruct Branch: 
,I/Adreno-EGL( 7165): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7165): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7165): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7165): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7165): Remote Branch: 
I/Adreno-EGL( 7165): Local Patches: 
I/Adreno-EGL( 7165): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,V/NativeCrypto( 1898): SSL shutdown failed: ssl=0x6bc0c9d0: I/O error during system call, Connection timed out
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1898): Sending checkin request (11591 bytes)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3732): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3732): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3732): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3732): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3732): handleAsyncCustNotification do not startCustService
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6509): DownloadService onCreate
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 7019): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4284): networkInfo.isConnected() = false
,I/DownloadManager( 6509): in removeSpuriousFiles
V/DownloadManager( 6509): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 7079): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7079): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428e80b8 on behalf of 6509
,W/Settings( 7019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 6509): in trimDatabase
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428e9688 on behalf of 6509
,V/DownloadManager( 6509): DownloadService onStartCommand
,V/DownloadManager( 6509): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428ebcb8 on behalf of 6509
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMSGCM( 7121): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 6509): DownloadService onDestroy
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 7134): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7134): CONNECT : WIFI_CONNECT
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6509): DownloadService onCreate
,I/DownloadManager( 6509): in removeSpuriousFiles
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428f0750 on behalf of 6509
,D/dalvikvm(  962): GC_EXPLICIT freed 1815K, 47% free 30617K/57588K, paused 3ms+6ms, total 93ms
,I/DownloadManager( 6509): in trimDatabase
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6509): DownloadService onStartCommand
V/DownloadManager( 6509): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
,D/PhoneState( 4284): setPdpRejectCasuse : false
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428f1cd8 on behalf of 6509
D/MobileConnectivityChangeReceiver( 7079): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 7019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 7079): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428f35b8 on behalf of 6509
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6509): DownloadService onDestroy
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7121): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 7134): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7134): CONNECT : WIFI_CONNECT
E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/EventLogService( 1898): Aggregate from 1450446422452 (log), 1450444577700 (data)
,I/CheckinRequestBuilder( 1898): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1898): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x431393e0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1898): awaiting user notification for token
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1898): Classify the device as Phone.
,I/CheckinTask( 1898): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1898): Checking schedule, now: 1450446426401 next: 1451023822398
,I/CheckinService( 1898): active receiver: disabled
,D/GCM     ( 1555): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinService( 1898): Checking schedule, now: 1450446426451 next: 1451023822398
,I/CheckinService( 1898): active receiver: disabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1555): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3732): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
,D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
,D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3732): begin check event
,I/AppUp4:CustModeStarterReceiver( 3732): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/DownloadManager( 6509): DownloadService onCreate
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/EAS     ( 7019): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4284): networkInfo.isConnected() = true
,D/PhoneState( 4284): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 7079): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7079): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2848): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7121): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7134): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7134): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/DownloadManager( 6509): in removeSpuriousFiles
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428f7ba8 on behalf of 6509
,D/LGDMClient( 2848): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 6509): in trimDatabase
,V/DownloadManager( 6509): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 7019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LGDMClient( 2848): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428f94d8 on behalf of 6509
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LGDMClient( 2848): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 6509): DownloadService onStartCommand
D/LGDMClient( 2848): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2848): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2848): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 6509): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6509): created cursor android.database.sqlite.SQLiteCursor@428fb768 on behalf of 6509
,V/DownloadManager( 6509): DownloadService onDestroy
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 7147): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 6463:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  962): Killing 6445:com.android.gallery3d/u0a27 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7365 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  962): Handling package changes for user 0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mmsto"
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 3989): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3989): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 7365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7365): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
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
,I/Babel   ( 7365): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7365): MmsConfig.loadMmsSettings
,I/Babel   ( 7365): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 7365): MmsConfig.loadFromDatabase
,I/MediaCodecList( 7365): getNewMediaCodecItem [0][DTSDecode][audio/dts]
W/BaseRuntimeLoader( 7365): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,I/MediaCodecList( 7365): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 7365): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
W/BaseRuntimeLoader( 7365): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/MediaCodecList( 7365): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 7365): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7365): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 7365): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7365): MmsConfig.loadFromResources
,E/Babel   ( 7365): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7365): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/Settings( 7365): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GmsNetworkLocationProvi( 1424): DISABLE
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7365): [loadRssi] File not exist 
V/LGRssiData( 7365): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7365): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 7365): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7365): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7365): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3732): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3732): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): onReceive
D/AppUp4:CustFacade( 3732): Context : android.app.ReceiverRestrictedContext@428ad1e0
D/AppUp4:CustFacade( 3732): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3732): isOpenOperator : true
,D/AppUp4:CustFacade( 3732): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 3732): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3732): begin check event
D/AppUp4:Utils( 3732): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3732): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7412 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/LocationProviderProxy(  962): applying state to connected service
,D/HyLog   ( 7412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7412): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  962): applying state to connected service
,I/SystemConfig( 7412): BUILD Country: EU
,I/SystemConfig( 7412): BUILD Operator: OPEN
I/ActivityManager(  962): Killing 6937:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): Killing 6975:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7428 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,I/SystemConfig( 7412): systemFeature RCS result false
,D/SystemConfig( 7412): refreshRcsSupport() :false
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7428): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 6509:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2673): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7445 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7445): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7445): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7445): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1555): GC_EXPLICIT freed 1348K, 28% free 17999K/24832K, paused 4ms+6ms, total 55ms
,I/dalvikvm( 7445): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7445): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7445): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1898): GC_CONCURRENT freed 2036K, 22% free 19584K/24832K, paused 4ms+5ms, total 60ms
I/dalvikvm( 7445): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7445): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7445): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7445): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7445): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7445): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7445): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7445): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7445): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7445): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7445): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 7445): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7445): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7445): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7445): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x029a
I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7482 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2673): UpdateCorporaTask done [took 324 ms] updated apps [took 324 ms] 
,I/dalvikvm( 7445): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 7445): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x001a
D/HyLog   ( 7482): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7482): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7482): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7445): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7445): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7445): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 7445): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7445): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1898): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1898): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1898): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm(  962): GC_EXPLICIT freed 2120K, 47% free 30754K/57588K, paused 5ms+14ms, total 170ms
,V/DownloadManager( 7482): DownloadService onCreate
,I/DownloadManager( 7482): in removeSpuriousFiles
,V/DownloadManager( 7482): DownloadService onStartCommand
,V/DownloadManager( 7482): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7482): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7482): created cursor android.database.sqlite.SQLiteCursor@428dd850 on behalf of 7482
,V/DownloadManager( 7482): created cursor android.database.sqlite.SQLiteCursor@428dea38 on behalf of 7482
V/DownloadManager( 7482): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 7482): in trimDatabase
,V/DownloadManager( 7482): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 7482): created cursor android.database.sqlite.SQLiteCursor@428e4b58 on behalf of 7482
,V/DownloadManager( 7482): created cursor android.database.sqlite.SQLiteCursor@428e4858 on behalf of 7445
,V/DownloadManager( 7482): DownloadService onDestroy
,D/Finsky  ( 7445): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  962): Killing 7019:com.lge.email/u0a24 (adj 15): empty #17
,D/Finsky  ( 7445): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7445): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7445): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7445): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7445): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7445): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7445): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7445): Total arena pages for JIT: 11
,I/dalvikvm( 7445): Total arena pages for JIT: 12
,I/dalvikvm( 7445): Total arena pages for JIT: 13
,I/dalvikvm( 7445): Total arena pages for JIT: 14
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7445): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7445): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7445): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7445): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.78/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GAV4    ( 7365): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 7079:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c6a8b0 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446441767632358; DSPS: 40014052; Offset: 1450445220635674351
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7445): [540] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7445): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446461768560212; DSPS: 40669442; Offset: 1450445220635686677
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446480035, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446480037, nextTick: 59995, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446481769024434; DSPS: 41324817; Offset: 1450445220635693136
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446501770361347; DSPS: 41980221; Offset: 1450445220635687275
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446521770808380; DSPS: 42635595; Offset: 1450445220635707062
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446540035, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446540053, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446541771836707; DSPS: 43290989; Offset: 1450445220635697791
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446561773176954; DSPS: 43946393; Offset: 1450445220635695265
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446581773625341; DSPS: 44601768; Offset: 1450445220635685888
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446600051, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446600058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446601774594309; DSPS: 45257159; Offset: 1450445220635708811
,D/wpa_supplicant( 2021): wlan0: BSS: Remove id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:97]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446621775982426; DSPS: 45912565; Offset: 1450445220635693120
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446641776420151; DSPS: 46567939; Offset: 1450445220635703599
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446660040, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446660051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446661777376968; DSPS: 47223331; Offset: 1450445220635683853
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446681778782117; DSPS: 47878737; Offset: 1450445220635685194
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446701779238843; DSPS: 48534112; Offset: 1450445220635684156
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446720029, nextTick: 59997, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446720052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446721780645029; DSPS: 49189518; Offset: 1450445220635686533
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x42aceb30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1555): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1555): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1555): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1555): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 7445): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7445): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7445): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 7445): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7445): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 7445): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7445): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 7445): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 7445): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 7445): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446741781541930; DSPS: 49844907; Offset: 1450445220635698425
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446761782028804; DSPS: 50500283; Offset: 1450445220635697017
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446780028, nextTick: 59995, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446780055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446781783004606; DSPS: 51155675; Offset: 1450445220635696257
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446801784942093; DSPS: 51811099; Offset: 1450445220635680619
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446821785402227; DSPS: 52466474; Offset: 1450445220635682989
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446840034, nextTick: 59994, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446840047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446841786792142; DSPS: 53121879; Offset: 1450445220635699613
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446861788125372; DSPS: 53777283; Offset: 1450445220635690070
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446881788572835; DSPS: 54432657; Offset: 1450445220635710287
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446900036, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446900038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446901789556651; DSPS: 55088050; Offset: 1450445220635687023
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446921790900327; DSPS: 55743454; Offset: 1450445220635687925
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446941791332965; DSPS: 56398828; Offset: 1450445220635693317
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446960033, nextTick: 59983, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450446960045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446961792338947; DSPS: 57054221; Offset: 1450445220635692219
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450446981794293297; DSPS: 57709645; Offset: 1450445220635693444
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447001794736591; DSPS: 58365019; Offset: 1450445220635709492
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447020032, nextTick: 59982, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447020044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447021795696072; DSPS: 59020411; Offset: 1450445220635692410
,I/ProcessStatsService(  962): Prepared write state in 53ms
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2015-12-17-18-45-00.bin
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447041799319974; DSPS: 59675890; Offset: 1450445220635684721
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447061800199569; DSPS: 60331279; Offset: 1450445220635679306
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447080026, nextTick: 60000, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447080048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447081801562024; DSPS: 60986683; Offset: 1450445220635698987
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447101802944238; DSPS: 61642089; Offset: 1450445220635677393
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447121803383668; DSPS: 62297463; Offset: 1450445220635689577
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447140032, nextTick: 59981, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450447140045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1450447141804345759; DSPS: 62952854; Offset: 1450445220635705623
,TIME-OUT KILL (timeout was 1800000ms)
```
