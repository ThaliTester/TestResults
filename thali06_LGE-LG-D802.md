#### Test 5065027857de7f1_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Loading module APK com.google.android.play.games
--------- beginning of /dev/log/system
I/ActivityManager(  965): Delaying start of: ServiceRecord{43b57460 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1945): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1945): launchTask
W/dalvikvm( 1945): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
W/GAV2    ( 4119): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  965): Killing 3395:com.google.android.music:main/u0a107 (adj 15): empty #17
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.vision from APK com.google.android.gms
V/ConfigFetchTask( 1945): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VKhbwElEV7aoYo3AIw9Azs0zGNODxy8xSh4kQrc8HcMtsR-nIIBXcN9kVAz42c7tFcCAzlRKZDGuSX2SP3_5KJP-CPALdCf-JZHGGLjy_JOFaPcZ-xxNwVStQBrwpuTtZOHfOwsQU2mhspp3L07prynmUEslr3dYbuHbK0Nhg8SQ1vFR0Ihr5qt_33qNpJmkrOztomzSUcTvkkSelb1ec3S16a_F-ucXG5_V-kzpY_DM81Q-Q
D/Vision  ( 1945): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1945): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1945): No vision deps
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PeopleContactsSync( 1945): CP2 sync disabled
I/GoogleURLConnFactory( 1945): Using platform SSLCertificateSocketFactory
F/ActivityManager(  965): Service ServiceRecord{433166c0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{431e00a0 3395:com.google.android.music:main/u0a107} not same as in map: null
I/dalvikvm( 1945): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1945): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1945): VFY: replacing opcode 0x6e at 0x000e
F/ActivityManager(  965): Service ServiceRecord{431d5a08 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{431e00a0 3395:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
E/DataScheduler( 1945): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1945): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1945): fetch service done; releasing wakelock
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
I/ConfigFetchService( 1945): stopping self
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
D/AndroidRuntime( 4159): 
D/AndroidRuntime( 4159): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4159): CheckJNI is OFF
D/dalvikvm( 4159): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4159): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4159): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4159): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4159): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4159): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1945): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 1945): GC_CONCURRENT freed 1616K, 26% free 18440K/24832K, paused 2ms+4ms, total 25ms
D/Icing   ( 1945): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1945): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
E/memtrack( 4159): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4159): failed to load memtrack module: -2
D/AndroidRuntime( 4159): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4159
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (119 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{42b69160 stackId=1, 2 tasks}
D/AndroidRuntime( 4159): Shutting down VM
D/UsbSettingsControl( 2517): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2517): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3569): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4159): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3569): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3569): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4200 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4200): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
V/WebViewChromium( 4200): Binding Chromium to the background looper Looper (main, tid 1) {4280dc78}
I/chromium( 4200): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4200): Initializing chromium process, renderers=0
W/chromium( 4200): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4200): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4200): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4200): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4200): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4200): Remote Branch: 
I/Adreno-EGL( 4200): Local Patches: 
I/Adreno-EGL( 4200): Reconstruct Branch: 
I/dalvikvm( 4200): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4200): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4200): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4200): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4200): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4200): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4200): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4200): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4200): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4200): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4200): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4200): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4200): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4200): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4200): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4200): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4200): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4200): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4200): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4200): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 4200): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4200): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4200): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4200): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4200): Enabling debug mode 0
W/AwContents( 4200): nativeOnDraw failed; clearing to background color.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/InputMethodManagerService(  965): IME STATUS OFF
W/AwContents( 4200): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +481ms
I/ActivityManager( 4200): Timeline: Activity_idle id: android.os.BinderProxy@4280f3b8 time:110064
D/JsMessageQueue( 4200): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3} time:110320
D/ActivityManager(  965): no-history finish of ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{431bf028 ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2517): [AUTORUN] onStop()
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4200): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 4200): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428138f8
D/dalvikvm( 4200): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428138f8
D/jxcore_app_log( 4200): JniHelper::setJavaVM(0x416da838), pthread_self() = 1631817608
D/JX-Cordova( 4200): jxcore cordova android initializing
I/dalvikvm( 4200): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4200): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4200): VFY: replacing opcode 0x6e at 0x0045
I/chromium( 4200): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  965): battery changed pluggedType: 2
,D/dalvikvm( 4200): GC_CONCURRENT freed 2777K, 12% free 21876K/24832K, paused 2ms+1ms, total 40ms
D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4200): GC_FOR_ALLOC freed 230K, 12% free 21864K/24832K, paused 22ms, total 22ms
D/dalvikvm( 4200): GC_FOR_ALLOC freed 194K, 12% free 21889K/24832K, paused 21ms, total 21ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 23.687MB for 144892-byte allocation
D/dalvikvm( 4200): GC_FOR_ALLOC freed 257K, 13% free 21936K/24976K, paused 37ms, total 37ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 23.802MB for 217334-byte allocation
D/dalvikvm( 4200): GC_FOR_ALLOC freed 369K, 13% free 22010K/25192K, paused 36ms, total 36ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 23.978MB for 325996-byte allocation
D/dalvikvm( 4200): GC_FOR_ALLOC freed 570K, 14% free 22132K/25512K, paused 33ms, total 33ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 24.252MB for 488990-byte allocation
D/dalvikvm( 4200): GC_FOR_ALLOC freed 868K, 15% free 22308K/25992K, paused 28ms, total 29ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 24.659MB for 733480-byte allocation
D/dalvikvm( 4200): GC_FOR_ALLOC freed 1289K, 16% free 22566K/26712K, paused 26ms, total 27ms
D/dalvikvm( 4200): GC_CONCURRENT freed 1676K, 15% free 22937K/26712K, paused 0ms+2ms, total 27ms
D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4200): GC_FOR_ALLOC freed 355K, 15% free 22917K/26712K, paused 23ms, total 23ms
I/dalvikvm-heap( 4200): Grow heap (frag case) to 26.127MB for 1650320-byte allocation
,D/dalvikvm( 4200): GC_CONCURRENT freed 1762K, 18% free 23469K/28324K, paused 2ms+2ms, total 29ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 4200): GC_FOR_ALLOC freed 1324K, 17% free 23542K/28324K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 27.524MB for 2475476-byte allocation
,D/dalvikvm( 4200): GC_CONCURRENT freed 2061K, 22% free 24251K/30744K, paused 3ms+2ms, total 47ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/dalvikvm( 4200): GC_CONCURRENT freed 2367K, 21% free 24479K/30744K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4200): GC_FOR_ALLOC freed 363K, 21% free 24359K/30744K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 29.502MB for 3713210-byte allocation
,D/dalvikvm( 4200): GC_CONCURRENT freed 2746K, 26% free 25524K/34372K, paused 1ms+2ms, total 40ms
,D/dalvikvm( 4200): GC_FOR_ALLOC freed 602K, 26% free 25467K/34372K, paused 22ms, total 24ms
,W/jxcore-log( 4200): Initializing JXcore engine
,W/jxcore-log( 4200): JXcore engine is ready
,D/dalvikvm( 4200): GC_CONCURRENT freed 354K, 19% free 28114K/34372K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 4200): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4200): Starting JXcore engine
,W/jxcore-log( 4200): Platform android
W/jxcore-log( 4200): 
,W/jxcore-log( 4200): Process ARCH arm
W/jxcore-log( 4200): 
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.456131 Y: -0.390518 Z: 9.797012 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456131 .y:-0.390518 .z:9.797012
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.462372 Y: -0.398163 Z: 9.777130 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462372 .y:-0.398163 .z:9.777130
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/jxcore-log( 4200): JXcore Cordova bridge is ready!
I/jxcore-log( 4200): 
,W/jxcore-log( 4200): JXcore engine is started
,I/chromium( 4200): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4200): Skipped 161 frames!  The application may be doing too much work on its main thread.
,I/GAV2    ( 4119): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/jxcore-log( 4200): Toggling radios to true
I/jxcore-log( 4200): 
D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c4fa10:true
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  965): Message: 1
,D/BluetoothManagerService(  965): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  965): New client listening to asynchronous messages
D/WifiService(  965): setWifiEnabled: true pid=4200, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  965): setting operational mode to 1
D/WifiStateMachine(  965): handleMessage: E msg.what=131083
,D/WifiStateMachine(  965): processMsg: InitialState
,I/jxcore-log( 4200): Radios toggled
I/jxcore-log( 4200): 
E/WifiHW  (  965): Wifi MAC Address = 34:fc:ef:de:0a:e2
,E/WifiHW  (  965): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  965): ": cur_etheraddr=34:fc:ef:de:0a:e2
,D/SoftapController(  264): Softap fwReload - Ok
D/WifiService(  965): disconnect pid=4200, uid=10304
,D/WifiService(  965): reconnect pid=4200, uid=10304
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring down wlan0
I/jxcore-log( 4200): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4200): 
I/jxcore-log( 4200): Perf Test app loaded loaded
I/jxcore-log( 4200): 
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/WifiStateMachine(  965): setWifiState: enabling
E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
I/jxcore-log( 4200): check test folder
I/jxcore-log( 4200): 
,I/jxcore-log( 4200): found test : ./testFindPeers.js
I/jxcore-log( 4200): 
,V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): Supplicant start successful
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/WifiMonitor(  965): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  965): connecting to supplicant
D/wpa_supplicant( 4256): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4256): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4256): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4256): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4256): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4256): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4256): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4256): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4256): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4256): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4256): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4256): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4256): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4256): disable_scan_offload=1
D/wpa_supplicant( 4256): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4256): update_config=1
D/wpa_supplicant( 4256): device_name='g2_open_com'
D/wpa_supplicant( 4256): manufacturer='LGE'
D/wpa_supplicant( 4256): model_name='LG-D802'
D/wpa_supplicant( 4256): model_number='LG-D802'
D/wpa_supplicant( 4256): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4256): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4256): p2p_disabled=1
D/wpa_supplicant( 4256): p2p_no_group_iface=1
D/wpa_supplicant( 4256): Line: 15 - start of a new network block
D/wpa_supplicant( 4256): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4256): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4256): key_mgmt: 0x2
,D/wpa_supplicant( 4256): priority=1 (0x1)
,D/BluetoothAdapterService( 1216): REFCOUNT: CREATED. INSTANCE_COUNT1
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4257 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [2]
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/BluetoothAdapterService(1115939424)( 1216): onCreate
,I/jxcore-log( 4200): found test : ./testSendData.js
I/jxcore-log( 4200): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c5b588:true
,D/BluetoothAdapterState( 1216): make
I/bluedroid( 1216): init ready=0
,D/bt-btif ( 1216): in initialized:0
D/bt-btif ( 1216): root, p->name:Bluedroid, child/value:0x6060d108, bytes:160
I/BluetoothAdapterState( 1216): Entering OffState
,D/bt-btif ( 1216): p->used:0, type:0, p->flag:0
,I/bte_conf( 1216): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/BT_PROF ( 1216): set profile trace flags 0x0
,D/BTIF_CORE( 1216): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1216):  [BTUI] Load_abtddress
D/bt-btif ( 1216): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1216): Got prior random BDA 34:FC:EF:9D:93:0B
I/bluedroid( 1216): get_profile_interface socket
I/bt-btif ( 1216): btif_get_adapter_property 2
,I/bt-btif ( 1216): btif_get_adapter_property 1
D/BluetoothAdapterService(1115939424)( 1216): onBind
D/wpa_supplicant( 4256): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4256): Priority group 1
D/wpa_supplicant( 4256):    id=0 ssid='NG700'
,D/wpa_supplicant( 4256): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/btif_config_util( 1216): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  965): Message: 40
,D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/wpa_supplicant( 4256): disable_scan_offload=1
D/wpa_supplicant( 4256): Priority group 1
,D/wpa_supplicant( 4256):    id=0 ssid='NG700'
I/wpa_supplicant( 4256): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4256): nl80211: RFKILL status not available
D/wpa_supplicant( 4256): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4256): nl80211: TDLS supported
D/wpa_supplicant( 4256): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4256): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4256): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4256): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4256): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4256): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4256): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
,D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
,D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 11
,I/GKI_LINUX( 1216): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1216): btif task starting
D/bt-btif ( 1216): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1216): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1216): execute storage request event : 3
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:2 
,I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1216): execute storage request event : 3
,D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:1 
,D/bt-btif ( 1216): in, bd addr:, prop type:1, len:512
,I/bluedroid( 1216): config_hci_snoop_log
D/lge_bdaddr_loader( 4277): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 4277): [BTUI] bluetooth_load_bdaddress
D/BluetoothManagerService(  965): Calling onBluetoothServiceUp callbacks
D/lge_bdaddr_loader( 4277): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,D/BluetoothManagerService(  965): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/dalvikvm( 1216): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothAdapterService(1115939424)( 1216): Enable called with quiet mode status =  false
D/BluetoothAdapterState( 1216): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,I/BluetoothAdapterState( 1216): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1216): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  965): Message: 60
,D/BluetoothAdapterService(1115939424)( 1216): processStart()
,D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1115939424)( 1216): processStart(): Make Bond State Machine
,D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothBondStateMachine( 1216): make
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BluetoothAdapterService( 1216): setAdapterService(): set to: null
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,D/LGBluetoothServiceAdapter( 1216): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
D/LGBluetoothServiceAdapter( 1216): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1216): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1216): StableState(): Entering Off State
,I/ConfigService( 1535): onDestroy
E/lge_bdaddr_loader( 4277): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4277): [BTUI] bdaddr_loader ::: END
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
,W/BluetoothAdapterService( 1216): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
,D/BluetoothHeadset(  965): Proxy object connected
,D/BluetoothHeadset( 1449): Proxy object connected
D/BluetoothHeadset( 1449): Proxy object connected
D/BrcmHeadsetService( 1216): Received start request. Starting profile...
D/BluetoothHeadset( 1449): Proxy object connected
,I/Brcm_BluetoothHeadsetServiceJni( 1216): classInitNative: succeeds
D/HeadsetStateMachine( 1216): make
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
,W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.a2dp.A2dpService
D/HyLog   ( 4257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4257): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
,I/LGBluetoothHeadsetServiceJni( 1216): classInitNative: succeeds
,D/LGBluetoothHfpAdapter( 1216): Version 1.5
,W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.hid.HidService
,I/bluedroid( 1216): get_profile_interface handsfree
I/bt-btif ( 1216): btif_hf_get_interface
,I/bt-btif ( 1216): init
,D/bt-btif ( 1216): btif_enable_service: current services:0x40
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
V/AudioPolicyService(  271): getOutput()
V/AudioPolicyManagerBase(  271): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  271): getOutput() returns output 2
,V/AudioSystem( 1216): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.hdp.HealthService
V/AudioFlinger(  271): registerClient() client 0xb8f4cd58, pid 1216
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  271): thread 0xb2729008 type 0 TID 930 waking up
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
,V/AudioFlinger(  271): thread 0xb25be008 type 0 TID 1002 waking up
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
,V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb2729008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem(  271): ioConfigChanged() opening already existing output! 2
I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_properties_cb
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1449): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1449): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1599): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb25be008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 3
,V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1449): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1449): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1599): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  965): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1599): ioConfigChanged() event 0, ioHandle 3
,V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1599): ioConfigChanged() opening already existing output! 3
V/AudioSystem(  965): ioConfigChanged() opening already existing output! 3
,D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
V/AudioSystem( 1216): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1216): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
V/AudioSystem( 1216): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1216): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
,V/AudioSystem( 1216): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1216): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1216): streamType 8
V/AudioTrack( 1216): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
I/chromium( 4200): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/AudioPolicyService(  271): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  271): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1216): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,D/HeadsetStateMachine( 1216): Enter Disconnected: -2
,D/HeadsetPhoneState( 1216): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1216): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1216): [BTUI] change sampling rate to 8000 when device is disconnected
,E/AudioSystem( 1216): AudioSystem::setParameters()...keyValue bt_samplerate=8000
D/PCSuite ( 4257): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1216
V/SRS_Proc(  271): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  271): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.pan.PanService
,D/BluetoothA2dp(  965): Proxy object connected
,D/A2dpService( 1216): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1216): classInitNative: succeeds
,D/A2dpStateMachine( 1216): make
I/bluedroid( 1216): get_profile_interface a2dp
,E/BluetoothAdapterService( 1216): File transfer profiels supported!!
I/bt-btif ( 1216): btif_av_get_interface
I/bt-btif ( 1216): init
I/bt-btif ( 1216): ## A2DP START MEDIA TASK ##
,I/ActivityManager(  965): Killing 3052:android.process.media/u0a23 (adj 15): empty #17
D/LGBluetoothXmlHandler( 2517): dvice configuraion start
I/GKI_LINUX( 1216): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1216): UIPC_Init
I/bt-btif ( 1216): ### uipc_main_init ###
W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService( 1216): File transfer profiels supported!!
D/LGBluetoothXmlHandler( 2517): startDocument!
D/bt-btif ( 1216): UIPC_Open : ch_id 0, p_cback 60ab0b25
I/bt-btif ( 1216): SETUP CHANNEL SERVER 0
I/bt-btif ( 1216): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1216): created socket fd 70
D/LGBluetoothXmlHandler( 2517): startElement - elet = Device
D/LGBluetoothXmlHandler( 2517): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2517): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2517): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2517): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2517): endDocument!
I/bt-btif ( 1216): ADD SERVER FD TO ACTIVE SET 70
I/bt-btif ( 1216): UIPC SEND WAKE UP
I/bt-btif ( 1216): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1216): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1216): btif_enable_service: current services:0x48
D/bt-btif ( 1216): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1216): ## ON A2DP IDLE ##
D/bt-btif ( 1216): UIPC_Close : ch_id 1
I/LGBluetoothA2dpServiceJni( 1216): classInitNative: succeeds
I/bt-btif ( 1216): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpAdapter( 1216): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/BluetoothAVRCP1.3ServiceJni( 1216): classInitNativeAVRCP
V/Avrcp   ( 1216): make
D/A2dpStateMachine( 1216): Enter Disconnected: -2
W/BluetoothAdapterService( 1216): Starting service com.android.bluetooth.gatt.GattService
E/BluetoothAdapterService( 1216): File transfer profiels supported!!
W/BluetoothAdapterService( 1216): Starting service com.broadcom.bt.service.sap.SapService
D/LGBluetoothAvrcpManager( 1216): [BTUI] initAvcrpManager
E/BluetoothAdapterService( 1216): File transfer profiels supported!!
W/BluetoothAdapterService( 1216): Starting service com.broadcom.bt.service.ftp.FTPService
D/LGBluetoothAvrcpManager( 1216): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1216): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1216): initNativeAVRCP
I/bluedroid( 1216): get_profile_interface avrcp
I/bt-btif ( 1216): btif_rc_get_interface
I/bt-btif ( 1216): ## init ##
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,D/HeadsetStateMachine( 1216): Proxy object connected
,I/BluetoothHidServiceJni( 1216): classInitNative: succeeds
D/HidService( 1216): Received start request. Starting profile...
I/bluedroid( 1216): get_profile_interface hidhost
I/bt-btif ( 1216): btif_hh_get_interface
I/bt-btif ( 1216): init
,D/bt-btif ( 1216): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,I/BluetoothHealthServiceJni( 1216): classInitNative: succeeds
,D/HealthService( 1216): Received start request. Starting profile...
I/bluedroid( 1216): get_profile_interface health
I/bt-btif ( 1216): btif_hl_get_interface
I/bt-btif ( 1216): init
D/bt-btif ( 1216): Process name (droid.bluetooth)
,D/bt-btif ( 1216): btif_hl_soc_thread_init
D/bt-btif ( 1216): create_thread: entered
D/bt-btif ( 1216): create_thread: thread created successfully
D/bt-btif ( 1216): entered btif_hl_select_thread
D/bt-btif ( 1216): btif_hl_select_wakeup_init
D/bt-btif ( 1216): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1216): max_s=79 
D/bt-btif ( 1216): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1216): classInitNative: succeeds
,D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/HeadsetPhoneState( 1216): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1216): Disconnected process message: 11
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BluetoothPanServiceJni( 1216): classInitNative(L105): succeeds
D/dalvikvm( 1216): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BluetoothPan(  965): BluetoothPAN Proxy object connected
D/PanService( 1216): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1216): initializeNative(L110): pan
I/bluedroid( 1216): get_profile_interface pan
D/bt-btif ( 1216): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  965): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
I/BluetoothAdapterState( 1216): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
I/LGBluetoothMapAdapter( 1216): [BTUI] getInstance : create [LGBluetoothMapAdapter]
,V/BluetoothMapService( 1216): BluetoothMapBinder()
D/BluetoothMapService( 1216): Received start request. Starting profile...
,D/BluetoothMapService( 1216): start()
,D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,V/BluetoothPbapReceiver( 1216): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1216): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1216): ***********state = 11
,I/BtGatt.JNI( 1216): classInitNative(L685): classInitNative: Success!
,D/BtGatt.DebugUtils( 1216): handleDebugAction() action=null
D/BtGatt.GattService( 1216): Received start request. Starting profile...
D/BtGatt.GattService( 1216): start()
D/BluetoothPermissionRequest( 2517): onReceive
I/bluedroid( 1216): get_profile_interface gatt
,D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c688f8:true
,I/BluetoothSAPServiceJni( 1216): classInitNative(L170): succeeds
D/SapService( 1216): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1216): initializeNative(L175): sap
I/bluedroid( 1216): get_profile_interface sap
I/bt-btif ( 1216): btif_sc_get_interface
I/bt-btif ( 1216): init
D/bt-btif ( 1216): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1216): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1216): [BTUI] Create LGBluetoothSapManager Instance
,D/LGBluetoothResetSettingReceiver( 2517): [BTUI] Loading JNI Library
,D/LGBluetoothSapManager( 1216): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1449): [BTUI] SAP_ENABLE_EVT
,E/BluetoothSettings_JNI( 2517): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/LGBluetoothResetSettingReceiver( 2517): return without doing reset settings.
,D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,V/BluetoothFTPServiceJni( 1216): classInitNative
I/BluetoothFTPServiceJni( 1216): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
,D/BluetoothFTPService( 1216): BluetoothFtpBinder()
D/**BluetoothFTPService( 1216): Received start request. Starting profile...
,V/BluetoothFTPService( 1216): FTP-Server Service start
D/BluetoothFTPServiceJni( 1216): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1216): get_profile_interface ftp
I/bt-btif ( 1216): btif_fts_get_interface
I/bt-btif ( 1216): init
D/bt-btif ( 1216): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1216): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
,V/BluetoothMapService( 1216): Handler(): got msg=1
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
,D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1216): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1115939424)( 1216): Message: 1
,D/BluetoothAdapterService(1115939424)( 1216): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1216): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1216): All profile services started.
D/BluetoothAdapterState( 1216): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1216): enable 1
I/bt-btif ( 1216): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1216): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/GKI_LINUX( 1216): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 1216): init
I/bt_vendor( 1216): init
I/bt_vnd_conf( 1216): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1216): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1216): libbt-hci init returns 0
,I/bt_hci_bdroid( 1216): bt_hc_worker_thread started
,I/ActivityManager(  965): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4304 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4304): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 3826:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/AuthorizationBluetoothService( 1535): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt_userial_vendor( 1216): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1216): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1216): device fd = 84 open
,D/bt_hwcfg( 1216): Chipset BCM4335A0
,D/bt_hwcfg( 1216): Target name = [BCM4335A0]
D/bt_hwcfg( 1216): Target name = [BCM4335]
I/bt_hwcfg( 1216): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1216): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1216): bt vendor lib: set UART baud 4000000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4256): netlink: Operstate: linkmode=1, operstate=5
,D/wpa_supplicant( 4256): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4256): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4256): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4256): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4256): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4256): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4256): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4256): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4256): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  965): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  965): sendTetherStateChangedBroadcast 1, 0, 0
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2517): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2517): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2517): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/Config  ( 2517): getOperator() : OPEN
,D/UsbSettingsControl( 2517): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2517): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsReceiver( 2517): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2517): [AUTORUN] setTetherStatus() : status=false
,D/wpa_supplicant( 4256): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4256): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4256): wlan0: Setting scan request: 0 sec 100000 usec
,I/bt_hwcfg( 1216): Releasing 4335 AXI BRIDGE lock
D/wpa_supplicant( 4256): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4256): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4256): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4256): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4256): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4256): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4256): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): Using existing control interface directory.
I/wpa_supplicant( 4256): 0xb7b98cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4256): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4256): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4256): lge_eap_carrier_var_init
D/wpa_supplicant( 4256): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4256): wlan0: Added interface wlan0
D/wpa_supplicant( 4256): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4256): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4256): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4256): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4256): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4256): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4256): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4256): update_config=1
D/wpa_supplicant( 4256): device_name='Thali Test's G2'
,D/wpa_supplicant( 4256): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4256): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4256): persistent_reconnect=1
,D/wpa_supplicant( 4256): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4256): update_config=1
D/wpa_supplicant( 4256): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4256): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4256): eapol_version=1
D/wpa_supplicant( 4256): ap_scan=1
,D/wpa_supplicant( 4256): fast_reauth=1
D/wpa_supplicant( 4256): p2p_disabled=0
D/wpa_supplicant( 4256): p2p_no_group_iface=0
I/wpa_supplicant( 4256): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4256): nl80211: RFKILL status not available
D/wpa_supplicant( 4256): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4256): nl80211: TDLS supported
D/wpa_supplicant( 4256): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4256): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4256): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4256): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4256): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4256): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7ba8c28
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4256): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4256): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4256): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4256): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4256): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4256): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4256): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4256): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4256): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4256): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4256): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4256): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4256): nl80211: Flush PMKIDs
D/wpa_supplicant( 4256): p2p0: State: DISCONNECTED -> INACTIVE
D/wpa_supplicant( 4256): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4256): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4256): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4256): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4256): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4256): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4256): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): Using existing control interface directory.
I/wpa_supplicant( 4256): 0xb7ba8098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4256): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4256): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4256): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4256): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4256): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4256): [ITEC] USE NON-INET
I/wpa_supplicant( 4256): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4256): HY wiflus comm channel initialized
D/wpa_supplicant( 4256): P2P: Own listen channel: 11
I/wpa_supplicant( 4256): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4256): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4256): P2P: Add operating class 81
D/wpa_supplicant( 4256): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4256): P2P: Add operating class 115
D/wpa_supplicant( 4256): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4256): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4256): p2p0: Added interface p2p0
D/wpa_supplicant( 4256): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4256): random: Got 18/20 bytes from /dev/random
D/wpa_supplicant( 4256): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 4256): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4256): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/WifiStateMachine(  965): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: InitialState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131144
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): deferMessage: msg=131144
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): deferMessage: msg=131085
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131149
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): setSuspendOptimizations: 2 true
D/WifiStateMachine(  965): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131101
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147457
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): Supplicant connection established
D/WifiNative-wlan0(  965): doString: DRIVER MACADDR
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER MACADDR'
D/WifiNative-wlan0(  965):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): setWifiState: enabled
D/WifiOffDelayIfNotUsed(  965): setPowerSaveActivated(false)
D/WifiActivationWhileCharging(  965): unregister : we don't need to unregister
E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdService( 1156): Waiting for WifiP2p enabling
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiConfigStore(  965): Loading config and enabling all networks
D/WifiNative-wlan0(  965): doString: LIST_NETWORKS
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4256): wlan0: Control interface command 'LIST_NETWORKS'
D/WifiNative-wlan0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  965): 0	NG700	any	
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [3]
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'bssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 scan_ssid
I/WifiServiceExtension(  965): batteryPsActivateMsgHandler : state:0 event:3
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/PCSuite ( 4257): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4256): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  965): ***WAPI : not WAPI
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4256): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4256): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4256): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  965): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  965): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4256): device_name='g2_open_com'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4256): manufacturer='LGE'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4256): model_name='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4256): model_number='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
D/wpa_supplicant( 4256): serial_number='022678fb504e29b0'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4256): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  965): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4256): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4256): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedState
W/Settings( 3300): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/LGDMClient( 2810): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setDetailed state, old =IDLE and new state=DISCONNECTED
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 3
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4256): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4256): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
D/LGDMClient( 2810): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/WifiNative-wlan0(  965):    returned wpa_state=DISCONNECTED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleScreenStateChanged: true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4256): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4329 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  965): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131144
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up p2p0
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132106
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4256): nWIFIDualbandAPConnection: 1
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/WifiMonitor(  965): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132096
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4256): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4256): disconnect_rssi_lvl: -100
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): P2pEnablingState
D/WifiP2pService(  965): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2p socket connection successful
D/WifiP2pService(  965): P2pEnabledState
D/WifiP2pService(  965): sending p2p connection changed broadcast
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiStateMachine(  965): handleMessage: E msg.what=143371
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiNative-p2p0(  965): doBoolean: SET persistent_reconnect 1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4256): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4256): persistent_reconnect=1
D/wpa_supplicant( 4256): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4256): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4256): device_name='Thali Test's G2'
D/WifiNative-p2p0(  965):    returned true
D/WifiServiceExtension(  965): postfix byte check : 15
D/WifiNative-p2p0(  965): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4256): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4256): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4256): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET device_type 10-0050F204-5
D/WifiP2pService(  965): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  965): before postfix = Thali Test's G2
D/WifiP2pService(  965): after postfix = Thali Test's G2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4256): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4256): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4256): wlan0: nl80211: scan request
D/wpa_supplicant( 4256): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4256): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4256): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4256): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4256): nl80211: Event message available
D/wpa_supplicant( 4256): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4256): wlan0: nl80211: Scan trigger
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4256): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4256): Single channel concurrency preference: sta
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: STATUS
D/wpa_supplicant( 4256): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  965):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): p2p_state=IDLE
D/WifiNative-p2p0(  965): wifi_display=1
D/WifiNative-p2p0(  965): ifname=p2p0
D/WifiNative-p2p0(  965): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): ifname=wlan0
D/WifiNative-p2p0(  965): address=34:fc:ef:de:0a:e2
D/HyLog   ( 4329): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4329): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4329): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-p2p0(  965): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4256): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4256): P2P: Stopping find
D/wpa_supplicant( 4256): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4256): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4256): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  965): DeviceAddress: 36:fc:ef:de:0a:e2
I/bt_hwcfg( 1216): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1216): Settlement delay -- 100 ms
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4256): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: LIST_NETWORKS
I/WfdStateTracker( 1156): handleP2pThisDeviceChanged
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4256): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  965): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4256): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4256): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/LGDMSGCM( 4329): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4343 uid=10101 gids={50101, 1028, 1015, 3003}
D/wpa_supplicant( 4256): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
,D/wpa_supplicant( 4256): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WifiNative-p2p0(  965):    returned true
,E/WifiServiceExtension(  965): No p2p device connected
D/WifiP2pService(  965): sending p2p persistent groups changed broadcast
D/WifiP2pService(  965): InactiveState
D/WifiP2pService(  965): InactiveState{ when=-28ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-29ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): DefaultState{ when=-29ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=-29ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-29ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): DefaultState{ when=-29ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  965): Killing 3244:com.android.mms/u0a35 (adj 15): empty #17
,D/HyLog   ( 4343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4343): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4343): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  965): remove 430826a8
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  965): No listener is left
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/Wireless_Storage( 4343): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 4084): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4084): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  965): Killing 3300:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/bt_hwcfg( 1216): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1216): Setting local bd addr to 34:FC:EF:9D:93:0B
I/bt_hwcfg( 1216): vendor lib fwcfg completed
I/bt-btif ( 1216): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1216): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1216): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1216): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1216): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1216): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1216): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1216): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1216): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1216): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1216): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1216): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1216): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1216): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1216): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1216): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1216): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1216): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1216): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1216): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1216): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1216): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1216): bta_dm_sm_execute event:0x0
I/bt-btif ( 1216): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1216): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1216): bta_sys_sm_execute state:1, event:0x1
I/bt-btif ( 1216): bta_sys_hw_evt_enabled for 0
,D/bt-btif ( 1216):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1216): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1216):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1216):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1216): ##################################
D/bt-btif ( 1216): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1216): ##################################
D/bt-btif ( 1216): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1216): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b054c5 
I/bt-smp  ( 1216): SMP_Register state=0
E/bt-btm  ( 1216): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b054c5 
D/bt-btif ( 1216): bta_gattc_register state 0
D/bt-btif ( 1216): bta_gattc_enable
I/bt-att  ( 1216): GATT_Register
D/bt-att  ( 1216): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1216): allocated gatt_if=3
D/bt-btif ( 1216): bta_dm_gattc_callback event = 0
D/bt-btif ( 1216): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1216): GATT_StartIf gatt_if=3
D/bt-att  ( 1216): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1216): gatt_find_the_connected_bda found=0 found_idx=7
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1216): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1216): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1216): bta_dm_sm_execute event:0x2
D/bt-btif ( 1216): BTA is generating EIR
D/bt-sdp  ( 1216): getAccess buffer->st_uid:1000rds:3
D/bt-btif ( 1216): getAccess buffer->st_uid:1000 buffer->st_gid:1028
I/bt-btif ( 1216): Adding UUID=0x110C into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1216): nsc_mask: 0x6
D/bt-btif ( 1216): bta_av_co_audio_init
D/bt-btif ( 1216): bta_av_co_audio_init: 0
D/bt-btif ( 1216): audio[0] av_handle: 1 codec_type: 0
,D/bt-btif ( 1216): bta_av_co_audio_init
I/bt-btif ( 1216): bta_av_co_audio_init: 1
D/bt-btif ( 1216): bta_av_co_audio_init: 1
D/bt-btif ( 1216): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1216): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1216): A2D_AddRecord uuid: 110a
I/bt-btif ( 1216): Adding UUID=0x110A into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1216): rc_acp_handle:0 idx:1
D/bt-btif ( 1216): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1216): reg_audio: 0x1
D/bt-btif ( 1216): bta_ag_scb_alloc 1
I/bt-btif ( 1216): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1216): bta_ag_add_record uuid: 1112
I/bt-btif ( 1216): Adding UUID=0x1112 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1216): bta_ag_add_record uuid: 111f
I/bt-btif ( 1216): Adding UUID=0x111F into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1216): bta_fts_api_enable srm:1
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1216): Adding UUID=0x1106 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1216): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1216): bta_fts_ci_resume status:1
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1216): Adding UUID=0x112D into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1216): bte_sap_evt: event=0
,E/bt-btif ( 1216): Calling BTA_HhEnable,
D/bt-btif ( 1216): bta_gattc_register state 2
I/bt-att  ( 1216): GATT_Register
D/bt-att  ( 1216): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1216): allocated gatt_if=4
D/bt-btif ( 1216): bta_hh_gattc_callback event = 0
I/bt-att  ( 1216): GATT_StartIf gatt_if=4
D/bt-att  ( 1216): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1216): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1216): in add:1
D/bt-btif ( 1216): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1216): Remote device:f8:95:c7:87:3c:51, size:18
,D/bt-btif ( 1216): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1216): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1216): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1216): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1216): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1216): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1216): Remote device:b4:ce:f6:ab:a4:6a, size:18
,D/bt-btif ( 1216): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1216): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1216): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1216): Remote device:7c:f9:0e:51:18:22, size:18
,D/bt-btif ( 1216): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1216): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1216): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1216): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1216): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1216): Remote device:f8:95:c7:87:85:54, size:18
I/bt-btif ( 1216): bta_dm_sm_execute event:0x9
D/bt-btif ( 1216): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1216): Remote device:e0:db:10:14:e2:c0, size:18
,I/bt-btif ( 1216): bta_dm_sm_execute event:0x9
D/bt-btif ( 1216): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1216): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1216): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1216): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1216): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1216): bta_dm_sm_execute event:0x9
D/bt-btif ( 1216): Remote device:, size:128
E/bt-btif ( 1216): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1216): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1216): out
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1216): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1216): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1216): in, bd addr:, prop type:16, len:4,
E/bt-btif ( 1216): Unknow prop type:16
I/bt-btif ( 1216): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1216): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1216): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1216): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1216): btif_storage_get_adapter_property property->type:3 devicemode 0
I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1216): Property change not handled in Java land:16
,I/bt-btif ( 1216): btif_storage_load_bonded_devices: 3 bonded devices found
D/bt-btif ( 1216): in, bd addr:f8:95:c7:87:85:54, prop type:1, len:249
D/bt-btif ( 1216): in, bd addr:f8:95:c7:87:85:54, prop type:10, len:249
D/bt-btif ( 1216): in, bd addr:f8:95:c7:87:85:54, prop type:4, len:4
D/bt-btif ( 1216): in, bd addr:f8:95:c7:87:85:54, prop type:5, len:4
D/bt-btif ( 1216): in, bd addr:f8:95:c7:87:85:54, prop type:3, len:512
,I/bt-btif ( 1216): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1216): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1216): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1216): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1216): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1216): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1216): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1216): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
D/bt-btif ( 1216): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
,I/bt-btif ( 1216): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1216): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1216): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1216): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1216): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1216): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1216): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1216): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1216): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1216): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1216): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1216): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1216): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1216): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1216): hw_sco_config...
,E/bt_hwcfg( 1216): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1216): HC lib lpm enable=1 return 0
I/bt-btif ( 1216): BTA_BrcmInit
E/bt-gki  ( 1216): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
,D/IOP_DB_BT( 1216): db_open: file /etc/bluetooth/iop_bt.db
,I/bt-btif ( 1216): HC lpm_result_cb 1
D/IOP_DB_BT( 1216): db_open: db_open : handle 1623140908l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1216): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1216): db_query: result 1
I/        ( 1216): iop_db_open: iop_db_open status 0
D/bt-btif ( 1216): btsock initializing...
D/bt-btif ( 1216): in initialized:1
D/bt-btif ( 1216): ts[7].used:1
D/bt-btif ( 1216): ts[6].used:0
D/bt-btif ( 1216): alloc_thread_slot ret:6
D/bt-btif ( 1216): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1216): h:6, thread id:1641149360
I/bt-btif ( 1216): BTA_JvEnable
D/bt-btif ( 1216): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1216): unhandled event:0, slot id:0
D/bt-btif ( 1216): btsock successfully initialized
D/bt-btif ( 1216): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1216): Enabling PAN....
I/bt-btif ( 1216): bta_pan_co_init
D/bt-btif ( 1216): local_role:3
D/bt-btif ( 1216): btpan_role:0x3
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1216): Adding UUID=0x1116 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1216): Adding UUID=0x1115 into EIR
I/bte_conf( 1216): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1216): Adding UUID=0x1116 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1216): Removing UUID=0x1117 from EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1216): Adding UUID=0x1115 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1216): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bt-btif ( 1216): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1216): Adding UUID=0x1200 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1216): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1216): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1216): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1216): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1216): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1216): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1216): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1216): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1216): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1216): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1216): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1216): File Transfer: Enable Complete
I/bt-btif ( 1216): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1216): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1216): onFtpServerEnabled: /storage
D/bt-btif ( 1216): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1216): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1216): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1216): btif_hh_upstreams_evt--Loading added devices
D/BluetoothAdapterState( 1216): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1216): ScanMode =  20
D/BluetoothAdapterProperties( 1216): State =  11
D/BluetoothAdapterProperties( 1216): mDiscoverableTimeout =  120
I/bt-btif ( 1216): btif_set_adapter_property type: 7, len 4, 0x428ae330
I/bt-btif ( 1216): set property scan mode : 1
I/bt-btif ( 1216): bta_dm_sm_execute event:0x3
I/bt-btif ( 1216): btif_in_storage_request_copy_cb
I/bt-btif ( 1216): btif_set_adapter_property type: 9, len 4, 0x428ae388
I/bt-btif ( 1216): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1216): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1216): Broadcasting updateAdapterState() to 1 receivers.
D/bt-btif ( 1216): btif_in_storage_request_copy_cb
D/BluetoothManagerService(  965): Message: 60
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  965): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  965): onBluetoothStateChange(on) call bindService
D/bt-btif ( 1216): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1216): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1216): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1216): Remote device:14:b4:84:21:3b:49, size:18
,D/bt-btif ( 1216): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1216): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1216): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1216): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1216): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1216): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1216): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1216): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1216): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1216): Remote device:50:2e:6c:ac:21:50, size:18
V/BluetoothAdapterService( 1216): startPbapService
D/bt-btif ( 1216): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1216): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1216): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1216): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1216): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1216): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1216): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1216): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1216): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1216): Remote device:58:2a:f7:ed:96:be, size:18
,D/bt-btif ( 1216): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1216): Remote device:, size:18
E/bt-btif ( 1216): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1216): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1216): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1216): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1216): execute storage request event : 2
I/bt-btif ( 1216): type: 7, len 4, 0x6061c032
D/bt-btif ( 1216): in, bd addr:, prop type:7, len:4
,D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
D/BluetoothHeadset(  965): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  965): onBluetoothStateChange: up=true
I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1216): Entering On State
,D/LGBluetoothServiceAdapter( 1216): [BTUI] OnState
,D/LGBluetoothServiceAdapter( 1216): [BTUI]         global_name: Thali Test's G2
I/bt-btif ( 1216): execute storage request event : 2
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 11 -> 12
I/bt-btif ( 1216): type: 9, len 4, 0x6061c07e
D/bt-btif ( 1216): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1216): HAL bt_hal_cbacks->adapter_properties_cb
,D/LGBluetoothServiceAdapter( 1216): [BTUI]         local_name: Thali Test's G2
,D/BluetoothAdapterService(1115939424)( 1216): Quiet mode Enabled = false
D/BluetoothAdapterService(1115939424)( 1216): Initiate auto connection on BT on...
,D/BluetoothAdapterService( 1216): [BTUI] autoConnect() : not allowed
,W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1156): Message: 1
D/LGBluetoothAPIService( 1156): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(1115939424)( 1216): Get Bonded Devices being called
I/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIService Binding Success
D/bt_h4   ( 1216): vendor lib postload completed
I/bt-btif ( 1216): HC postload_cb 0
D/BluetoothAdapterService( 1216): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4283e260
V/BluetoothPbapService( 1216): Pbap Service onCreate
V/BluetoothPbapService( 1216): Starting PBAP service
D/LGBluetoothPbapAdapter( 1216): [BTUI] getInstance : create
V/BluetoothPbapService( 1216): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1216): state: 12
D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  965): Message: 40
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1216): onReceive
D/BluetoothMapService( 1216): STATE_ON
D/LGBluetoothAPIServer( 1216): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1216): [BTUI] onBind()
D/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1156): Message: 100
D/LGBluetoothAPIService( 1156): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1216): Handler(): got msg=1
V/BluetoothPbapService( 1216): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1216): Pbap Service initSocket
V/BluetoothMapService( 1216): Handler(): got msg=1
,D/BluetoothMapService( 1216): Map Service startRfcommSocketListener
,D/BluetoothMapService( 1216): Map Service initSocket
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1216): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 1216): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
E/BluetoothServiceJni( 1216): SOCK FLAG = 1 ***********************
D/bt-btif ( 1216): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1216): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1216): BTA_JvCreateRecordByUser
D/bt-btif ( 1216): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1216): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1216): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1216): Adding UUID=0x112F into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1216): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1216): BTA_JvRfcommStartServer
D/bt-btif ( 1216): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1216): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1216): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1216): Succeed to create listening socket 
V/BluetoothPbapService( 1216): Accepting socket connection...
E/BluetoothServiceJni( 1216): SOCK FLAG = 1 ***********************
D/bt-btif ( 1216): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1216): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1216): BTA_JvCreateRecordByUser
D/bt-btif ( 1216): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1216): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1216): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1216): Adding UUID=0x1132 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1216): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1216): BTA_JvRfcommStartServer
D/bt-btif ( 1216): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
,D/bt-btif ( 1216): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1216): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1216): Succeed to create listening socket 
D/BluetoothMapService( 1216): Accepting socket connection...
V/BluetoothPbapReceiver( 1216): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1216): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1216): ***********state = 12
,D/LocalBluetoothProfileManager( 2517): Adding local A2DP profile
,D/BluetoothManagerService(  965): Message: 30
,D/LocalBluetoothProfileManager( 2517): Adding local HEADSET profile
,D/BluetoothManagerService(  965): Message: 30
,D/BluetoothManagerService(  965): Message: 30
W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
,D/BluetoothManagerService(  965): Message: 30
,W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
D/LocalBluetoothProfileManager( 2517): Adding local MAP profile
D/BluetoothMap( 2517): Create BluetoothMap proxy object
,D/BluetoothManagerService(  965): Message: 30
,D/BluetoothManagerService(  965): Message: 30
,V/BluetoothPbapService( 1216): Pbap Service onBind
,D/LocalBluetoothProfileManager( 2517): LocalBluetoothProfileManager construction complete
W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,D/LGBluetoothUserBindClient( 2517): [BTUI] initUserBindClient
,D/DockEventReceiver( 2517): finishStartingService: stopping service
,D/BluetoothA2dp( 2517): Proxy object connected
,D/A2dpProfile( 2517): Bluetooth service connected
,W/ContextImpl( 2517): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothHeadset( 2517): Proxy object connected
D/HeadsetProfile( 2517): Bluetooth service connected
D/BluetoothInputDevice( 2517): Proxy object connected
D/HidProfile( 2517): Bluetooth service connected
D/BluetoothPan( 2517): BluetoothPAN Proxy object connected
D/PanProfile( 2517): Bluetooth service connected
,D/BluetoothMap( 2517): Proxy object connected
D/MapProfile( 2517): Bluetooth service connected
,D/BluetoothMap( 2517): getConnectedDevices()
,V/BluetoothMapService( 1216): getConnectedDevices()
D/BluetoothPbap( 2517): Proxy object connected
D/PbapServerProfile( 2517): Bluetooth service connected
,D/LGBluetoothUserBindClient( 2517): [BTUI] onServiceConnected
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothPermissionRequest( 2517): onReceive
D/LGBluetoothFeatureConfig( 2517): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2517): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2517): return without doing reset settings.
V/BluetoothOppReceiver( 1216): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1216): [BTUI] startOppService()
,V/BluetoothOppManager( 1216): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1216): isPrivacyLogsEnabled : true
V/BtOppService( 1216): onCreate
,D/LGBluetoothOppAdapter( 1216): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1216): send message
,V/BtOppService( 1216): Starting RfcommListener
,D/BluetoothOppPreference( 1216): Dumping Names:  
D/BluetoothOppPreference( 1216): {}
D/BluetoothOppPreference( 1216): Dumping Channels:  
,D/BluetoothOppPreference( 1216): {}
,V/BtOppService( 1216): onStartCommand
V/BluetoothOppNotification( 1216): new notify threadi!
,V/BtOppService( 1216): Deleted complete outbound shares, number =  0
,V/BluetoothOppNotification( 1216): send delay message
V/BtOppService( 1216): start RfcommListener
V/BtOppService( 1216): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428deb58 on behalf of 
V/BtOppService( 1216): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 1216): RfcommListener started
V/BtOppRfcommListener( 1216): Starting RFCOMM listener....
,V/BtOppService( 1216): ContentObserver received notification
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BtOppService( 1216): ContentObserver received notification
V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,W/BluetoothAdapter( 1216): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1216): SOCK FLAG = 0 ***********************
D/bt-btif ( 1216): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1216): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1216): BTA_JvCreateRecordByUser
D/bt-btif ( 1216): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1216): name:OBEX Object Push, scn:12
D/bt-btif ( 1216): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1216): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1216): Adding UUID=0x1105 into EIR
D/bt-btif ( 1216): BTA is generating EIR
I/bt-btif ( 1216): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1216): BTA_JvRfcommStartServer
D/bt-btif ( 1216): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1216): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
,D/LGBluetoothServiceAdapter( 1216): [BTUI] createSocketChannel FD=95 mFd=92
V/BtOppRfcommListener( 1216): Started RFCOMM listener....
I/BtOppRfcommListener( 1216): Accept thread started.
,V/BtOppRfcommListener( 1216): Accepting connection...
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428e2318 on behalf of 
,V/BluetoothOppNotification( 1216): mUpdateCompleteNotification = true
,D/AuthorizationBluetoothService( 1535): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1535): Proximity feature is not enabled.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428e3840 on behalf of 
V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 1216): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428e5738 on behalf of 
V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428e66a8 on behalf of 
V/BluetoothOppNotification( 1216): update too frequent, put in queue
V/BluetoothOppNotification( 1216): outbound: succ-0  fail-0
V/BtOppService( 1216): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 1216): outbound notification was removed.
V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428e8f00 on behalf of 
,V/BluetoothOppNotification( 1216): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1216): inbound notification was removed.
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428ea5e8 on behalf of 
,D/dalvikvm(  965): GC_EXPLICIT freed 23224K, 49% free 29404K/57228K, paused 2ms+8ms, total 134ms
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4256): EAPOL: disable timer tick
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4256): EAPOL: disable timer tick
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1216): new notify threadi!
,V/BluetoothOppNotification( 1216): send delay message
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428ec078 on behalf of 
,V/BluetoothOppNotification( 1216): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428edcb0 on behalf of 
,V/BluetoothOppNotification( 1216): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1216): outbound notification was removed.
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428ef840 on behalf of 
,V/BluetoothOppNotification( 1216): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1216): inbound notification was removed.
,V/BluetoothOppProvider( 1216): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1216): created cursor android.database.sqlite.SQLiteCursor@428f0de8 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  271): thread 0xb25be008 type 0 TID 1002 going to sleep
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  271): thread 0xb2729008 type 0 TID 930 going to sleep
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): nl80211: Event message available
D/wpa_supplicant( 4256): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4256): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4256): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4256): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 4256): nl80211: Survey data missing
D/wpa_supplicant( 4256): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 7 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Add new id 8 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 4256): wlan0: New scan results available
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4256): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4256): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4256): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4256): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 4256): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4256): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4,256): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4256): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4256): WPS: AP[4] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4256): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4256): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 4256): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4256): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-52
D/wpa_supplicant( 4256): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4256): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-52 wps
D/wpa_supplicant( 4256): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4256): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4256): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4256): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 4256): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 4256): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4256): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4256): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4256): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7b9a5a8  current_ssid=0x0
,D/wpa_supplicant( 4256): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC,
E/wpa_supplicant( 4256): USIM:  scard_init function
D/wpa_supplicant( 4256): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
,D/wpa_supplicant( 4256): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 4256): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
,D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00,
,D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 4256): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4256): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4256): wlan0: Cancelling scan request
,D/wpa_supplicant( 4256): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4256): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4256): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4256): RSN: PMKSA cache search - network_ctx=0xb7b9a5a8 try_opportunistic=0
,D/wpa_supplicant( 4256): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4256): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4256): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 4256): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4256): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4256): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4256): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 4256): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4256): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4256): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 4256): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 4256): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4256): nl80211: Unsubscribe mgmt frames handle 0xb7b99590 (mode change),
,D/wpa_supplicant( 4256): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590,
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a],
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
,D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590,
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590,
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 4256): nl80211: Register frame type=0xd0 nl_handle=0xb7b99590
,D/wpa_supplicant( 4256): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4256): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4256):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256):   * freq=2412
,D/wpa_supplicant( 4256):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 4256):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256):   * Auth Type 0
D/wpa_supplicant( 4256):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48],
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 a0:c5:62:7a:49:97],
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 64:7c:34:12:7f:81]
D/wpa_supplicant( 4256): nl80211: Connect request send successfully,
D/wpa_supplicant( 4256): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4256): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 4256): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4256): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 10:9a:dd:8e:22:d9]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 0c:bd:51:2b:c1:25],
D/wpa_supplicant( 4256): RSN: Ignored PMKID candidate without preauth flag
,D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147461,
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987,
,D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 4256): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/wpa_supplicant( 4256): nl80211: Event message available
D/wpa_supplicant( 4256): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4256): nl80211: Connect event
D/wpa_supplicant( 4256): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4256): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4256): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4256): wlan0: Association info event
D/wpa_supplicant( 4256): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4256): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4256): wlan0: freq=2412 MHz
D/wpa_supplicant( 4256): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4256): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4256): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4256): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): scard is not null..
D/wpa_supplicant( 4256): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4256): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4256): TDLS: Remove peers on association
D/wpa_supplicant( 4256): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4256): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4256): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4256): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4256): EAPOL: enable timer tick
D/wpa_supplicant( 4256): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4256): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 4256): wlan0: Cancelling scan request
D/wpa_supplicant( 4256): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4256): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 ...
D/wpa_supplicant( 4256): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4256): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4256): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4256): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4256): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4256):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4256):   key_nonce - hexdump(len=32): a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 77 c3 ce a4 fd df 37 3c 98 76 65 d5 20 ec 22 d9 d5
D/wpa_supplicant( 4256):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 ...
D/wpa_supplicant( 4256): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4256): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4256): Get randomness: len=32 entropy=10
D/wpa_supplicant( 4256): WPA: Renewed SNonce - hexdump(len=32): fd 95 a0 ba 79 d8 ab 29 3b d3 42 ba 94 ef a8 7b c1 62 73 06 95 8a 66 de c0 12 83 d7 58 3e 51 d6
D/wpa_supplicant( 4256): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4256): WPA: Nonce1 - hexdump(len=32): fd 95 a0 ba 79 d8 ab 29 3b d3 42 ba 94 ef a8 7b c1 62 73 06 95 8a 66 de c0 12 83 d7 58 3e 51 d6
,D/wpa_supplicant( 4256): WPA: Nonce2 - hexdump(len=32): a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 77 c3 ce a4 fd df 37 3c 98 76 65 d5 20 ec 22 d9 d5
D/wpa_supplicant( 4256): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4256): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4256): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01,
D/wpa_supplicant( 4256): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4256): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4256): WPA: Derived Key MIC - hexdump(len=16): 0a 11 36 7f 48 2f 45 c5 de 60 7b fe 6c 6b 6a 5a
,D/wpa_supplicant( 4256): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 fd 95 a0 ba 79 d8 ab 29 3b d3 42 ba 94 ef a8 ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4256): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 ...
D/wpa_supplicant( 4256): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4256): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4256): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4256): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4256):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4256):   key_nonce - hexdump(len=32): a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 77 c3 ce a4 fd df 37 3c 98 76 65 d5 20 ec 22 d9 d5
D/wpa_supplicant( 4256):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_rsc - hexdump(len=8): c4 d3 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4256):   key_mic - hexdump(len=16): be f1 99 de c1 53 96 c6 84 62 fa 32 af 63 49 7a
D/wpa_supplicant( 4256): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a1 76 0c f3 ac d3 2d 19 c5 b2 73 e7 23 41 20 ...
D/wpa_supplicant( 4256): RSN: encrypted key data - hexdump(len=56): 11 1c 5f b1 26 82 50 65 13 41 1e df b1 8a d7 fe f3 cc e8 c9 a3 bf 62 e2 2d 27 1d ce 88 a2 ee ae ...
D/wpa_supplicant( 4256): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4256): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4256): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4256): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 4256): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4256): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4256): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4256): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4256): WPA: Derived Key MIC - hexdump(len=16): 73 94 09 0e 2f 8e 0e fe 5f b8 17 c8 2a 4e 79 3f
D/wpa_supplicant( 4256): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4256): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7b99c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4256):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4256): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4256): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4256): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4256): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 4256): WPA: RSC - hexdump(len=6): c4 d3 00 00 00 00
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7503a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4256):    broadcast key
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 4256): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4256): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4256): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4256): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4256): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4256): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4256): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4256): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4256): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4256): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4256): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4256): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4256): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4256): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4256): EAPOL authentication completed successfully
D/wpa_supplicant( 4256): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4256): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4256): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147459
,D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4256): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiService(  965): New client listening to asynchronous messages
,D/WifiStateMachine(  965): handleMessage: X
,D/DhcpStateMachine(  965): StoppedState
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-70ms what=147462 obj=android.net.wifi.StateChangeResult@42871678 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4431 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-63ms what=147462 obj=android.net.wifi.StateChangeResult@42808de8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-62ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-21ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 4256): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,D/HyLog   ( 4431): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4431): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4431): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4431): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4431): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4431): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4431): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4431): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4431): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4431): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4431): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4431): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  965): Killing 4015:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4256): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): handleMessage: X
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432ef4c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432ef4c0 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4256): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4256): EAPOL: disable timer tick
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4200): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4200): 
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
,V/LgDhcpStateMachineHelper(  965): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4256): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4256): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4256): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  965): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
,D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState enter
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=0 connState=2
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): handleMessage: X
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/QRemote ( 4431): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/QRemote ( 4431): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,D/QRemote ( 4431): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/QRemote ( 4431): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/        (  264): RouteController
,I/PCSuite ( 4257): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4257): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,D/QRemote ( 4431): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4431): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/QRemote ( 4431): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4431): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,V/        (  264): RouteController
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/        (  264): RouteController
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  600): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  600): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  600): |CAC| updateNetCfgInfo
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC|                   Netconfig               
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  600): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  600): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  600): |CAC| 	NetConfig: ip4        =192.168.1.121
V/QCNEA   (  600): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  600): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  600): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  600): |CAC| *********************************************
,D/QCNEA   (  600): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| net type = 1
V/QCNEA   (  600): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| Received ssid= NG700
V/QCNEA   (  600): |CAC| 	ssid           =NG700
V/QCNEA   (  600): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  600): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  600): |CAC| dispatchNetCfg: updating:0xb7c738dc
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/libc    (  264): _dns_getaddrinfo: iptype =1
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  965): NTP server returned: 1449832366753 (Fri Dec 11 12:12:46 CET 2015) reference: 119945 certainty: 25 system time offset: 2239
,E/LocSvc_afw(  965): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  965): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  965): V/time: 1449832366753
E/LocSvc_eng(  965):   timeReference: 119945
E/LocSvc_eng(  965):   uncertainty: 25
E/LocSvc_utils_q(  965): D/msg_q_snd: Sending message with handle = 0x67021890
E/LocSvc_utils_ll(  965): D/linked_list_add: Adding to list data_obj = 0x67021890
E/LocSvc_utils_q(  965): D/msg_q_snd: Finished Sending message with handle = 0x67021890
E/LocSvc_eng(  965): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
E/LocSvc_afw(  965): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_utils_ll(  965): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  965): D/msg_q_rcv: Received message 0x67021890 rv = 0
E/LocSvc_eng(  965): V/time: 1449832366753
E/LocSvc_eng(  965):   timeReference: 119945
E/LocSvc_eng(  965):   uncertainty: 25
E/LocSvc_ApiV02(  965): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 25
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 56, req_id 56 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 56, len = 16
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 56, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 56 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  965): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  965): D/msg_q_rcv: Waiting on message
,D/GpsLocationProvider(  965): calling native_inject_xtra_data
E/LocSvc_afw(  965): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  965): V/length: 58777
E/LocSvc_eng(  965):   data: 0x6a65d308
E/LocSvc_utils_q(  965): D/msg_q_snd: Sending message with handle = 0x6EDB2B50
,E/LocSvc_utils_ll(  965): D/linked_list_add: Adding to list data_obj = 0x6EDB2B50
E/LocSvc_utils_q(  965): D/msg_q_snd: Finished Sending message with handle = 0x6EDB2B50
E/LocSvc_utils_ll(  965): D/linked_list_remove: Removing from list
E/LocSvc_afw(  965): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
E/LocSvc_utils_q(  965): D/msg_q_rcv: Received message 0x6EDB2B50 rv = 0
E/LocSvc_eng(  965): V/length: 58777
E/LocSvc_eng(  965):   data: 0x6a65d308
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 58777
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/58, len = 1024, total injected = 0
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/58, len = 1024, total injected = 1024
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/58, len = 1024, total injected = 2048
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/58, len = 1024, total injected = 3072
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/58, len = 1024, total injected = 4096
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/58, len = 1024, total injected = 5120
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/58, len = 1024, total injected = 6144
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8,
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/58, len = 1024, total injected = 7168
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/58, len = 1024, total injected = 8192
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53,
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/58, len = 1024, total injected = 9216,
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0,
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 ,
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/58, len = 1024, total injected = 10240
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0,
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/58, len = 1024, total injected = 11264
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/58, len = 1024, total injected = 12288
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/58, len = 1024, total injected = 13312
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/58, len = 1024, total injected = 14336
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/58, len = 1024, total injected = 15360
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/58, len = 1024, total injected = 16384
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/58, len = 1024, total injected = 17408
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0,
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/58, len = 1024, total injected = 18432
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044,
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/58, len = 1024, total injected = 19456
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/58, len = 1024, total injected = 20480
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044,
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/58, len = 1024, total injected = 21504
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/58, len = 1024, total injected = 22528
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/58, len = 1024, total injected = 23552
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/58, len = 1024, total injected = 24576
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/58, len = 1024, total injected = 25600
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/58, len = 1024, total injected = 26624
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/58, len = 1024, total injected = 27648
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0,
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/58, len = 1024, total injected = 28672
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/58, len = 1024, total injected = 29696
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/58, len = 1024, total injected = 30720
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/58, len = 1024, total injected = 31744
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/58, len = 1024, total injected = 32768
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/58, len = 1024, total injected = 33792
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/58, len = 1024, total injected = 34816
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/58, len = 1024, total injected = 35840
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/58, len = 1024, total injected = 36864
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/58, len = 1024, total injected = 37888
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/58, len = 1024, total injected = 38912
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/58, len = 1024, total injected = 39936
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/58, len = 1024, total injected = 40960
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/58, len = 1024, total injected = 41984
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/58, len = 1024, total injected = 43008
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/58, len = 1024, total injected = 44032
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/58, len = 1024, total injected = 45056
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/58, len = 1024, total injected = 46080
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/58, len = 1024, total injected = 47104
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/58, len = 1024, total injected = 48128
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/58, len = 1024, total injected = 49152
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/58, len = 1024, total injected = 50176
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/58, len = 1024, total injected = 51200
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/58, len = 1024, total injected = 52224
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/58, len = 1024, total injected = 53248
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/58, len = 1024, total injected = 54272
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/58, len = 1024, total injected = 55296
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/58, len = 1024, total injected = 56320
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/58, len = 1024, total injected = 57344
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/58, len = 409, total injected = 58368
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x67320480, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67320480
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67320480, resp id = 53, client cookie ptr = 0x67320e18
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x67320480 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58777
E/LocSvc_MsgTask(  965): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  965): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  965): handleMessage: X
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/        (  965): Setting time of day to sec=1449832369
,W/        (  965): Unable to set rtc to 1449832369: Invalid argument
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-9ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:12:49
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1156): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832369589, nextTick: 10431, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832369598, nextTick: 10435, mDrawingTime: 0
,I/MusicWidget( 2096): intentReceiver onReceive() action::android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
,I/MusicWidget( 2096): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2096): beingMusicWidget_Lock() result::false
,I/MusicWidget( 2096): beingMusicWidget_Quick() result::false
,I/MusicWidget( 2096): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2096): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2096): performUpdate()_4x1
,I/MusicWidget( 2096): status::mounted
,I/MusicWidget( 2096): defaultAppWidget()_4x1
I/MusicWidget( 2096): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdateStart : false
I/MusicWidget( 2096): setDefaultViewLayoutId()_4x1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/MusicWidget( 2096): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2096): linkButtons()_4x1
,D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1872): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1872): 2 : Map key string is -2
,D/lim     ( 1872): 2 : time = 12:12
I/WeatherReflect( 1872): Model Name : LG-D802
D/WeatherTheme( 1872): 2 : Different view - status_min_formatted : 11 != 12
D/WeatherTheme( 1872): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1872): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1872): 2 : Fixed theme : optimus
,I/MusicWidget( 2096): pushUpdate()_4x1
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::3
,D/WeatherTheme( 1872): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,I/MusicWidget( 2096): beingMusicWidget_Quick() result::false
,D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:12:49
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,D/QCNEA   (  600): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
,D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@428243b0
D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
,I/LicenseContentProvider( 2926): start selecting data
,D/SIMObserver( 2926): simInfo1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/AppUp4:CustModeStarterReceiver( 3659): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3659): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3659): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3659): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3659): handleAsyncCustNotification do not startCustService
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4577 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  965): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4591 uid=10063 gids={50063, 3003, 1028, 1015}
,D/HyLog   ( 4577): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4577): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4577): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4591): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2096): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2096): beingMusicWidget_Lock() result::false
,V/DownloadManager( 4577): DownloadService onCreate
,I/DownloadManager( 4577): in removeSpuriousFiles
,D/EAS     ( 4100): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4100): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4100): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42854b40 on behalf of 4577
,I/DownloadManager( 4577): in trimDatabase
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42858240 on behalf of 4577
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): DownloadService onStartCommand
,W/linker  ( 4100): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4100): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4100): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4100): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/ActivityManager(  965): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4617 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/dalvikvm( 4100): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4285c1e8 on behalf of 4577
D/HtmlEditor( 4100): register_HtmlEditor, Success
D/HtmlEditor( 4100): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4100): register_HtmlEditorTimer, Success
D/HtmlEditor( 4100): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4100): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4100): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4100): register_HtmlEditorFont, Success
D/HtmlEditor( 4100): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4100): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4100): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4100): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4100): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4100): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4100): JNI_OnLoad Success
I/HubEmail( 4100): JNI_OnLoad()
I/HubEmail( 4100): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4100): registerNatives()
I/HubEmail( 4100): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4100): registerNativeMethods()
I/HubEmail( 4100): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/DelayedSyncController( 4591): Delaying sync.
W/Settings( 4100): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42860240 on behalf of 4577
,D/HyLog   ( 4617): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4617): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4617): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Finsky  ( 3736): [339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3736): [1] 5.onFinished: Installation state replication succeeded.
,V/DownloadManager( 4577): DownloadService onDestroy
I/ActivityManager(  965): Killing 4051:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,W/DriveInitializer( 1945): Background init thread started
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 3678:com.android.contacts/u0a21 (adj 15): empty #17
,I/ConversationSkinProvider( 4617): skin provider oncreate
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,I/ConfigFetchService( 1945): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,E/[MMS]   ( 4617): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 4617): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4617): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4617): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
I/ConfigFetchService( 1945): running network task: configservice_periodic
W/BaseRuntimeLoader( 4617): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/WakeLock( 1945): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1945): launchTask
,E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 4617): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4617): MmsSettings: Matching Xml Data file name = 2131034168
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  965): battery changed pluggedType: 2
,D/dalvikvm( 1535): GC_EXPLICIT freed 772K, 29% free 17874K/24832K, paused 2ms+3ms, total 32ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/Auth.Api.Credentials( 1945): [CredentialSyncAdapter] Unknown sync event.
,I/ConfigService( 1535): onCreate
,D/[MMS]   ( 4617): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4617): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
,E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4617): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_dr_a = [1]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   auto_retr = [1]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   auto_retr_r = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4617): MmsSettings: [LGE]   slide_dur = [5]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   del_old = [1]
D/Batterystats( 1945): User is not opted-in to Usage & Diagnostics.
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4617): MmsSettings: [LGE]   max_editor_num = [2000]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4617): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   anonymous_spam_setting = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4617): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_dr_invisible = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   animation_effect = [1]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   one_bubble = [1]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   hide_sync_header_update = [1]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4617): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   kr_skt_feature_set = [0]
I/ConfigFetchService( 1945): service connected
D/[MMS]   ( 4617): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_message_setting = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4617): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sticky_note = [0]
D/ConfigFetchService( 1945): ConfigApi connection successful.
D/[MMS]   ( 4617): MmsSettings: [LGE]   wificalling_feature_set = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4617): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
,D/[MMS]   ( 4617): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 4617): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
,I/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 4617): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4617): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,W/DriveInitializer( 1945): Awaiting to be initialized
,W/DriveInitializer( 1945): Background init thread ended
,I/[MMS]   ( 4617): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4617): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b8a489d8
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
,E/Diag_Lib(  275): Setting the api flag to : 1
,E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
E/Diag_Lib(  275):  Message ID ............... 37 
E/Diag_Lib(  275): qmi_service_release called, user_handle=20200
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  275): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  275): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b8a489f0
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
,E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
,E/Diag_Lib(  275):  API Flag .............. 1 
E/Diag_Lib(  275):  Message ID ............... 37 
E/Diag_Lib(  275): qmi_service_release called, user_handle=20200
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  275): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  275): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
,E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4617): isDrmV1 =true
,V/DrmWrapper( 4617): isDrmV2 =false
,V/MmsConfig( 4617): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 4617): [setMmsEnabledWhenDataDisabled]enabled=true
,D/dalvikvm( 1945): GC_CONCURRENT freed 1200K, 23% free 19236K/24832K, paused 3ms+3ms, total 34ms
,V/MmsConfigStaticVar( 4617): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4617): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4617): Contact init()_Create new insatnce
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.442886 Y: -0.398041 Z: 9.764755 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442886 .y:-0.398041 .z:9.764755
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/dalvikvm(  965): GC_EXPLICIT freed 2455K, 49% free 29442K/57228K, paused 3ms+8ms, total 95ms
,D/DelayedSyncController( 4591): Delaying sync.
,I/MessagingNotification( 4617): registerLEDObserver
,I/MessagingNotification( 4617): registerLEDObserver REGISTER
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.442871 Y: -0.400620 Z: 9.763885 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442871 .y:-0.400620 .z:9.763885
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/MmsConfig( 4617): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/LocationManagerService(  965): getProviders()=[passive, gps]
D/LocationManagerService(  965): request 4318e1b0 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,I/LOG_TAG ( 4617): registerContactDBChangeObserver
,I/LgeMiscReceiver( 4617): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4617): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4617): networkInfo.isConnected() = false
D/CountryDetector(  965): The first listener is added
E/ActivityThread( 4617): Failed to find provider info for com.lge.ims.provider.uc
,V/LGRssiData( 4617): [loadRssi] File not exist 
,V/LGRssiData( 4617): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4617): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4617): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4617): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4617): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4671 uid=10052 gids={50052, 3003}
I/ActivityManager(  965): Killing 4119:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/HyLog   ( 4671): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4671): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4671): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4671): [loadRssi] File not exist 
V/LGRssiData( 4671): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4671): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4671): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4671): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4671): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4671): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 4671): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4671): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4671): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4671): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4671): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4671): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4671): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4685 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  965): Killing 1860:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/CheckinService( 1945): Checking schedule, now: 1449832370363 next: 1449796404139
,I/CheckinService( 1945): active receiver: enabled
D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 2ms+2ms, total 21ms
D/HyLog   ( 4685): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4685): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4685): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+1ms, total 15ms
,I/CheckinService( 1945): Preparing to send checkin request
,I/EventLogService( 1945): Accumulating logs since 1449831602437
,D/DrmBroadcastReceiver( 4685): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2810): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  965): Killing 4329:com.lge.lgdmsgcm/1000 (adj 15): empty #17
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/LGDMClient( 2810): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2810): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2810): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2810): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2810): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2810): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinRequestBuilder( 1945): Checkin reason type: 8 attempt count: 1
D/WifiService(  965): New client listening to asynchronous messages
E/ActivityThread( 1945): Failed to find provider info for com.google.android.wearable.settings
,W/BaseRuntimeLoader( 1945): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1945): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1945): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1945): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1945): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4297e1e0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4701 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4701): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4701): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4701): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4701): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4701): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4701): VFY: replacing opcode 0x62 at 0x005e
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/MultiDex( 4701): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4701): install
I/MultiDex( 4701): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 4701): loading existing secondary dex files
I/MultiDex( 4701): load found 3 secondary dex files
,I/MultiDex( 4701): install done
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/NFS     ( 4343): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4343): CONNECT : WIFI_CONNECT
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4718 uid=10104 gids={50104, 3003, 1028, 1015}
D/dalvikvm( 4701): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4701): VFY: unable to resolve instance field 61
D/dalvikvm( 4701): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4701): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4701): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4701): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4701): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4701): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4701): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4701): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4701): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4701): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42813250
D/dalvikvm( 4701): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42813250
D/dalvikvm( 4701): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42813250, skipping init
D/dalvikvm( 4701): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42813250
D/dalvikvm( 4701): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42813250
V/JNIHelp ( 4701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/HyLog   ( 4718): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4718): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4718): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/dalvikvm( 4701): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42813250
W/GAV2    ( 4718): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 4701): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42813250
D/dalvikvm( 4701): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42813250
,D/dalvikvm( 4701): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42813250
,I/ProviderInstaller( 4701): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4701): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4701): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4701): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4701): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4701): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4701): VFY: replacing opcode 0x6e at 0x0201
,V/WebViewChromium( 4718): Binding Chromium to the main looper Looper (main, tid 1) {4280e170}
,I/chromium( 4718): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4718): Initializing chromium process, renderers=0
,W/chromium( 4718): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4718): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4718): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4718): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4718): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4718): Remote Branch: 
I/Adreno-EGL( 4718): Local Patches: 
I/Adreno-EGL( 4718): Reconstruct Branch: 
,I/NSApplication( 4718): Starting up...
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/QSEECOMAPI: (  271): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  271): App is not loaded in QSEE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/ActivityManager(  965): Killing 4084:com.lge.bnr/1000 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/dalvikvm( 4701): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.a.a
W/dalvikvm( 4701): VFY: unable to resolve virtual method 299: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4701): VFY: replacing opcode 0x6e at 0x0013
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/QSEECOMAPI: (  271): Loaded image: APP id = 2
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3b000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3b000
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/dalvikvm( 4701): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4701): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4701): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4701): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4701): VFY: unable to resolve virtual method 727: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4701): VFY: replacing opcode 0x6e at 0x00bb
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,I/GoogleURLConnFactory( 4701): Using platform SSLCertificateSocketFactory
,I/iu.SyncManager( 1945): SYNC; picasa accounts
D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/NetworkLogImpl( 1945): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1945): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1945): num queued entries: 0
,I/iu.UploadsManager( 1945): num updated entries: 0
,I/iu.SyncManager( 1945): NEXT; no task
D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,E/DataScheduler( 4701): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager(  965): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4783 uid=10010 gids={50010, 3003, 1028, 4002}
D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
D/HyLog   ( 4783): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4783): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4783): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,E/OpenGL ES Test( 4783): getCurrentLocale == en_US
E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
,E/OpenGL ES Test( 4783): localeFound retString == en_US
,D/ALBootInit( 4783): ====action==>android.intent.action.TIME_SET
D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=3976185912
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ALBootInit( 4783): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4783): [setNextAlert] start
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/Alarms  ( 4783): [setNextAlert] (1)
,D/Alarms  ( 4783):  minTime  = 0
,D/Alarms  ( 4783):  -- OK multi -- 0
E/jeny.kim( 4783): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4783): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4783): setStatusBarIcon : false
,D/Alarms  ( 4783): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4783): ====action==>android.intent.action.TIME_SET
,E/OpenGL ES Test( 4783): getCurrentLocale == en_US
E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
,E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
,E/OpenGL ES Test( 4783): localeFound retString == en_US
,E/OpenGL ES Test( 4783): isExistDatabase = false
,I/CommonUtil( 4783): BUILD Country: EU
E/OpenGL ES Test( 4783): loadMapCityData() -- S
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
,E/OpenGL ES Test( 4783): localeFound retString == en_US
,E/OpenGL ES Test( 4783): loadMapCityData() - While S
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,E/OpenGL ES Test( 4783): loadMapCityData() - While E
,E/OpenGL ES Test( 4783): loadMapCityData() -- E
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
E/OpenGL ES Test( 4783): localeFound retString == en_US
E/OpenGL ES Test( 4783): getCurrentLocale == en_US
,E/OpenGL ES Test( 4783): localeFound retString == en_US
,E/OpenGL ES Test( 4783): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  965): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4800 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4304:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4800): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4800): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/Config  ( 4800): LGCalendar ver.4.2.6
,I/Config  ( 4800): start check model
I/Config  ( 4800): start check native_ca
,E/Config  ( 4800): [setCountryAndOperator] Operator=OPEN, Country=EU
,D/GCM     ( 1535): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1535): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/CalendarWidget( 4800): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,I/InitNotificationRingtoneService( 4800): Start InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  965): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4818 uid=10016 gids={50016, 3003, 1028, 1015}
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/InitNotificationRingtoneService( 4800): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4800): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4800): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4800): End InitializeAlertRingtoneService.onHandleIntent
,I/CalendarProvider2( 4818): Created com.android.providers.calendar.CalendarAlarmManager@4282fac0(com.android.providers.calendar.CalendarProvider2@42826a28)
,I/ActivityManager(  965): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4835 uid=10043 gids={50043, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4257:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4701): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b91c50
D/dalvikvm( 4701): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b91c50
,D/dalvikvm( 4701): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42b91c50, skipping init
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm(  965): GC_EXPLICIT freed 1351K, 49% free 29395K/57228K, paused 3ms+6ms, total 90ms
D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/TASKS   ( 4835): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4835): onReceive() #################################################
,I/TASKS   ( 4835): getCurrentThemeInfo START #############################
,I/TASKS   ( 4835): com.lge.launcher2.theme.optimus
I/TASKS   ( 4835): com.lge.task
I/TASKS   ( 4835): getCurrentThemeInfo END #############################
I/TASKS   ( 4835): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4835): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4835): intentAction : android.intent.action.TIME_SET
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
I/ActivityManager(  965): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4853 uid=10122 gids={50122}
I/ActivityManager(  965): Killing 4431:com.lge.qremote/u0a96 (adj 15): empty #17
W/ActivityThread(  965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4853): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4853): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Settings( 4701): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4853): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42818e80, skipping init
D/TimeService( 4853): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832371616
D/        ( 4853): TimeServiceNative: User Time to be set is 1449832371616
D/QC-time-services( 4853): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4853): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 4853): Lib:time_genoff_operation: pargs->ts_val = 1449832371616
D/QC-time-services(  610): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4853): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  610): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832371616
D/QC-time-services(  610): Daemon:genoff_opr: Base = 2, val = 1449832371616, operation = 0
D/QC-time-services(  610): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/17/70 22:57:43
D/QC-time-services(  610): Daemon:Value read from RTC seconds = 9241063000
D/QC-time-services(  610): Daemon:new time 1449832371616 
,D/QC-time-services(  610): Daemon: delta 1440591308616 genoff 1440591308616 
D/QC-time-services(  610): Daemon:genoff_persistent_update: Writing genoff = 1440591308616 to memory
D/QC-time-services(  610): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  610): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QC-time-services(  610): Updating the TOD offset
,D/QC-time-services(  610): Daemon:genoff_persistent_update: Writing genoff = 1440591308616 to memory
D/QC-time-services(  610): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  610): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  610): Daemon:Update to modem bit set
E/QC-time-services( 4853): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  610): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  610): Daemon: Base = 2, Value being sent to MODEM = 1133867571616
,I/ActivityManager(  965): Killing 3736:com.android.vending/u0a50 (adj 15): empty #17
E/QC-time-services(  610): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  610): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
,D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@428243b0
D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
I/LicenseContentProvider( 2926): start selecting data
,D/SIMObserver( 2926): simInfo1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
,I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4100): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4577): DownloadService onCreate
,D/EAS     ( 4100): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/DownloadManager( 4577): in removeSpuriousFiles
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/LgeMiscReceiver( 4617): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4617): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4617): networkInfo.isConnected() = true
D/PhoneState( 4617): setPdpRejectCasuse : false
W/Settings( 4100): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42867d68 on behalf of 4577
D/MobileConnectivityChangeReceiver( 4671): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4671): onReceive CONNECTIVITY_CHANGE networkType=1
I/DownloadManager( 4577): in trimDatabase
V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428692f0 on behalf of 4577
D/DrmBroadcastReceiver( 4685): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 4685): 1  network is available. Sync DRM Time with NTP
V/DownloadManager( 4577): DownloadService onStartCommand
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4286b028 on behalf of 4577
V/DrmService( 4685): Service onCreate
D/DrmService( 4685): Received new request = 2
D/LGDMClient( 2810): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/dalvikvm( 4701): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/DrmSntpClient( 4685): Start Sync process
D/DrmSntpClient( 4685): Server : 0
V/DownloadManager( 4577): DownloadService onDestroy
V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
E/DataScheduler( 4685): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/LGDMClient( 2810): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2810): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2810): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4876 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/LGDMClient( 2810): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2810): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2810): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4876): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/LGDMSGCM( 4876): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/NFS     ( 4343): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4343): CONNECT : WIFI_CONNECT
W/ContextImpl( 4876): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm( 4875): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,I/LGDrmService( 4685): _DRM_ServiceGet() : Bind lgdrm service
D/dalvikvm( 3709): GC_FOR_ALLOC freed 751K, 16% free 20922K/24832K, paused 14ms, total 14ms
I/LGDRM   (  275): [DRM] SET TIME : YR=2015, MON=12, DAY=11
,I/LGDRM   (  275): [DRM] SET TIME : HR=11, MIN=12, SEC=50
,I/dalvikvm-heap( 3709): Grow heap (frag case) to 26.514MB for 4099024-byte allocation
,I/DrmSntpClient( 4685): Synched
D/DrmService( 4685): Completed !! request = 2
,D/DrmService( 4685): Request count = 0
,V/DrmService( 4685): Service onDestroy
D/dalvikvm( 4701): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4701): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 75ms
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4701): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4701): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4701): Remote Branch: 
I/Adreno-EGL( 4701): Local Patches: 
I/Adreno-EGL( 4701): Reconstruct Branch: 
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 3709): GC_CONCURRENT freed 37K, 14% free 24892K/28836K, paused 3ms+2ms, total 16ms
I/ActivityManager(  965): Killing 3692:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/dalvikvm( 3709): GC_FOR_ALLOC freed 2K, 14% free 24889K/28836K, paused 18ms, total 18ms
,D/AuthorizationBluetoothService( 1535): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1535): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1945): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm-heap( 3709): Grow heap (frag case) to 30.388MB for 4099024-byte allocation
,D/dalvikvm( 3709): GC_CONCURRENT freed <1K, 13% free 28892K/32840K, paused 2ms+1ms, total 13ms
,I/ActivityManager(  965): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4893 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/LocationInitializer( 1945): Restart initialization of location
,D/WeatherAncestor( 1872): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:12:51
D/HyLog   ( 4893): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4893): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4893): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
,D/Weather_cast( 1872): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1872): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:12:51
,D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,D/WeatherQuickCover( 1872): 2 : quick cover state : opened : 0
,W/dalvikvm( 4893): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4893): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4893): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4893): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4893): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4893): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4893): install
,I/MultiDex( 4893): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
,I/MultiDex( 4893): loading existing secondary dex files
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4908 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
I/MultiDex( 4893): load found 3 secondary dex files
I/MultiDex( 4893): install done
,D/HyLog   ( 4908): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4908): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4908): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4893): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4893): VFY: unable to resolve instance field 61
,D/dalvikvm( 4893): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4893): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4893): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4893): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4893): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4893): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4893): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4893): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4893): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4893): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c390
,D/dalvikvm( 4893): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c390
,D/dalvikvm( 4893): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c390, skipping init
D/dalvikvm( 4893): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c390
,D/dalvikvm( 4893): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c390
,V/JNIHelp ( 4893): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/dalvikvm( 4893): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c390
,D/dalvikvm( 4893): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4281c390
D/dalvikvm( 4893): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c390
,D/dalvikvm( 4893): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4281c390
D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2259148384
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Babel   ( 4908): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4908): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4908): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4908): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 4908): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 4908): MmsConfig.loadFromDatabase
I/MediaCodecList( 4908): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4908): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 4908): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/Settings( 4908): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 4908): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4908): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4908): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4908): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4908): MmsConfig.loadFromResources
,E/Babel   ( 4908): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4908): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/ProviderInstaller( 4893): Installed default security provider GmsCore_OpenSSL
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4908): [loadRssi] File not exist 
V/LGRssiData( 4908): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4908): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4908): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4908): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4908): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@428243b0
D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
,I/LicenseContentProvider( 2926): start selecting data
,D/SIMObserver( 2926): simInfo1
,I/dalvikvm( 4893): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4893): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x003f
,I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/WearableService( 4893): callingUid 10006, callindPid: 4893
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
E/dalvikvm( 4893): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4893): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
D/dalvikvm( 4893): VFY: replacing opcode 0x1f at 0x0054
V/DownloadManager( 4577): DownloadService onCreate
I/DownloadManager( 4577): in removeSpuriousFiles
W/dalvikvm( 4893): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4100): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4100): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4286f1b0 on behalf of 4577
I/DownloadManager( 4577): in trimDatabase
V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42870ba8 on behalf of 4577
I/LgeMiscReceiver( 4617): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4617): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4617): networkInfo.isConnected() = true
D/PhoneState( 4617): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 4671): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4100): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4671): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2810): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LGDMClient( 2810): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4876): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4577): DownloadService onStartCommand
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42872d58 on behalf of 4577
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,I/NFS     ( 4343): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4343): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2810): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4876): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
E/LGDMClient( 2810): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2810): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2810): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2810): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/dalvikvm( 4893): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4893): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x000d
V/DownloadManager( 4577): DownloadService onDestroy
I/dalvikvm( 4893): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4893): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4893): VFY: replacing opcode 0x6e at 0x0201
,D/dalvikvm( 3709): GC_FOR_ALLOC freed 2K, 13% free 28892K/32840K, paused 17ms, total 17ms
,E/MDM     ( 1424): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm-heap( 3709): Grow heap (frag case) to 34.297MB for 4099024-byte allocation
,D/dalvikvm( 3709): GC_CONCURRENT freed 4K, 11% free 33054K/36844K, paused 2ms+1ms, total 15ms
,D/dalvikvm( 1535): GC_EXPLICIT freed 1248K, 28% free 17903K/24832K, paused 1ms+3ms, total 24ms
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/CalendarWidget( 4800): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4800): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/TASKS_APP_WIDGET( 4835): onReceive() #################################################
,I/TASKS   ( 4835): getCurrentThemeInfo START #############################
I/TASKS   ( 4835): com.lge.launcher2.theme.optimus
I/TASKS   ( 4835): com.lge.task
I/TASKS   ( 4835): getCurrentThemeInfo END #############################
I/TASKS   ( 4835): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4835): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4835): intentAction : com.lge.task.APPWIDGET_UPDATE
D/CalendarWidget( 4800): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4800): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1535): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1535): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1945): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1945): Restart initialization of location
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4701): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4701): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4701): Remote Branch: 
I/Adreno-EGL( 4701): Local Patches: 
I/Adreno-EGL( 4701): Reconstruct Branch: 
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4701): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4701): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4701): Remote Branch: 
I/Adreno-EGL( 4701): Local Patches: 
I/Adreno-EGL( 4701): Reconstruct Branch: 
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4908): UserRecoverableAuthException.
,E/Babel   ( 4908): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4908): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4908): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4908): Error getting auth token
,E/Babel   ( 4908): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4908): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4908): Account registration failedRedacted-21
E/Babel   ( 4908): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4908): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4908): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4908): Account sign in complete with state 106account: Redacted-21
,I/CheckinRequestBuilder( 1945): Classify the device as Phone.
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4908): Unexpected exception while authenticating.
,E/Babel   ( 4908): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4908): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4908): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4908): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4908): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4908): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4908): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4908): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4908): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43062048: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CalendarProvider2( 4818): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4818): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4800): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4800): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CalendarWidget( 4800): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4800): Beginning updateAlertNotification
,D/AlertService( 4800): No fired or scheduled alerts
,I/ActivityManager(  965): Killing 4783:com.lge.clock/u0a10 (adj 15): empty #17
,D/CalendarWidget( 4800): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4800): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1945): Sending checkin request (11668 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinResponseProcessor( 1945): From server: 2 gservices updates and 0 deletes
,D/dalvikvm( 1945): GC_CONCURRENT freed 1639K, 22% free 19530K/24832K, paused 8ms+7ms, total 76ms
,I/CertBlacklister(  965): Certificate blacklist changed, updating...
,I/CertBlacklister(  965): Certificate blacklist updated
,I/GservicesProvider( 1535): main difference update completed
,I/ActivityManager(  965): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4970 uid=10003 gids={50003, 3003, 2001}
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 28ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 21ms
,D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4970): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1945): Checkin reason type: 8 attempt count: 1
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 22ms
,E/ActivityThread( 1945): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/UpdateFetcherService( 4970): Update started
,D/DownloadManager( 4577): DB Update : deleted 1
,V/DownloadManager( 4577): DownloadService onCreate
,I/DownloadManager( 4577): in removeSpuriousFiles
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): initiating download with UID 10003
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4287be70 on behalf of 4577
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): DownloadService onStartCommand
I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/DownloadManager( 4577): in trimDatabase
V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42880fb8 on behalf of 4577
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42882298 on behalf of 4577
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 4577): processing inserted download 165
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:190
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42885960 on behalf of 4577
,E/UpdateRequestReceiver( 4970): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/dalvikvm(  965): GC_EXPLICIT freed 1451K, 49% free 29608K/57228K, paused 2ms+8ms, total 83ms
,D/DownloadManager( 4577): DB Update : status 192
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428886e0 on behalf of 4577
I/UpdateFetcherService( 4970): Update started
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4288a560 on behalf of 4577
,D/DownloadManager( 4577): DB Update : deleted 1
,V/DownloadManager( 4577): processing updated download 165, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
V/DownloadManager( 4577): DownloadService onStartCommand
I/DownloadManager( 4577): Download 165 starting
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4288e438 on behalf of 4577
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4577): initiating download with UID 10003
D/DownloadManager( 4577): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43c63e98: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1945): awaiting user notification for token
E/DataScheduler( 4577): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/CheckinRequestBuilder( 1945): Classify the device as Phone.
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428a7d98 on behalf of 4577
,V/DownloadManager( 4577): processing updated download 165, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428a9c58 on behalf of 4577
V/DownloadManager( 4577): processing inserted download 166
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=166:190
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428abe10 on behalf of 4577
,D/DownloadManager( 4577): DB Update : status 192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/CheckinTask( 1945): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428af9c0 on behalf of 4577
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428b0000 on behalf of 4577
,I/DownloadManager( 4577): Download 166 starting
I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4577): processing updated download 165, status: 192
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 1945): Checking schedule, now: 1449832373594 next: 1450409769587
I/CheckinService( 1945): active receiver: disabled
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 9272K, 14% free 68361K/78612K, paused 44ms, total 44ms
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428b2b20 on behalf of 4577
V/DownloadManager( 4577): processing updated download 166, status: 192
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=166:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@428b4690 on behalf of 4577
,D/DownloadManager( 4577): fileSize : -1state.mContinuingDownload :false
,E/UpdateRequestReceiver( 4970): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4970): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 4970): Received malformed URL while handling Gservices.CHANGED_ACTION
I/CheckinService( 1945): Checking schedule, now: 1449832373634 next: 1450409769587
,I/CheckinService( 1945): active receiver: disabled
,I/ActivityManager(  965): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5030 uid=10009 gids={50009, 3003}
,I/DownloadManager( 4577): Ignoring Content-Length since Transfer-Encoding is also defined
D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5030): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5030): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/DownloadManager( 4577): Content-Disposition: null
V/DownloadManager( 4577): Content-Length: -1
V/DownloadManager( 4577): Content-Location: null
V/DownloadManager( 4577): Content-Type: text/plain
V/DownloadManager( 4577): ETag: null
V/DownloadManager( 4577): Transfer-Encoding: chunked
,V/DownloadManager( 4577): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4577): Min update size = 16384
V/DownloadManager( 4577): getting filename from uri
I/DownloadManager( 4577): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
,V/DownloadManager( 4577): keeping extension
,V/DownloadManager( 4577): target file: /cache/10152015-sms-metadata.txt
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42906980 on behalf of 4577
D/DownloadManager( 4577): DB Update : title 10152015-sms-metadata.txt
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4577): DB Update : total_bytes -1
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4290e1a8 on behalf of 4577
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4577): processing updated download 165, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42910b28 on behalf of 4577
,I/LGDrmService( 4577): _DRM_ServiceGet() : Bind lgdrm service
,D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
V/DownloadManager( 4577): processing updated download 166, status: 192
D/DownloadManager( 4577): DB Update : current_bytes 383
,D/DownloadManager( 4577): DB Update : total_bytes 383
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=166:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4291f470 on behalf of 4577
,W/BaseRuntimeLoader( 5030): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5030): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5030): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5030): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/LFT     ( 4577): notifyThroughDatabase after updateDB  id :  166, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4577): notifyThroughDatabase start id : 166 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42922210 on behalf of 4577
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42925848 on behalf of 4577
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/DownloadManager( 4577): DB Update : numfailed 0
D/DownloadManager( 4577): DB Update : method 0
D/DownloadManager( 4577): DB Update : lastmod 1449832373699
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/10152015-sms-metadata.txt
D/DownloadManager( 4577): DB Update : status 200
V/DownloadManager( 4577): processing updated download 165, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/ContactAccountLoggerTas( 2609): canRun() : Opted Out
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4292a110 on behalf of 4577
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4577): Download 166 finished with status SUCCESS
D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/Search.GservicesUpdateTask( 2609): Updating Gservices keys
V/DownloadManager( 4577): processing updated download 166, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=166:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@4292cae8 on behalf of 4577
D/DownloadManager( 4577): checkStatusUpdate current status 192 is changed to 200
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
D/DownloadManager( 4577): checkStatusUpdate return true mID : mStatus = 166 : 200 => 200
D/wpa_supplicant( 4256): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42930430 on behalf of 4577
V/DownloadManager( 4577): processing updated download 165, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42933b90 on behalf of 4577
,I/ContactAccountLoggerTas( 2609): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2609): canRun() : Opted Out
,W/Search.LoginHelper( 2609): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2609): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2609): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2609): canRun() : Opted Out
,I/CheckinService( 1945): Checking schedule, now: 1449832373795 next: 1450409769587
,I/CheckinService( 1945): active receiver: disabled
,I/SystemUpdateService( 1945): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1945): onCreate
,D/SystemUpdateService( 1945): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/dalvikvm( 1535): null clazz in OP_INSTANCE_OF, single-stepping
,D/GCM     ( 1535): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1535): GC_EXPLICIT freed 1265K, 28% free 17911K/24832K, paused 1ms+3ms, total 25ms
,I/ActivityManager(  965): Killing 4853:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
D/SystemEventReceiver( 1945): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1945): Updating ocr activity enabled=false
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
I/SystemUpdateService( 1945): cancelUpdate (empty URL)
I/GCoreUlr( 1424): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/SystemUpdateService( 1945): active receiver: disabled
,D/SystemUpdateService( 1945): onDestroy
,I/GCoreUlr( 1424): DispatchingService.onCreate()
,I/GCoreUlr( 1424): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
W/ActivityThread( 4577): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DownloadManager( 4577): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4577): Content-Disposition: null
V/DownloadManager( 4577): Content-Length: -1
V/DownloadManager( 4577): Content-Location: null
V/DownloadManager( 4577): Content-Type: text/plain
V/DownloadManager( 4577): ETag: null
V/DownloadManager( 4577): Transfer-Encoding: chunked
V/DownloadManager( 4577): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4577): Min update size = 16384
V/DownloadManager( 4577): getting filename from uri
I/DownloadManager( 4577): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
,V/DownloadManager( 4577): keeping extension
V/DownloadManager( 4577): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a2aba8 on behalf of 4577
,D/DownloadManager( 4577): DB Update : title 08202014-metadata.txt
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4577): DB Update : total_bytes -1
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a2d728 on behalf of 4577
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
V/DownloadManager( 4577): processing updated download 165, status: 192
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=165:192
D/DownloadManager( 4577): DB Update : current_bytes 384
,D/DownloadManager( 4577): DB Update : total_bytes 384
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a39dd0 on behalf of 4577
V/LFT     ( 4577): notifyThroughDatabase after updateDB  id :  165, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4577): notifyThroughDatabase start id : 165 name : /cache/08202014-metadata.txt status : 200
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a3bd90 on behalf of 4577
,D/DownloadManager( 4577): DB Update : numfailed 0
D/dalvikvm( 1535): GC_EXPLICIT freed 134K, 29% free 17878K/24832K, paused 2ms+3ms, total 24ms
,D/DownloadManager( 4577): DB Update : method 0
D/DownloadManager( 4577): DB Update : lastmod 1449832374026
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4577): DB Update : status 200
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a3ed30 on behalf of 4577
,I/DownloadManager( 4577): Download 165 finished with status SUCCESS
,V/DownloadManager( 4577): DownloadService onDestroy
I/ActivityManager(  965): Killing 2926:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 3659): Removing dead content provider:android.content.ContentProviderProxy@42860678
I/GCoreUlr( 1424): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1424): Unbound from all location providers
,I/GCoreUlr( 1424): DispatchingService.onDestroy()
,I/GCoreUlr( 1424): Unbound from all location providers
,D/dalvikvm( 1945): GC_EXPLICIT freed 727K, 22% free 19448K/24832K, paused 2ms+3ms, total 35ms
,D/dalvikvm(  965): GC_EXPLICIT freed 1273K, 49% free 29451K/57228K, paused 3ms+7ms, total 97ms
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 166; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a44598 on behalf of 4970
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 166; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a47e30 on behalf of 4970
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4577): initiating download with UID 10003
,V/DownloadManager( 4577): DownloadService onCreate
,I/DownloadManager( 4577): in removeSpuriousFiles
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a4cf08 on behalf of 4577
I/DownloadManager( 4577): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 4577): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
,I/DownloadManager( 4577): in trimDatabase
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a4eaa0 on behalf of 4577
D/GCM     ( 1535): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a51038 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 165; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a55bf0 on behalf of 4970
,V/DownloadManager( 4577): processing inserted download 165
,V/DownloadManager( 4577): processing inserted download 166
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 165; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a5b490 on behalf of 4970
V/DownloadManager( 4577): processing inserted download 167
V/LFT     ( 4577): isReadyToDownload mId, mStatus=167:190
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a5ca50 on behalf of 4577
,D/DownloadManager( 4577): DB Update : status 192
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a5ecd0 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a60ed0 on behalf of 4577
,I/DownloadManager( 4577): Download 167 starting
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4577): initiating download with UID 10003
,V/DownloadManager( 4577): processing updated download 167, status: 192
I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/LFT     ( 4577): isReadyToDownload mId, mStatus=167:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4577): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a70250 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a72a60 on behalf of 4577
,V/DownloadManager( 4577): processing updated download 167, status: 192
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=167:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a74e18 on behalf of 4577
V/DownloadManager( 4577): processing inserted download 168
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:190
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4577): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4577): Content-Disposition: null
V/DownloadManager( 4577): Content-Length: -1
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a78078 on behalf of 4577
V/DownloadManager( 4577): Content-Location: null
V/DownloadManager( 4577): Content-Type: text/plain
,V/DownloadManager( 4577): ETag: null
V/DownloadManager( 4577): Transfer-Encoding: chunked
V/DownloadManager( 4577): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4577): Min update size = 16384
,V/DownloadManager( 4577): getting filename from uri
D/DownloadManager( 4577): DB Update : status 192
I/DownloadManager( 4577): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
,V/DownloadManager( 4577): keeping extension
,V/DownloadManager( 4577): target file: /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a7b090 on behalf of 4577
,D/DownloadManager( 4577): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4577): DB Update : total_bytes -1
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a7f058 on behalf of 4577
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a7f288 on behalf of 4577
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/LGDRM   (  275): [DRM] Part_DetectType() : Buffer contains XML Prologue
,D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,I/DownloadManager( 4577): Download 168 starting
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4577): processing updated download 167, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=167:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4577): DB Update : current_bytes 13383
,D/DownloadManager( 4577): DB Update : total_bytes 13383
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a8e528 on behalf of 4577
,V/LFT     ( 4577): notifyThroughDatabase after updateDB  id :  167, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4577): notifyThroughDatabase start id : 167 name : /cache/10152015-sms-blacklist.txt status : 200
V/DownloadManager( 4577): processing updated download 168, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a93da0 on behalf of 4577
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a93bd8 on behalf of 4577
D/DownloadManager( 4577): DB Update : numfailed 0
D/DownloadManager( 4577): DB Update : method 0
,D/DownloadManager( 4577): DB Update : lastmod 1449832374495
D/DownloadManager( 4577): DB Update : mimetype text/plain
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4577): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4577): DB Update : status 200
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a97190 on behalf of 4577
,V/DownloadManager( 4577): processing updated download 168, status: 192
,I/DownloadManager( 4577): Download 167 finished with status SUCCESS
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42a9a030 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 167; sort is lastmod DESC.
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42aa2cf8 on behalf of 4970
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42aa95a8 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 167; sort is lastmod DESC.
V/DownloadManager( 4577): processing updated download 168, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42aae3f0 on behalf of 4970
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42aaf740 on behalf of 4577
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4970): Update downloaded, starting installation
,I/UpdateFetcherService( 4970): Started installation
,D/DownloadManager( 4577): DB Update : deleted 1
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42ac4e98 on behalf of 4577
,D/DownloadManager( 4577): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4577): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 4577): processing updated download 168, status: 192
,V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b04fd0 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b074f0 on behalf of 4577
,V/DownloadManager( 4577): processing updated download 168, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b094f0 on behalf of 4577
,I/DownloadManager( 4577): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4577): Content-Disposition: null
,V/DownloadManager( 4577): Content-Length: -1
V/DownloadManager( 4577): Content-Location: null
V/DownloadManager( 4577): Content-Type: text/plain
V/DownloadManager( 4577): ETag: null
V/DownloadManager( 4577): Transfer-Encoding: chunked
V/DownloadManager( 4577): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4577): Min update size = 16384
,V/DownloadManager( 4577): getting filename from uri
I/DownloadManager( 4577): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
V/DownloadManager( 4577): keeping extension
,V/DownloadManager( 4577): target file: /cache/08202014-pins.txt
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b0d000 on behalf of 4577
,D/DownloadManager( 4577): DB Update : title 08202014-pins.txt
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4577): DB Update : total_bytes -1
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4577): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b0fdf0 on behalf of 4577
,V/DownloadManager( 4577): processing updated download 168, status: 192
D/DownloadManager( 4577): transferData threadNum : -1
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b1af38 on behalf of 4577
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): DB Update : current_bytes 32768
,V/DownloadManager( 4577): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b20198 on behalf of 4577
,D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): transferData threadNum : -1
,D/DownloadManager( 4577): DB Update : current_bytes 39938
V/DownloadManager( 4577): processing updated download 168, status: 192
,D/DownloadManager( 4577): DB Update : total_bytes 39938
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b23ce0 on behalf of 4577
V/LFT     ( 4577): notifyThroughDatabase after updateDB  id :  168, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4577): notifyThroughDatabase start id : 168 name : /cache/08202014-pins.txt status : 200
V/DownloadManager( 4577): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b26110 on behalf of 4577
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b27d48 on behalf of 4577
D/DownloadManager( 4577): DB Update : numfailed 0
D/DownloadManager( 4577): DB Update : method 0
D/DownloadManager( 4577): DB Update : lastmod 1449832374602
D/DownloadManager( 4577): DB Update : mimetype text/plain
D/DownloadManager( 4577): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4577): DB Update : status 200
,V/DownloadManager( 4577): processing updated download 168, status: 192
V/LFT     ( 4577): isReadyToDownload mId, mStatus=168:192
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b2ab20 on behalf of 4577
D/DownloadManager( 4577): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4577): checkStatusUpdate return true mID : mStatus = 168 : 200 => 200
,I/DownloadManager( 4577): Download 168 finished with status SUCCESS
,V/DownloadManager( 4577): DownloadService onDestroy
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 168; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b2f4a8 on behalf of 4970
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 168; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b32b68 on behalf of 4970
,W/ContextImpl( 4970): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4970): Update downloaded, starting installation
,I/UpdateFetcherService( 4970): Started installation
,D/DownloadManager( 4577): DB Update : deleted 1
,V/DownloadManager( 4577): DownloadService onCreate
,I/DownloadManager( 4577): in removeSpuriousFiles
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b367c0 on behalf of 4577
,I/DownloadManager( 4577): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
I/DownloadManager( 4577): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
V/DownloadManager( 4577): DownloadService onStartCommand
,V/DownloadManager( 4577): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4577): in trimDatabase
V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b39568 on behalf of 4577
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b3a588 on behalf of 4577
,V/DownloadManager( 4577): processing inserted download 165
,D/DownloadManager( 4577): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 4577): processing inserted download 168
,D/DownloadManager( 4577): deleteFileIfExists() deleting /cache/08202014-pins.txt
,V/DownloadManager( 4577): DownloadService onDestroy
I/ConfigUpdateInstallReceiver(  965): Not installing, new version is <= current version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV2    ( 4718): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Killing 3659:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 4100:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  965): Killing 4908:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3,
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV2    ( 3709): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,V/ConfigFetchTask( 1945): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Uv8Xyt838j9zuyRJYvXZIUbOWboMN6_IBUCj8XBMD7NQdRnSXVdE1wgqPwNwiXRdKe8oDStmI2CLU3v2q_y6e6BL8AD1rBzBtmJMQDv_NUS1O4P93MsUykta9jlV2QsumYF7cFPkrzL-xkZW2vMzL0GdpmHfgtrbGqbLoFfPOgUAwuEJqXAqo2nWmd70ZS6eQSaW4DGJkAvtQ1HjmeJ31nybMjwRYYqP25STQuPA2TT-7C9pY
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832380029, nextTick: 60001, mDrawingTime: 2
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832380056, nextTick: 59974, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1945): Using platform SSLCertificateSocketFactory
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3569): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/ActivityManager(  965): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5140 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/SlideAside( 3569): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
E/SlideAside( 3569): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/SlideAside( 3569): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5140): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ConfigFetchTask( 1945): updating config table for com.google.android.gms
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 5140):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5140):  [AppBoxDatabaseHelper] construct
,I/AppUp4  ( 5140):  setFingerPrint start
,I/AppUp4  ( 5140):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5140):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5140):  beforefinger == newfinger no write in DB
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "sms"
,D/AppUp4:AppBoxApplication( 5140): AppBoxApplication onCreate()
,D/AppBoxBlacklist( 5140): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/PackageParser( 5140): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
,I/ConfigFetchService( 1945): fetch service done; releasing wakelock
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4:Utils( 5140): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 5140): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5140): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
,I/ConfigFetchService( 1945): stopping self
D/PackageParser( 5140): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,I/AppUp4:CustModeStarterReceiver( 5140): onReceive
D/AppUp4:CustFacade( 5140): Context : android.app.ReceiverRestrictedContext@42825218
D/AppUp4:CustFacade( 5140): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5140): isOpenOperator : true
,D/AppUp4:CustFacade( 5140): isPhone : true
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  965): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5168 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "smsto"
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HyLog   ( 5168): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5168): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5168): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LicenseContentProvider( 5168): start selecting data
W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5168): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/SIMObserver( 5168): simInfo1
,I/AppUp4:EulaManager( 5140): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5140): begin check event
D/AppUp4:Utils( 5140): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5140): Event For Nothing, skip.
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5181 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): Killing 4591:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): Killing 4617:com.android.mms/u0a35 (adj 15): empty #18
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/CountryDetector(  965): No listener is left
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5181): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5181): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5181): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/SystemConfig( 5181): BUILD Country: EU
,I/SystemConfig( 5181): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4685:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5197 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/VacuumService( 1535): Vacuum at: now=1449832380857 tag=VacuumService
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
D/WifiController(  965): battery changed pluggedType: 2
,I/SystemConfig( 5181): systemFeature RCS result false
,D/SystemConfig( 5181): refreshRcsSupport() :false
,V/GmsNetworkLocationProvi( 1424): DISABLE
,D/HyLog   ( 5197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5197): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/LocationManagerService(  965): remove 4318e1b0
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,D/dalvikvm(  965): GC_EXPLICIT freed 2559K, 49% free 29601K/57228K, paused 3ms+7ms, total 89ms
,I/ActivityManager(  965): Killing 4876:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2609): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5216 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5216): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5216): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5216): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,I/IcingCorporaProvider( 2609): UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1535): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/dalvikvm( 5216): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5216): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5216): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5216): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5216): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5216): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5216): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5216): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5216): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5216): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5216): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5216): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5216): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5216): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5216): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5216): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x0292
,I/dalvikvm( 5216): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5216): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b445b8 on behalf of 5216
,I/dalvikvm( 5216): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5216): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5216): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5216): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5216): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5216): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5216): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5216): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 5216): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5256 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/ActivityManager(  965): Killing 4343:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5256): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5256): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PeopleContactsSync( 1945): CP2 sync disabled
,W/Uploader( 1535): No account for auth token provided
,I/MediaCodecList( 5256): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5256): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5256): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5256): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5256): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5256): MmsConfig.loadMmsSettings
I/Babel   ( 5256): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5256): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5256): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5256): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5256): MmsConfig.loadFromResources
,W/Uploader( 1535):  no longer exists, so no auth token.
,E/Babel   ( 5256): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5256): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5256): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 5140): [getPackageName] uri : package:com.google.android.gms
V/LGRssiData( 5256): [loadRssi] File not exist 
,D/AppUp4  ( 5140): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 5140): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5256): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5256): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 5140): onReceive
V/TelephonyAutoProfiling( 5256): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5256): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5256): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:CustFacade( 5140): Context : android.app.ReceiverRestrictedContext@42825218
D/AppUp4:CustFacade( 5140): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5140): isOpenOperator : true
,D/AppUp4:CustFacade( 5140): isPhone : true
,I/LicenseContentProvider( 5168): start selecting data
,D/SIMObserver( 5168): simInfo1
,I/AppUp4:EulaManager( 5140): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5140): begin check event
D/AppUp4:Utils( 5140): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5140): Event For Nothing, skip.
,I/IcingCorporaProvider( 2609): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Uploader( 1535): No account for auth token provided
,D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ConfigFetchService( 1945): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/PackageBroadcastService( 1945): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{43280990 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ConfigFetchService( 1945): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1945): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1945): service connected
,W/ConfigFetchService( 1945): ConfigApi client is not connected. Falling back to defaultfetch interval.
,D/ConfigFetchService( 1945): ConfigApi connection successful.
,I/ConfigFetchService( 1945): stopping self
,I/Icing   ( 1945): updateResources: need to parse f{com.google.android.gms}
,W/Uploader( 1535): No account for auth token provided
,I/ActivityManager(  965): Killing 4718:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,W/Uploader( 1535): No account for auth token provided
,D/dalvikvm( 1945): GC_CONCURRENT freed 1805K, 21% free 19639K/24832K, paused 4ms+4ms, total 55ms
,I/IcingCorporaProvider( 2609): UpdateCorporaTask done [took 317 ms] updated apps [took 317 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5216): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 5216): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5216): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5216): VFY: replacing opcode 0x62 at 0x0037
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  965): battery changed pluggedType: 2
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1535): GC_EXPLICIT freed 1546K, 27% free 18151K/24832K, paused 2ms+5ms, total 35ms
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5216): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Finsky  ( 5216): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5216): Total arena pages for JIT: 11
,I/dalvikvm( 5216): Total arena pages for JIT: 12
I/dalvikvm( 5216): Total arena pages for JIT: 13
,I/dalvikvm( 5216): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5216): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5216): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5216): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5216): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1156): GC_CONCURRENT freed 2920K, 11% free 25451K/28544K, paused 3ms+3ms, total 58ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.448196 Y: -0.395660 Z: 9.744125 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448196 .y:-0.395660 .z:9.744125
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.445541 Y: -0.398087 Z: 9.764496 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445541 .y:-0.398087 .z:9.764496
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,W/PackageSettings(  965): Skipping PackageSetting{42cb6ba8 com.example.hello/10311} due to missing metadata
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8276 usec
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.444290 Y: -0.392319 Z: 9.759186 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444290 .y:-0.392319 .z:9.759186
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.457901 Y: -0.389893 Z: 9.744965 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457901 .y:-0.389893 .z:9.744965
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  581): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
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
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.442291 Y: -0.387497 Z: 9.755966 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442291 .y:-0.387497 .z:9.755966
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.454330 Y: -0.387772 Z: 9.773453 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454330 .y:-0.387772 .z:9.773453
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455170 Y: -0.372391 Z: 9.774734 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455170 .y:-0.372391 .z:9.774734
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.452469 Y: -0.379608 Z: 9.756790 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452469 .y:-0.379608 .z:9.756790
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44d431a8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  965): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8593450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455841 Y: -0.391190 Z: 9.749725 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455841 .y:-0.391190 .z:9.749725
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4256): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 4256): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4256): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4256): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,E/SlideAside( 3569): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{42865e68 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1872): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:13:4
,I/SlideAside( 3569): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
,D/WeatherAncestor( 1872): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:13:4
D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 413ms
D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832385299, nextTick: 54733, mDrawingTime: 1
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832385352, nextTick: 54679, mDrawingTime: 1
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
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
,D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/dalvikvm(  965): GC_EXPLICIT freed 1395K, 49% free 29647K/57228K, paused 10ms+12ms, total 201ms
D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 33, B = 33
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:13:5
,D/WeatherService( 1872): 2 : ACTION screen on
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1156): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 27, B = 27
,D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:13:5
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GsmSST  ( 1449): Emergency Service
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
,I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3}
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,I/LGImmersionVibrator(  965): Vibrator off
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43c7d1f0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 4256): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4256): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/UsbSettings( 2517): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/WifiController(  965): CMD_SCREEN_OFF 
D/WifiController(  965): shouldWifiStayAwake TRUE
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
V/UsbSettings( 2517): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2517): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2517): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1156): RESTART MSG
D/VolumeVibrator( 1156): clear
,D/wpa_supplicant( 4256): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{4301b310 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:13:5
,D/WeatherService( 1872): 2 : ACTION screen off
,D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:13:5
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,D/NfcService( 1474): NFC-C OFF
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  581): sns_pwr.c(320):releasing wakelock
,I/GAV4    ( 5256): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1535): onDestroy
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5216): [441] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5216): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832403567244154; DSPS: 5277070; Offset: 1449832242523848158
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832423568647323; DSPS: 5932476; Offset: 1449832242523847519
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832440044, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832440062, nextTick: 59968, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832443570190285; DSPS: 6587886; Offset: 1449832242523864602
,I/rmt_storage(  612): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb8d5a178
I/rmt_storage(  612): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  612): wakelock acquired: 1, error no: 42
,I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193958856)
,I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193958856) wakelock released: 1, error no: 0
I/rmt_storage(  612): 
I/rmt_storage(  612): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb8d5a178
,E/Diag_Lib(  691): [IMS_FATAL]| 2912 | 704 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832463580483923; DSPS: 7243583; Offset: 1449832242523873816
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832483581970165; DSPS: 7898992; Offset: 1449832242523864697
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832500044, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832500055, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832503583788491; DSPS: 8554412; Offset: 1449832242523851968
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832523585226504; DSPS: 9209819; Offset: 1449832242523855655
,I/jxcore-log( 4200): Connected to the server!
I/jxcore-log( 4200): 
,I/chromium( 4200): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832543586956652; DSPS: 9865236; Offset: 1449832242523846301
,D/wpa_supplicant( 4256): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 7 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4256): wlan0: BSS: Remove id 8 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4256): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 0c:bd:51:2b:c1:25]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832560043, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832560050, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832563588703364; DSPS: 10520653; Offset: 1449832242523853511
,D/dalvikvm( 2597): GC_CONCURRENT freed 7679K, 33% free 16868K/24832K, paused 3ms+1ms, total 39ms
,I/ActivityManager(  965): Killing 4835:com.lge.task/u0a43 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b69160 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832583590071481; DSPS: 11176058; Offset: 1449832242523848337
,D/dalvikvm( 2597): GC_CONCURRENT freed 1617K, 31% free 17298K/24832K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 2597): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2597): GC_FOR_ALLOC freed 1664K, 31% free 17250K/24832K, paused 24ms, total 24ms
,I/Mlt MonitorService( 2597): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832603591726578; DSPS: 11831472; Offset: 1449832242523855485
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832620048, nextTick: 59968, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832620058, nextTick: 59971, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832623593186050; DSPS: 12486880; Offset: 1449832242523850113
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832643594781146; DSPS: 13142292; Offset: 1449832242523858295
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832663596314316; DSPS: 13797702; Offset: 1449832242523865586
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1462): GC_CONCURRENT freed 1537K, 7% free 25440K/27280K, paused 16ms+2ms, total 44ms
,D/dalvikvm( 2597): GC_CONCURRENT freed 1935K, 31% free 17235K/24832K, paused 4ms+2ms, total 32ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832680042, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832680048, nextTick: 59977, mDrawingTime: 3
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x42bb2380: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1535): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1535): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1535): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1535): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1535): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5216): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5216): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5216): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5216): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5216): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5216): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5216): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5216): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5216): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5216): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832683597933058; DSPS: 14453115; Offset: 1449832242523866896
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832703599632789; DSPS: 15108531; Offset: 1449832242523857643
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832723601558460; DSPS: 15763954; Offset: 1449832242523860707
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832740038, nextTick: 59961, mDrawingTime: 13
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832740060, nextTick: 59969, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832743603209077; DSPS: 16419368; Offset: 1449832242523863374
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832763604789642; DSPS: 17074780; Offset: 1449832242523857025
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832783606370988; DSPS: 17730192; Offset: 1449832242523851457
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832800022, nextTick: 59976, mDrawingTime: 15
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832800063, nextTick: 59968, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832803608337803; DSPS: 18385616; Offset: 1449832242523865147
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832823610066285; DSPS: 19041033; Offset: 1449832242523854127
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832843611876226; DSPS: 19696452; Offset: 1449832242523863531
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832860018, nextTick: 59972, mDrawingTime: 19
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832860064, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832863613523770; DSPS: 20351866; Offset: 1449832242523863126
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832883615538555; DSPS: 21007292; Offset: 1449832242523863751
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832903617553026; DSPS: 21662718; Offset: 1449832242523864062
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832920015, nextTick: 60000, mDrawingTime: 12
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832920071, nextTick: 59938, mDrawingTime: 8
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832923619132080; DSPS: 22318130; Offset: 1449832242523856202
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832943621318115; DSPS: 22973562; Offset: 1449832242523844971
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832963622862847; DSPS: 23628972; Offset: 1449832242523863824
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832980022, nextTick: 60002, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449832980065, nextTick: 59963, mDrawingTime: 4
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449832983624175964; DSPS: 24284375; Offset: 1449832242523864685
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833003625819498; DSPS: 24939789; Offset: 1449832242523860270
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833023627668813; DSPS: 25595210; Offset: 1449832242523848013
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833040032, nextTick: 59993, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833040037, nextTick: 59993, mDrawingTime: 2
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833043629207347; DSPS: 26250620; Offset: 1449832242523860668
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833063630556403; DSPS: 26906024; Offset: 1449832242523866950
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833083634798634; DSPS: 27561523; Offset: 1449832242523867238
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/Ads     ( 1945): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833100046, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833100059, nextTick: 59969, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833103636137377; DSPS: 28216927; Offset: 1449832242523863208
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833123636566692; DSPS: 28872301; Offset: 1449832242523865276
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833143637694392; DSPS: 29527698; Offset: 1449832242523863826
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833160045, nextTick: 59966, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833160058, nextTick: 59971, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833163639339854; DSPS: 30183112; Offset: 1449832242523861339
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833183641539117; DSPS: 30838544; Offset: 1449832242523863336
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833203642385724; DSPS: 31493932; Offset: 1449832242523855451
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833220043, nextTick: 59977, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833220050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833223650974363; DSPS: 32149573; Offset: 1449832242523868651
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833243652565761; DSPS: 32804985; Offset: 1449832242523873135
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833263653615545; DSPS: 33460380; Offset: 1449832242523854803
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833280074, nextTick: 59956, mDrawingTime: 3
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833280075, nextTick: 59958, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833283657748870; DSPS: 34115875; Offset: 1449832242523868255
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833303659526727; DSPS: 34771294; Offset: 1449832242523845575
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833323661258647; DSPS: 35426710; Offset: 1449832242523868511
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833340041, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833340047, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833343662130202; DSPS: 36082099; Offset: 1449832242523855056
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833363666869725; DSPS: 36737614; Offset: 1449832242523864354
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833383668491488; DSPS: 37393027; Offset: 1449832242523868686
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833400036, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833400053, nextTick: 59978, mDrawingTime: 1
,D/GCM     ( 1535): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1945): Aggregate from 1449832370444 (log), 1449831602437 (data)
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833403669340178; DSPS: 38048415; Offset: 1449832242523862884
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833423671220641; DSPS: 38703837; Offset: 1449832242523851257
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833443672901049; DSPS: 39359252; Offset: 1449832242523853198
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833460024, nextTick: 59997, mDrawingTime: 7
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833460075, nextTick: 59955, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833463674443385; DSPS: 40014662; Offset: 1449832242523869655
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833483681966503; DSPS: 40670269; Offset: 1449832242523854931
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833503683151755; DSPS: 41325668; Offset: 1449832242523849998
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833520047, nextTick: 59966, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833520059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833523684742268; DSPS: 41981080; Offset: 1449832242523853597
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833543685877157; DSPS: 42636477; Offset: 1449832242523859335
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833563687227722; DSPS: 43291881; Offset: 1449832242523867127
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833580044, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833580048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833583688597714; DSPS: 43947286; Offset: 1449832242523863828
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833603689686561; DSPS: 44602682; Offset: 1449832242523854042
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833623690925980; DSPS: 45258083; Offset: 1449832242523842240
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833640045, nextTick: 59967, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833640058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833643692730973; DSPS: 45913502; Offset: 1449832242523846696
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833663694305340; DSPS: 46568913; Offset: 1449832242523864667
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833683694730541; DSPS: 47224287; Offset: 1449832242523862622
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833700039, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833700045, nextTick: 59983, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833703696226106; DSPS: 47879696; Offset: 1449832242523862825
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833723697784640; DSPS: 48535107; Offset: 1449832242523864963
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833743698628850; DSPS: 49190495; Offset: 1449832242523854681
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833760043, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833760049, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833763700967646; DSPS: 49845932; Offset: 1449832242523843623
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833783702550451; DSPS: 50501343; Offset: 1449832242523870032
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833803704240339; DSPS: 51156759; Offset: 1449832242523850935
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833820044, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833820056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833823709199185; DSPS: 51812281; Offset: 1449832242523865934
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833843711706886; DSPS: 52467723; Offset: 1449832242523871193
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833863713170004; DSPS: 53123131; Offset: 1449832242523869467
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833880045, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833880049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833883716818746; DSPS: 53778611; Offset: 1449832242523856100
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833903718365404; DSPS: 54434022; Offset: 1449832242523846362
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833923719988157; DSPS: 55089435; Offset: 1449832242523851683
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833940038, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449833940046, nextTick: 59982, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833943723271275; DSPS: 55744902; Offset: 1449832242523869420
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833963728376840; DSPS: 56400430; Offset: 1449832242523848032
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449833983729962613; DSPS: 57055842; Offset: 1449832242523846891
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834000036, nextTick: 59965, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834000057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834003731160263; DSPS: 57711241; Offset: 1449832242523854355
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834023732329422; DSPS: 58366639; Offset: 1449832242523863846
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834043733876289; DSPS: 59022050; Offset: 1449832242523854317
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834060025, nextTick: 59993, mDrawingTime: 9
,I/ProcessStatsService(  965): Prepared write state in 91ms
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834060117, nextTick: 59914, mDrawingTime: 1
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  965): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-10-09.bin
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834063735478781; DSPS: 59677462; Offset: 1449832242523869895
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b4a030 on behalf of 1945
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b4dde8 on behalf of 1945
,V/DownloadManager( 4577): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4577): created cursor android.database.sqlite.SQLiteCursor@42b514a0 on behalf of 1945
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834083739612575; DSPS: 60332958; Offset: 1449832242523853298
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834103741940277; DSPS: 60988394; Offset: 1449832242523861664
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834120032, nextTick: 59961, mDrawingTime: 16
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449834120058, nextTick: 59967, mDrawingTime: 3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834123743710268; DSPS: 61643812; Offset: 1449832242523861636
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834143744233595; DSPS: 62299189; Offset: 1449832242523866164
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1449834163749343691; DSPS: 62954717; Offset: 1449832242523849307
,TIME-OUT KILL (timeout was 1800000ms)
```
