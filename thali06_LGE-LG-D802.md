#### Test 50650278dbf8a2a_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1948): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1948): launchTask
W/dalvikvm( 1948): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.vision from APK com.google.android.gms
V/ConfigFetchTask( 1948): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WSEkJCbPBBYsy8vSvh9z0-5YWUjkmDxRkqQZvq81qcI-1YYF52IwdcbicdtxgUWvMJmpkT6UTUl79qCVvYQTbiPDQnwy5Tl8hzJKRaD7zbQt1IX7XBx_GF2Br5v7F983OgwPZKG4kTQrNcb6HAHoJ7FhOlXdaPjhhcluHatpRxm_YqRq9LscpBmPuAYay7Y-v1Qtr0jLdk3S-xQqisasZVC_-ASf7VteRYH-YpCNmEOcwkqzU
D/Vision  ( 1948): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1948): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1948): No vision deps
I/GoogleURLConnFactory( 1948): Using platform SSLCertificateSocketFactory
W/GAV2    ( 4082): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3402:com.google.android.music:main/u0a107 (adj 15): empty #17
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1948): CP2 sync disabled
F/ActivityManager(  966): Service ServiceRecord{43322c48 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432250b8 3402:com.google.android.music:main/u0a107} not same as in map: null
I/dalvikvm( 1948): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1948): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1948): VFY: replacing opcode 0x6e at 0x000e
F/ActivityManager(  966): Service ServiceRecord{43202620 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432250b8 3402:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
E/DataScheduler( 1948): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =0
D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1948): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1948): fetch service done; releasing wakelock
I/ConfigFetchService( 1948): stopping self
W/BaseAppContext( 1948): Using Auth Proxy for data requests.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 4123): 
D/AndroidRuntime( 4123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4123): CheckJNI is OFF
D/dalvikvm( 4123): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4123): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4123): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4123): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4123): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4123): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1948): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 1948): GC_CONCURRENT freed 1614K, 26% free 18434K/24832K, paused 4ms+5ms, total 44ms
D/dalvikvm( 1948): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/Icing   ( 1948): Loaded CLD2 Version V2.0 - 20141016
D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
E/memtrack( 4123): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4123): failed to load memtrack module: -2
I/Icing   ( 1948): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4123): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4123
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (149 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  966): startService SlideAside
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{432603b8 stackId=1, 2 tasks}
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4123): Shutting down VM
D/UsbSettingsControl( 2586): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2586): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/SlideAside( 3572): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4123): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+1ms, total 3ms
I/SlideAside( 3572): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4160 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 3572): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  269): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4160): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
V/WebViewChromium( 4160): Binding Chromium to the background looper Looper (main, tid 1) {42874188}
I/chromium( 4160): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4160): Initializing chromium process, renderers=0
W/chromium( 4160): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4160): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4160): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4160): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4160): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4160): Remote Branch: 
I/Adreno-EGL( 4160): Local Patches: 
I/Adreno-EGL( 4160): Reconstruct Branch: 
I/dalvikvm( 4160): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4160): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4160): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4160): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4160): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4160): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4160): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4160): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4160): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4160): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4160): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4160): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4160): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4160): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4160): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4160): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4160): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4160): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4160): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4160): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4160): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4160): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4160): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4160): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4160): Enabling debug mode 0
,W/AwContents( 4160): nativeOnDraw failed; clearing to background color.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +327ms
,W/AwContents( 4160): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  966): IME STATUS OFF
,I/ActivityManager( 4160): Timeline: Activity_idle id: android.os.BinderProxy@42875868 time:105184
,D/JsMessageQueue( 4160): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4160): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42879948
,D/dalvikvm( 4160): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42879948
,D/jxcore_app_log( 4160): JniHelper::setJavaVM(0x41736838), pthread_self() = 1639029520
,D/JX-Cordova( 4160): jxcore cordova android initializing
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3} time:105602
,D/UsbSettings( 2586): [AUTORUN] onStop()
D/ActivityManager(  966): no-history finish of ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{431d2b08 ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4160): GC_CONCURRENT freed 2776K, 13% free 21842K/24832K, paused 3ms+1ms, total 42ms
,D/dalvikvm( 4160): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 132K, 13% free 21823K/24832K, paused 26ms, total 27ms
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 302K, 12% free 21889K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 23.688MB for 144892-byte allocation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/dalvikvm( 4160): GC_FOR_ALLOC freed 267K, 13% free 21926K/24976K, paused 24ms, total 24ms
I/dalvikvm-heap( 4160): Grow heap (frag case) to 23.793MB for 217334-byte allocation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 369K, 13% free 22000K/25192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 23.968MB for 325996-byte allocation
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 570K, 14% free 22122K/25512K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 24.243MB for 488990-byte allocation
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 869K, 15% free 22298K/25992K, paused 38ms, total 39ms
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 24.649MB for 733480-byte allocation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 1288K, 16% free 22556K/26712K, paused 32ms, total 32ms
,D/dalvikvm( 4160): GC_CONCURRENT freed 1676K, 15% free 22928K/26712K, paused 1ms+3ms, total 53ms
D/dalvikvm( 4160): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 4160): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 4160): GC_FOR_ALLOC freed 376K, 15% free 22886K/26712K, paused 28ms, total 28ms
I/dalvikvm-heap( 4160): Grow heap (frag case) to 26.096MB for 1650320-byte allocation
D/dalvikvm( 4160): GC_CONCURRENT freed 1589K, 18% free 23447K/28324K, paused 2ms+2ms, total 28ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4160): GC_FOR_ALLOC freed 1468K, 17% free 23544K/28324K, paused 30ms, total 30ms
I/dalvikvm-heap( 4160): Grow heap (frag case) to 27.527MB for 2475476-byte allocation
D/dalvikvm( 4160): GC_CONCURRENT freed 265K, 16% free 26009K/30744K, paused 2ms+2ms, total 48ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4160): GC_FOR_ALLOC freed 4367K, 21% free 24512K/30744K, paused 29ms, total 30ms
I/dalvikvm-heap( 4160): Grow heap (frag case) to 29.653MB for 3713210-byte allocation
D/dalvikvm( 4160): GC_CONCURRENT freed 3019K, 26% free 25502K/34372K, paused 2ms+4ms, total 55ms
D/dalvikvm( 4160): GC_FOR_ALLOC freed 493K, 26% free 25447K/34372K, paused 22ms, total 22ms
W/jxcore-log( 4160): Initializing JXcore engine
W/jxcore-log( 4160): JXcore engine is ready
,D/dalvikvm( 4160): GC_CONCURRENT freed 345K, 19% free 28074K/34372K, paused 2ms+1ms, total 28ms
D/dalvikvm( 4160): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/jxcore-log( 4160): Starting JXcore engine
W/jxcore-log( 4160): Platform android
W/jxcore-log( 4160): 
W/jxcore-log( 4160): Process ARCH arm
W/jxcore-log( 4160): 
,I/jxcore-log( 4160): JXcore Cordova bridge is ready!
I/jxcore-log( 4160): 
,W/jxcore-log( 4160): JXcore engine is started
,I/chromium( 4160): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4160): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4160): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4082): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4160): Toggling radios to true
I/jxcore-log( 4160): 
,D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e3a1e8:true
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  966): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  966): Message: 1
,D/BluetoothManagerService(  966): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  966): New client listening to asynchronous messages
D/WifiService(  966): setWifiEnabled: true pid=4160, uid=10304
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1211): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116316256)( 1211): onCreate
,D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44965a98:true
,D/BluetoothAdapterState( 1211): make
I/bluedroid( 1211): init ready=0
,D/bt-btif ( 1211): in initialized:0
I/BluetoothAdapterState( 1211): Entering OffState
D/bt-btif ( 1211): root, p->name:Bluedroid, child/value:0x606706f8, bytes:160
,D/bt-btif ( 1211): p->used:0, type:0, p->flag:0
,I/bte_conf( 1211): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,D/btif_config_util( 1211): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/BT_PROF ( 1211): set profile trace flags 0x0
,D/BTIF_CORE( 1211): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1211):  [BTUI] Load_abtddress
D/bt-btif ( 1211): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
,D/bt-btif ( 1211): Got prior random BDA 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4225): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4225): [BTUI] bluetooth_load_bdaddress
,D/lge_bdaddr_loader( 4225): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,E/lge_bdaddr_loader( 4225): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4225): [BTUI] bdaddr_loader ::: END
,D/WifiStateMachine(  966): setting operational mode to 1
,D/WifiStateMachine(  966): handleMessage: E msg.what=131083
,D/WifiStateMachine(  966): processMsg: InitialState
,E/WifiHW  (  966): Wifi MAC Address = 34:fc:ef:de:0a:e2
E/WifiHW  (  966): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  966): ": cur_etheraddr=34:fc:ef:de:0a:e2
,I/jxcore-log( 4160): Radios toggled
I/jxcore-log( 4160): 
,D/SoftapController(  265): Softap fwReload - Ok
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4160): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4160): 
D/WifiService(  966): disconnect pid=4160, uid=10304
,D/WifiService(  966): reconnect pid=4160, uid=10304
I/jxcore-log( 4160): Perf Test app loaded loaded
I/jxcore-log( 4160): 
D/CommandListener(  265): Setting iface cfg
,D/CommandListener(  265): Trying to bring down wlan0
,D/WifiMonitor(  966): WifiMonitorSingleton gotten
,I/Choreographer( 4160): Skipped 68 frames!  The application may be doing too much work on its main thread.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/bluedroid( 1211): get_profile_interface socket
I/GKI_LINUX( 1211): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/bt-btif ( 1211): btif_get_adapter_property 2
I/bt-btif ( 1211): btif_get_adapter_property 1
D/bt-btif ( 1211): btif task starting
D/bt-btif ( 1211): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1211): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1211): execute storage request event : 3
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService(1116316256)( 1211): onBind
I/bt-btif ( 1211): execute storage request event : 3
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1211): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  966): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  966): Message: 40
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  966): Bluetooth Adapter name changed to Thali Test's G2
I/bluedroid( 1211): config_hci_snoop_log
D/BluetoothManagerService(  966): Stored Bluetooth name: Thali Test's G2
D/BluetoothManagerService(  966): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  966): Broadcasting onBluetoothServiceUp() to 8 receivers.
,I/jxcore-log( 4160): check test folder
I/jxcore-log( 4160): 
,D/dalvikvm( 1211): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/jxcore-log( 4160): found test : ./testFindPeers.js
I/jxcore-log( 4160): 
,D/BluetoothAdapterService(1116316256)( 1211): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1211): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1211): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1211): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  966): Message: 60
D/BluetoothAdapterService(1116316256)( 1211): processStart()
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  966): Bluetooth State Change Intent: 10 -> 11
,D/LGBluetoothAPIService( 1155): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116316256)( 1211): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1211): make
D/BluetoothAdapterService( 1211): setAdapterService(): set to: null
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/LGBluetoothServiceAdapter( 1211): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
,D/LGBluetoothServiceAdapter( 1211): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 1211): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1211): StableState(): Entering Off State
,D/LGBluetoothXmlHandler( 2586): dvice configuraion start
,I/jxcore-log( 4160): found test : ./testSendData.js
I/jxcore-log( 4160): 
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
D/LGBluetoothXmlHandler( 2586): startDocument!
D/LGBluetoothXmlHandler( 2586): startElement - elet = Device
D/LGBluetoothXmlHandler( 2586): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2586): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2586): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2586): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2586): endDocument!
W/BluetoothAdapterService( 1211): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
V/BluetoothPbapReceiver( 1211): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1211): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1211): ***********state = 11
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
D/BluetoothHeadset(  966): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BrcmHeadsetService( 1211): Received start request. Starting profile...
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.a2dp.A2dpService
,I/Brcm_BluetoothHeadsetServiceJni( 1211): classInitNative: succeeds
,D/HeadsetStateMachine( 1211): make
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothPermissionRequest( 2586): onReceive
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.hid.HidService
D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44c98ef0:true
D/LGBluetoothResetSettingReceiver( 2586): [BTUI] Loading JNI Library
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
E/BluetoothSettings_JNI( 2586): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.hdp.HealthService
D/LGBluetoothResetSettingReceiver( 2586): return without doing reset settings.
I/LGBluetoothHeadsetServiceJni( 1211): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 1211): Version 1.5
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
I/bluedroid( 1211): get_profile_interface handsfree
I/bt-btif ( 1211): btif_hf_get_interface
I/bt-btif ( 1211): init
D/bt-btif ( 1211): btif_enable_service: current services:0x40
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.pan.PanService
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
V/AudioPolicyService(  272): getOutput()
V/AudioPolicyManagerBase(  272): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  272): getOutput() returns output 2
V/AudioSystem( 1211): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  272): registerClient() client 0xb79ffa00, pid 1211
V/AudioFlinger(  272): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  272): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  272): thread 0xb2768008 type 0 TID 848 waking up
V/AudioFlinger(  272): thread 0xb25fd008 type 0 TID 1001 waking up
V/AudioFlinger(  272): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  272): processConfigEvents() remaining events 1
V/AudioFlinger(  272): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  272): processConfigEvents() remaining events 1
V/AudioFlinger(  272): PlaybackThread::audioConfigChanged_l, thread 0xb2768008, event 0, param 0
V/AudioSystem(  272): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  272): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  966): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  966): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1211): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1211): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1607): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1607): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  272): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  272): PlaybackThread::audioConfigChanged_l, thread 0xb25fd008, event 0, param 0
V/AudioSystem(  272): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  272): ioConfigChanged() opening already existing output! 3
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.map.BluetoothMapService
V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 3
V/AudioFlinger(  272): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1607): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1607): ioConfigChanged() opening already existing output! 3
V/AudioSystem(  966): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  966): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1211): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1211): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1211): samp,leRate 0, channelMask 0x1, format 1
V/AudioTrack( 1211): streamType 8
V/AudioTrack( 1211): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1211): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioPolicyService(  272): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  272): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1211): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/HeadsetStateMachine( 1211): Enter Disconnected: -2
D/HeadsetPhoneState( 1211): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1211): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1211): [BTUI] change sampling rate to 8000 when device is disconnected
E/AudioSystem( 1211): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  272): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1211
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
V/SRS_Proc(  272): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  272): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  272): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
D/BluetoothA2dp(  966): Proxy object connected
D/A2dpService( 1211): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1211): classInitNative: succeeds
D/A2dpStateMachine( 1211): make
I/bluedroid( 1211): get_profile_interface a2dp
I/bt-btif ( 1211): btif_av_get_interface
I/bt-btif ( 1211): init
I/bt-btif ( 1211): ## A2DP START MEDIA TASK ##
W/BluetoothAdapterService( 1211): Starting service com.android.bluetooth.gatt.GattService
I/GKI_LINUX( 1211): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1211): UIPC_Init
I/bt-btif ( 1211): ### uipc_main_init ###
D/bt-btif ( 1211): UIPC_Open : ch_id 0, p_cback 60b05b25
I/bt-btif ( 1211): SETUP CHANNEL SERVER 0
I/bt-btif ( 1211): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1211): created socket fd 69
I/bt-btif ( 1211): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1211): UIPC SEND WAKE UP
I/bt-btif ( 1211): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1211): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1211): btif_enable_service: current services:0x48
D/bt-btif ( 1211): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1211): ## ON A2DP IDLE ##
D/bt-btif ( 1211): UIPC_Close : ch_id 1
I/bt-btif ( 1211): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1211): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1211): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/BluetoothAVRCP1.3ServiceJni( 1211): classInitNativeAVRCP
D/A2dpStateMachine( 1211): Enter Disconnected: -2
V/Avrcp   ( 1211): make
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
W/BluetoothAdapterService( 1211): Starting service com.broadcom.bt.service.sap.SapService
D/LGBluetoothAvrcpManager( 1211): [BTUI] initAvcrpManager
E/BluetoothAdapterService( 1211): File transfer profiels supported!!
D/LGBluetoothAvrcpManager( 1211): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1211): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1211): initNativeAVRCP
I/bluedroid( 1211): get_profile_interface avrcp
I/bt-btif ( 1211): btif_rc_get_interface
I/bt-btif ( 1211): ## init ##
W/BluetoothAdapterService( 1211): Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
I/BluetoothHidServiceJni( 1211): classInitNative: succeeds
D/HidService( 1211): Received start request. Starting profile...
I/bluedroid( 1211): get_profile_interface hidhost
I/bt-btif ( 1211): btif_hh_get_interface
I/bt-btif ( 1211): init
D/bt-btif ( 1211): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
I/BluetoothHealthServiceJni( 1211): classInitNative: succeeds
D/HealthService( 1211): Received start request. Starting profile...
I/bluedroid( 1211): get_profile_interface health
I/bt-btif ( 1211): btif_hl_get_interface
I/bt-btif ( 1211): init
D/bt-btif ( 1211): Process name (droid.bluetooth)
D/bt-btif ( 1211): btif_hl_soc_thread_init
D/bt-btif ( 1211): create_thread: entered
D/bt-btif ( 1211): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1211): classInitNative: succeeds
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/HeadsetStateMachine( 1211): Proxy object connected
I/BluetoothPanServiceJni( 1211): classInitNative(L105): succeeds
D/dalvikvm( 1211): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BluetoothPan(  966): BluetoothPAN Proxy object connected
D/PanService( 1211): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1211): initializeNative(L110): pan
I/bluedroid( 1211): get_profile_interface pan
D/bt-btif ( 1211): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  966): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
I/BluetoothAdapterState( 1211): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/bt-btif ( 1211): entered btif_hl_select_thread
D/bt-btif ( 1211): btif_hl_select_wakeup_init
D/bt-btif ( 1211): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1211): max_s=79 
D/bt-btif ( 1211): set curr_set = org_set 
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
I/LGBluetoothMapAdapter( 1211): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1211): BluetoothMapBinder()
D/BluetoothMapService( 1211): Received start request. Starting profile...
D/BluetoothMapService( 1211): start()
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BtGatt.JNI( 1211): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1211): handleDebugAction() action=null
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/HeadsetPhoneState( 1211): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1211): Disconnected process message: 11
D/BtGatt.GattService( 1211): Received start request. Starting profile...
D/BtGatt.GattService( 1211): start()
I/bluedroid( 1211): get_profile_interface gatt
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
I/BluetoothSAPServiceJni( 1211): classInitNative(L170): succeeds
D/SapService( 1211): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1211): initializeNative(L175): sap
I/bluedroid( 1211): get_profile_interface sap
I/bt-btif ( 1211): btif_sc_get_interface
I/bt-btif ( 1211): init
D/bt-btif ( 1211): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1211): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1211): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1211): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1448): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
,I/chromium( 4160): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 4252): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4252): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4252): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4252): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4252): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4252): Global control interface '@android:wpa_wlan0'
,D/wpa_supplicant( 4252): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4252): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4252): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4252): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4252): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4252): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4252): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4252): disable_scan_offload=1
D/wpa_supplicant( 4252): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4252): update_config=1
D/wpa_supplicant( 4252): device_name='g2_open_com'
D/wpa_supplicant( 4252): manufacturer='LGE'
D/wpa_supplicant( 4252): model_name='LG-D802'
D/wpa_supplicant( 4252): model_number='LG-D802'
D/wpa_supplicant( 4252): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4252): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4252): p2p_disabled=1
D/wpa_supplicant( 4252): p2p_no_group_iface=1
D/wpa_supplicant( 4252): Line: 15 - start of a new network block
D/wpa_supplicant( 4252): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4252): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4252): key_mgmt: 0x2
D/wpa_supplicant( 4252): priority=1 (0x1)
V/BluetoothFTPServiceJni( 1211): classInitNative
I/BluetoothFTPServiceJni( 1211): classInitNative(L271): succeeds
,D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/BluetoothFTPService( 1211): BluetoothFtpBinder()
D/**BluetoothFTPService( 1211): Received start request. Starting profile...
,V/BluetoothFTPService( 1211): FTP-Server Service start
D/BluetoothFTPServiceJni( 1211): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1211): get_profile_interface ftp
I/bt-btif ( 1211): btif_fts_get_interface
I/bt-btif ( 1211): init
D/bt-btif ( 1211): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1211): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1211): Handler(): got msg=1
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1211): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116316256)( 1211): Message: 1
D/BluetoothAdapterService(1116316256)( 1211): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1211): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1211): All profile services started.
D/BluetoothAdapterState( 1211): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1211): enable 1
I/bt-btif ( 1211): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1211): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/bt_hci_bdroid( 1211): init
I/bt_vendor( 1211): init
I/bt_vnd_conf( 1211): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1211): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,I/bt-btif ( 1211): libbt-hci init returns 0
I/GKI_LINUX( 1211): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 1211): bt_hc_worker_thread started
,I/ActivityManager(  966): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4258 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4258): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 4252): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4252): Priority group 1
D/wpa_supplicant( 4252):    id=0 ssid='NG700'
,D/wpa_supplicant( 4252): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
,D/AuthorizationBluetoothService( 1531): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/wpa_supplicant( 4252): disable_scan_offload=1
D/wpa_supplicant( 4252): Priority group 1
D/wpa_supplicant( 4252):    id=0 ssid='NG700'
I/wpa_supplicant( 4252): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4252): nl80211: RFKILL status not available
D/wpa_supplicant( 4252): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4252): nl80211: TDLS supported
D/wpa_supplicant( 4252): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4252): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4252): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4252): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4252): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4252): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4252): nl80211: Subscribe to mgmt frames with non-AP handle 0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
,D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 11
I/ActivityManager(  966): Killing 3067:android.process.media/u0a23 (adj 15): empty #17
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  966): setWifiState: enabling
,E/WifiStateMachine(  966): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  966): useWiFiOffloading() : false
E/WifiStateMachine(  966): CONFIG_LGE_WLAN_PATH : true
D/WifiStateMachine(  966): Supplicant start successful
D/WifiMonitor(  966): WifiMonitorSingleton gotten
D/WifiMonitor(  966): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  966): connecting to supplicant
,V/WfdStateTracker( 1155): WfdStateTracker handleDirectStateChangedEvent: 1
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/WifiServiceExtension(  966): WIFI_STATE_CHANGED_ACTION [2]
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,I/ConfigService( 1531): onDestroy
,I/ActivityManager(  966): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4272 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/bt_userial_vendor( 1211): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1211): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1211): device fd = 84 open
,D/HyLog   ( 4272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4272): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/PCSuite ( 4272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  966): Killing 3239:com.android.mms/u0a35 (adj 15): empty #17
,D/CountryDetector(  966): No listener is left
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,I/LocationManagerService(  966): remove 430abc00
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/bt_hwcfg( 1211): Chipset BCM4335A0
,D/bt_hwcfg( 1211): Target name = [BCM4335A0]
D/bt_hwcfg( 1211): Target name = [BCM4335]
I/bt_hwcfg( 1211): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1211): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1211): bt vendor lib: set UART baud 4000000
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt_hwcfg( 1211): Releasing 4335 AXI BRIDGE lock
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/bt_hwcfg( 1211): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1211): Settlement delay -- 100 ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/bt_hwcfg( 1211): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1211): Setting local bd addr to 34:FC:EF:9D:93:0B
,I/bt_hwcfg( 1211): vendor lib fwcfg completed
,I/bt-btif ( 1211): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/        ( 1211): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1211): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1211): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1211): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1211): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1211): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1211): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 1211): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1211): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1211): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1211): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1211): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1211): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 1211): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1211): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1211): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1211): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1211): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1211): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
,D/bt-btif ( 1211): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1211): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1211): bta_dm_sm_execute event:0x0
I/bt-btif ( 1211): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1211): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1211): bta_sys_sm_execute state:1, event:0x1
,I/bt-btif ( 1211): bta_sys_hw_evt_enabled for 0
,D/bt-btif ( 1211):  bta_sys_hw_btm_cback was called with parameter: 0
,I/bt-btif ( 1211): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1211):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1211):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1211): ##################################
D/bt-btif ( 1211): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1211): ##################################
D/bt-btif ( 1211): btif_dm_get_ble_local_keys  *p_key_mask=0x03
,E/bt-btm  ( 1211): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b5a4c5 
I/bt-smp  ( 1211): SMP_Register state=0
E/bt-btm  ( 1211): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b5a4c5 
D/bt-btif ( 1211): bta_gattc_register state 0
D/bt-btif ( 1211): bta_gattc_enable
I/bt-att  ( 1211): GATT_Register
D/bt-att  ( 1211): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 1211): allocated gatt_if=3
D/bt-btif ( 1211): bta_dm_gattc_callback event = 0
D/bt-btif ( 1211): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1211): GATT_StartIf gatt_if=3
D/bt-att  ( 1211): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1211): gatt_find_the_connected_bda found=0 found_idx=7
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1211): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1211): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1211): bta_dm_sm_execute event:0x2
D/bt-btif ( 1211): BTA is generating EIR
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1211): Adding UUID=0x110C into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1211): nsc_mask: 0x6
D/bt-btif ( 1211): bta_av_co_audio_init
D/bt-btif ( 1211): bta_av_co_audio_init: 0
D/bt-btif ( 1211): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1211): bta_av_co_audio_init
D/bt-btif ( 1211): bta_av_co_audio_init: 1
D/bt-btif ( 1211): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1211): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1211): A2D_AddRecord uuid: 110a
I/bt-btif ( 1211): Adding UUID=0x110A into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1211): rc_acp_handle:0 idx:1
D/bt-btif ( 1211): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
,D/bt-btif ( 1211): reg_audio: 0x1
D/bt-btif ( 1211): bta_ag_scb_alloc 1
I/bt-btif ( 1211): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1211): bta_ag_add_record uuid: 1112
I/bt-btif ( 1211): Adding UUID=0x1112 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1211): bta_ag_add_record uuid: 111f
I/bt-btif ( 1211): Adding UUID=0x111F into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
,D/bt-btif ( 1211): getAccess buffer->st_uid:1000 buffer->st_gid:1028,
D/bt-btif ( 1211): bta_fts_api_enable srm:1
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1211): Adding UUID=0x1106 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1211): FTS:  SDP Registered (handle 0x00010006)
,I/bt-btif ( 1211): bta_fts_ci_resume status:1
,I/bt-btif ( 1211): FTP SERVER enabled with Root Path [/storage],
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1211): Adding UUID=0x112D into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1211): bte_sap_evt: event=0
E/bt-btif ( 1211): Calling BTA_HhEnable
,D/bt-btif ( 1211): bta_gattc_register state 2
I/bt-att  ( 1211): GATT_Register
D/bt-att  ( 1211): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1211): allocated gatt_if=4
D/bt-btif ( 1211): bta_hh_gattc_callback event = 0
I/bt-att  ( 1211): GATT_StartIf gatt_if=4
D/bt-att  ( 1211): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1211): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1211): in add:1
D/bt-btif ( 1211): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1211): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1211): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1211): Remote device:b0:c5:59:3f:75:69, size:18
,D/bt-btif ( 1211): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1211): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1211): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1211): Remote device:10:d3:8a:fb:85:d4, size:18
,D/bt-btif ( 1211): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1211): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1211): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1211): Remote device:08:ec:a9:50:76:27, size:18
,D/bt-btif ( 1211): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1211): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1211): Remote device:50:2e:6c:ac:21:50, size:18,
D/bt-btif ( 1211): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1211): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1211): Remote device:34:fc:ef:11:ae:67, size:18,
D/bt-btif ( 1211): Remote device:f8:95:c7:87:85:54, size:18,
D/bt-btif ( 1211): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1211): Remote device:e0:db:10:14:e2:c0, size:18
I/bt-btif ( 1211): bta_dm_sm_execute event:0x9
,D/bt-btif ( 1211): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1211): Remote device:90:e7:c4:f6:69:77, size:18
,D/bt-btif ( 1211): Remote device:90:e7:c4:3c:62:6a, size:18,
D/bt-btif ( 1211): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1211): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1211): bta_dm_sm_execute event:0x9
D/bt-btif ( 1211): Remote device:, size:128
E/bt-btif ( 1211): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1211): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,D/bt-btif ( 1211): out
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1211): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1211): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1211): in, bd addr:, prop type:16, len:4
,E/bt-btif ( 1211): Unknow prop type:16
I/bt-btif ( 1211): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1211): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1211): in, bd addr:, prop type:9, len:4,
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1211): btif_storage_get_adapter_property service_mask:0x120148
,D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 devicemode 0,
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1211): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  966): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  966): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1211): Property change not handled in Java land:16
,I/bt-btif ( 1211): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1211): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1211): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1211): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1211): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
,D/bt-btif ( 1211): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
,I/bt-btif ( 1211): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1211): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1211): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1211): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1211): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1211): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1211): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1211): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1211): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1211): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1211): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1211): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1211): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1211): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1211): hw_sco_config...
,E/bt_hwcfg( 1211): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1211): HC lib lpm enable=1 return 0
,I/bt-btif ( 1211): BTA_BrcmInit
E/bt-gki  ( 1211): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
I/bt-btif ( 1211): HC lpm_result_cb 1
,D/IOP_DB_BT( 1211): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 1211): db_open: db_open : handle 1623489068l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1211): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1211): db_query: result 1
I/        ( 1211): iop_db_open: iop_db_open status 0
,D/bt-btif ( 1211): btsock initializing...
D/bt-btif ( 1211): in initialized:1
D/bt-btif ( 1211): ts[7].used:1
D/bt-btif ( 1211): ts[6].used:0
D/bt-btif ( 1211): alloc_thread_slot ret:6
D/bt-btif ( 1211): h:6, cmd_fdr:87, cmd_fdw:88
,D/bt-btif ( 1211): h:6, thread id:1641509808
I/bt-btif ( 1211): BTA_JvEnable
D/bt-btif ( 1211): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1211): unhandled event:0, slot id:0
D/bt-btif ( 1211): btsock successfully initialized
D/bt-btif ( 1211): jni_initialized = 1, btpan_cb.enabled:0
,D/bt-btif ( 1211): Enabling PAN....
I/bt-btif ( 1211): bta_pan_co_init
,D/bt-btif ( 1211): local_role:3
D/bt-btif ( 1211): btpan_role:0x3
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1211): Adding UUID=0x1116 into EIR
,D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1211): Adding UUID=0x1115 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1211): Adding UUID=0x1116 into EIR
D/bt-btif ( 1211): BTA is generating EIR
,I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1211): Removing UUID=0x1117 from EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1211): Adding UUID=0x1115 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
,I/bte_conf( 1211): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1211): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bt-btif ( 1211): bta_dm_sm_execute event:0x31
,D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1211): Adding UUID=0x1200 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1211): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1211): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 1211): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/bt-btif ( 1211): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1211): adapter_state_change_callback: Status is: 1
,D/bt-btif ( 1211): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
,D/BluetoothAdapterState( 1211): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1211): ScanMode =  20
D/BluetoothAdapterProperties( 1211): State =  11
,D/BluetoothAdapterProperties( 1211): mDiscoverableTimeout =  120
I/bt-btif ( 1211): btif_set_adapter_property type: 7, len 4, 0x42902a20
I/bt-btif ( 1211): set property scan mode : 1
I/bt-btif ( 1211): bta_dm_sm_execute event:0x3
,I/bt-btif ( 1211): btif_in_storage_request_copy_cb
I/bt-btif ( 1211): btif_set_adapter_property type: 9, len 4, 0x42902a78
I/bt-btif ( 1211): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1211): Bluetooth adapter state changed: 11-> 12
,D/bt-btif ( 1211): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1211): btif_av_state_idle_handler devicemode: 0
D/BluetoothAdapterService( 1211): Broadcasting updateAdapterState() to 1 receivers.
D/bt-btif ( 1211): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
,D/bt-btif ( 1211): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/BluetoothManagerService(  966): Message: 60
,D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  966): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan(  966): onBluetoothStateChange(on) call bindService
,D/bt-btif ( 1211): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1211): File Transfer: Enable Complete
I/bt-btif ( 1211): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1211): operation_cmpl_callback(L192):  oper:3 status:0
V/BluetoothAdapterService( 1211): startPbapService
,I/BluetoothFTPService( 1211): onFtpServerEnabled: /storage
D/bt-btif ( 1211): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1211): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
,D/bt-btif ( 1211): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/bt-btif ( 1211): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1211): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1211): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1211): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1211): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1211): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1211): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1211): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1211): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1211): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1211): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1211): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1211): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1211): Remote device:7c:f9:0e:51:18:22, size:18
,D/bt-btif ( 1211): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1211): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1211): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1211): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1211): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1211): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1211): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1211): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1211): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1211): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1211): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1211): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1211): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1211): Remote device:, size:18
E/bt-btif ( 1211): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1211): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1211): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1211): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1211): execute storage request event : 2
I/bt-btif ( 1211): type: 7, len 4, 0x60678032
D/bt-btif ( 1211): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  966): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
I/bt-btif ( 1211): execute storage request event : 2
I/bt-btif ( 1211): type: 9, len 4, 0x6067807e
D/bt-btif ( 1211): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1211): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothA2dp(  966): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  966): Bluetooth State Change Intent: 11 -> 12
,D/LGBluetoothAPIService( 1155): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1155): Message: 1
,D/LGBluetoothAPIService( 1155): MESSAGE_BOOT_COMPLETED
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothAdapterService(1116316256)( 1211): Get Bonded Devices being called
D/bt_h4   ( 1211): vendor lib postload completed
I/bt-btif ( 1211): HC postload_cb 0
I/BluetoothAdapterState( 1211): Entering On State
D/BluetoothManagerService(  966): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 1211): onReceive
D/BluetoothManagerService(  966): Message: 40
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1211): STATE_ON
I/LGBluetoothAPIService( 1155): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothServiceAdapter( 1211): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1211): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1211): [BTUI]         local_name: Thali Test's G2
D/BluetoothAdapterService(1116316256)( 1211): Quiet mode Enabled = false
D/BluetoothAdapterService(1116316256)( 1211): Initiate auto connection on BT on...
,D/BluetoothAdapterService( 1211): [BTUI] autoConnect() : not allowed
,D/BluetoothAdapterService( 1211): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289a260
V/BluetoothPbapService( 1211): Pbap Service onCreate
,V/BluetoothPbapService( 1211): Starting PBAP service
,D/LGBluetoothPbapAdapter( 1211): [BTUI] getInstance : create
V/BluetoothPbapService( 1211): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1211): state: 12
,V/BluetoothMapService( 1211): Handler(): got msg=1
,D/BluetoothMapService( 1211): Map Service startRfcommSocketListener
,W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/LGBluetoothAPIServer( 1211): [BTUI] onCreate()
D/BluetoothMapService( 1211): Map Service initSocket
D/LGBluetoothAPIServer( 1211): [BTUI] onBind()
D/LGBluetoothAPIService( 1155): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothAPIService( 1155): Message: 100
D/LGBluetoothAPIService( 1155): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1211): Handler(): got msg=1
V/BluetoothPbapService( 1211): Pbap Service startRfcommSocketListener
W/BluetoothAdapter( 1211): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapReceiver( 1211): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1211): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1211): ***********state = 12
V/BluetoothPbapService( 1211): Pbap Service initSocket
E/BluetoothServiceJni( 1211): SOCK FLAG = 1 ***********************
D/bt-btif ( 1211): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1211): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1211): BTA_JvCreateRecordByUser
D/bt-btif ( 1211): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1211): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1211): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1211): Adding UUID=0x1132 into EIR
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000484 04071440
D/bt-btif ( 1211): MAPSS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1211): BTA_JvRfcommStartServer
D/bt-btif ( 1211): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1211): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1211): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothMapService( 1211): Succeed to create listening socket 
D/BluetoothMapService( 1211): Accepting socket connection...
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4252): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4252): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4252): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4252): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4252): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4252): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4252): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4252): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4252): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  966): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/LocalBluetoothProfileManager( 2586): Adding local A2DP profile
W/BluetoothAdapter( 1211): getBluetoothService() called with no BluetoothManagerCallback
,D/Tethering(  966): sendTetherStateChangedBroadcast 1, 0, 0
E/BluetoothServiceJni( 1211): SOCK FLAG = 1 ***********************
D/bt-btif ( 1211): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
,D/bt-btif ( 1211): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1211): BTA_JvCreateRecordByUser
D/bt-btif ( 1211): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1211): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1211): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1211): Adding UUID=0x112F into EIR
D/bt-btif ( 1211): BTA is generating EIR
,I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1211): PBS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1211): BTA_JvRfcommStartServer
D/libc    (  265): _dns_getaddrinfo: iptype =0
D/bt-btif ( 1211): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/bt-btif ( 1211): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1211): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothPbapService( 1211): Succeed to create listening socket 
,V/BluetoothPbapService( 1211): Accepting socket connection...
,D/BluetoothManagerService(  966): Message: 30
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/SocketClient(  265): write error (Broken pipe)
D/wpa_supplicant( 4252): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4252): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4252): wlan0: Setting scan request: 0 sec 100000 usec
,D/LocalBluetoothProfileManager( 2586): Adding local HEADSET profile
,D/BluetoothManagerService(  966): Message: 30
,D/BluetoothManagerService(  966): Message: 30
W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
,D/BluetoothManagerService(  966): Message: 30
,D/LocalBluetoothProfileManager( 2586): Adding local MAP profile
D/BluetoothMap( 2586): Create BluetoothMap proxy object
,D/BluetoothManagerService(  966): Message: 30
,D/BluetoothManagerService(  966): Message: 30
,D/LocalBluetoothProfileManager( 2586): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 1211): Pbap Service onBind
W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
D/wpa_supplicant( 4252): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4252): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4252): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4252): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
,D/LGBluetoothUserBindClient( 2586): [BTUI] initUserBindClient
D/wpa_supplicant( 4252): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4252): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4252): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): Using existing control interface directory.
I/wpa_supplicant( 4252): 0xb875bcc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4252): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4252): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4252): lge_eap_carrier_var_init
D/wpa_supplicant( 4252): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4252): wlan0: Added interface wlan0
D/wpa_supplicant( 4252): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4252): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4252): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4252): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4252): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4252): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4252): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4252): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4252): update_config=1
D/wpa_supplicant( 4252): device_name='Thali Test's G2'
D/wpa_supplicant( 4252): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4252): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4252): persistent_reconnect=1
,D/wpa_supplicant( 4252): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/DockEventReceiver( 2586): finishStartingService: stopping service
D/wpa_supplicant( 4252): update_config=1
D/wpa_supplicant( 4252): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4252): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4252): eapol_version=1
D/wpa_supplicant( 4252): ap_scan=1
,D/wpa_supplicant( 4252): fast_reauth=1
D/wpa_supplicant( 4252): p2p_disabled=0
,D/wpa_supplicant( 4252): p2p_no_group_iface=0
I/wpa_supplicant( 4252): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4252): nl80211: RFKILL status not available
D/wpa_supplicant( 4252): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4252): nl80211: TDLS supported
D/wpa_supplicant( 4252): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4252): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4252): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4252): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4252): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4252): nl80211: Subscribe to mgmt frames with non-AP handle 0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
,D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb876bc28
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 11
D/BluetoothA2dp( 2586): Proxy object connected
,W/ContextImpl( 2586): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/A2dpProfile( 2586): Bluetooth service connected
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4252): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4252): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4252): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4252): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4252): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4252): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4252): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4252): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4252): nl80211: 5735-5835 @ 40 MHz
D/wpa_supplicant( 4252): nl80211: Added 802.11b mode based on 802.11g information
D/BluetoothHeadset( 2586): Proxy object connected
D/HeadsetProfile( 2586): Bluetooth service connected
D/BluetoothInputDevice( 2586): Proxy object connected
D/HidProfile( 2586): Bluetooth service connected
D/BluetoothPan( 2586): BluetoothPAN Proxy object connected
D/PanProfile( 2586): Bluetooth service connected
D/BluetoothMap( 2586): Proxy object connected
D/MapProfile( 2586): Bluetooth service connected
D/BluetoothMap( 2586): getConnectedDevices()
V/BluetoothMapService( 1211): getConnectedDevices()
D/BluetoothPbap( 2586): Proxy object connected
D/PbapServerProfile( 2586): Bluetooth service connected
D/LGBluetoothUserBindClient( 2586): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2586): onReceive
D/LGBluetoothFeatureConfig( 2586): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2586): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2586): return without doing reset settings.
V/BluetoothOppReceiver( 1211): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1211): [BTUI] startOppService()
D/wpa_supplicant( 4252): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4252): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4252): nl80211: Flush PMKIDs
D/wpa_supplicant( 4252): p2p0: State: DISCONNECTED -> INACTIVE
,V/BluetoothOppManager( 1211): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1211): isPrivacyLogsEnabled : true
V/BtOppService( 1211): onCreate
,D/LGBluetoothOppAdapter( 1211): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppNotification( 1211): send message
,V/BtOppService( 1211): Starting RfcommListener
D/BluetoothOppPreference( 1211): Dumping Names:  
D/BluetoothOppPreference( 1211): {}
D/BluetoothOppPreference( 1211): Dumping Channels:  
,D/BluetoothOppPreference( 1211): {}
V/BtOppService( 1211): onStartCommand
,V/BtOppService( 1211): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/wpa_supplicant( 4252): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4252): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4252): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4252): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4252): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4252): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4252): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4252): Using existing control interface directory.
I/wpa_supplicant( 4252): 0xb876b098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4252): [ITEC] ASSIGN CALL BACK A4 5
V/BtOppService( 1211): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 1211): new notify threadi!
I/wpa_supplicant( 4252): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4252): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4252): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4252): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4252): [ITEC] USE NON-INET
I/wpa_supplicant( 4252): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4252): HY wiflus comm channel initialized
V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42931928 on behalf of 
D/wpa_supplicant( 4252): P2P: Own listen channel: 6
I/wpa_supplicant( 4252): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4252): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4252): P2P: Add operating class 81
D/wpa_supplicant( 4252): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4252): P2P: Add operating class 115
D/wpa_supplicant( 4252): P2P: Channels - hexdump(len=4): 24 28 2c 30
V/BluetoothOppNotification( 1211): send delay message
D/wpa_supplicant( 4252): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4252): p2p0: Added interface p2p0
V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/wpa_supplicant( 4252): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4252): random: Got 18/20 bytes from /dev/random
D/wpa_supplicant( 4252): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
V/BtOppService( 1211): start RfcommListener
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4252): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 4252): Get randomness: len=20 entropy=0
V/BtOppService( 1211): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 1211): RfcommListener started
V/BtOppService( 1211): ContentObserver received notification
D/wpa_supplicant( 4252): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,V/BtOppRfcommListener( 1211): Starting RFCOMM listener....
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42936750 on behalf of 
V/BtOppService( 1211): ContentObserver received notification
,V/BtOppService( 1211): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@429358b0 on behalf of 
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
W/BluetoothAdapter( 1211): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 1211): mUpdateCompleteNotification = true
D/WifiStateMachine(  966): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  966): invokeExitMethods: InitialState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  966): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131144
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): deferMessage: msg=131144
D/AuthorizationBluetoothService( 1531): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131085
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): deferMessage: msg=131085
E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
E/BluetoothServiceJni( 1211): SOCK FLAG = 0 ***********************
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131149
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): setSuspendOptimizations: 2 true
D/WifiStateMachine(  966): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131146
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131101
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2586): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2586): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2586): [AUTORUN] persist.sys.usb.config = boot,adb
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiStateMachine(  966): processMsg: DefaultState
D/bt-btif ( 1211): btsock_rfc_listen, service_name:OBEX Object Push
D/WifiStateMachine(  966): handleMessage: X
D/bt-btif ( 1211): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1211): BTA_JvCreateRecordByUser
D/bt-btif ( 1211): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1211): name:OBEX Object Push, scn:12
D/bt-btif ( 1211): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1211): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1211): Adding UUID=0x1105 into EIR
,D/LGBluetoothServiceAdapter( 1211): [BTUI] createSocketChannel FD=96 mFd=92
D/bt-btif ( 1211): BTA is generating EIR
I/bt-btif ( 1211): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1211): BTA_JvRfcommStartServer
D/bt-btif ( 1211): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1211): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
V/BtOppRfcommListener( 1211): Started RFCOMM listener....
I/BtOppRfcommListener( 1211): Accept thread started.
V/BtOppRfcommListener( 1211): Accepting connection...
I/Config  ( 2586): getOperator() : OPEN
D/UsbSettingsControl( 2586): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2586): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 2586): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2586): [AUTORUN] setTetherStatus() : status=false
D/WifiStateMachine(  966): handleMessage: E msg.what=147457
D/WifiStateMachine(  966): processMsg: SupplicantStartingState
D/WifiStateMachine(  966): Supplicant connection established
,D/WifiNative-wlan0(  966): doString: DRIVER MACADDR
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER MACADDR'
D/WifiNative-wlan0(  966):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  966): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  966): setWifiState: enabled
D/WifiOffDelayIfNotUsed(  966): setPowerSaveActivated(false)
D/WifiActivationWhileCharging(  966): unregister : we don't need to unregister
E/WifiStateMachine(  966): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  966): useWiFiOffloading() : false
E/WifiStateMachine(  966): CONFIG_LGE_WLAN_PATH : true
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiConfigStore(  966): Loading config and enabling all networks
D/WifiNative-wlan0(  966): doString: LIST_NETWORKS
I/WifiServiceExtension(  966): WIFI_STATE_CHANGED_ACTION [3]
D/WfdService( 1155): Waiting for WifiP2p enabling
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4252): wlan0: Control interface command 'LIST_NETWORKS'
I/WifiServiceExtension(  966): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0(  966):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  966): 0	NG700	any	
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/wpa_supplicant( 4252): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4252): wlan0: nl80211: scan request
D/wpa_supplicant( 4252): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 bssid
D/PCSuite ( 4272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/wpa_supplicant( 4252): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'bssid'
D/wpa_supplicant( 4252): nl80211: Event message available
D/wpa_supplicant( 4252): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4252): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4252): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  966): ***WAPI : not WAPI
D/WifiNative-wlan0(  966): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4252): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4252): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4252): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  966): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  966): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4252): device_name='g2_open_com'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4252): manufacturer='LGE'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4252): model_name='LG-D802'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4252): model_number='LG-D802'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
D/wpa_supplicant( 4252): serial_number='022678fb504e29b0'
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4252): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  966): invokeExitMethods: SupplicantStartingState
W/Settings( 3311): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  966): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  966): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  966): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4252): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4252): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  966): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): setDetailed state, old =IDLE and new state=DISCONNECTED
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-REMOVE 3
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/Wi,fiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  966): doBoolean: RECONNECT
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4252): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doString: STATUS
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4252): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  966):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  966): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  966): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  966): handleScreenStateChanged: true
D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4252): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  966): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131144
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131085
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=132106
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  966): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4252): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4252): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=132096
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/CommandListener(  265): Setting iface cfg
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/CommandListener(  265): Trying to bring up p2p0
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  966): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4252): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4252): disconnect_rssi_lvl: -100
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiP2pService(  966): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiMonitor(  966): WifiMonitorSingleton gotten
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  966): handleMessage: X
D/WifiMonitor(  966): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  966): handleMessage: E msg.what=143371
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiNative-p2p0(  966): doBoolean: SET persistent_reconnect 1
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4252): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4252): persistent_reconnect=1
D/wpa_supplicant( 4252): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  966):    returned true
D/WifiP2pService(  966): P2pEnablingState
D/WifiP2pService(  966): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2p socket connection successful
D/WifiP2pService(  966): P2pEnabledState
D/WifiP2pService(  966): sending p2p connection changed broadcast
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiNative-p2p0(  966): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4252): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4252): device_name='Thali Test's G2'
D/WifiNative-p2p0(  966):    returned true
D/WifiServiceExtension(  966): postfix byte check : 15
D/WifiNative-p2p0(  966): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4252): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4252): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4252): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4252): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4252): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4252): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4252): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4252): Single channel concurrency preference: sta
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doString: STATUS
D/wpa_supplicant( 4252): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  966):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  966): p2p_state=IDLE
D/WifiNative-p2p0(  966): wifi_display=1
D/WifiNative-p2p0(  966): ifname=p2p0
D/WifiNative-p2p0(  966): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  966): ifname=wlan0
D/WifiNative-p2p0(  966): address=34:fc:ef:de:0a:e2
D/WifiController(  966): battery changed pluggedType: 2
D/WifiP2pService(  966): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  966): before postfix = Thali Test's G2
D/WifiP2pService(  966): after postfix = Thali Test's G2
D/WifiNative-p2p0(  966): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4252): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4252): P2P: Stopping find
D/wpa_supplicant( 4252): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4252): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4252): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4252): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  966):    returned true
D/WifiNative-p2p0(  966): doString: LIST_NETWORKS
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4252): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  966):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  966): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4252): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4252): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  966): DeviceAddress: 36:fc:ef:de:0a:e2
,D/wpa_supplicant( 4252): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4252): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiNative-p2p0(  966):    returned true
D/WifiP2pService(  966): sending p2p persistent groups changed broadcast
D/WifiP2pService(  966): InactiveState
D/WifiP2pService(  966): InactiveState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): DefaultState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): InactiveState{ when=-26ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=-26ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): DefaultState{ when=-26ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServiceExtension(  966): No p2p device connected
,D/dalvikvm(  966): GC_EXPLICIT freed 22687K, 49% free 29084K/56808K, paused 3ms+10ms, total 162ms
V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42939c68 on behalf of 
V/BluetoothOppNotification( 1211): update too frequent, put in queue
V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 1211): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/WfdStateTracker( 1155): WfdStateTracker handleDirectStateChangedEvent: 2
D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
I/WfdStateTracker( 1155): handleP2pThisDeviceChanged
V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@4293c278 on behalf of 
V/BluetoothOppNotification( 1211): outbound: succ-0  fail-0
V/BluetoothOppNotification( 1211): outbound notification was removed.
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@4293dff0 on behalf of 
,V/BluetoothOppNotification( 1211): inbound: succ-0  fail-0
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/BluetoothOppNotification( 1211): inbound notification was removed.
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@4293f6d8 on behalf of 
,I/dalvikvm(  966): Jit: resizing JitTable from 8192 to 16384
I/ActivityManager(  966): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4337 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4337): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4337): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  966): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4350 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  966): Killing 3815:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4350): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4350): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4350): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Wireless_Storage( 4350): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 4046): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4046): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  966): Killing 3311:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4252): EAPOL: disable timer tick
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4252): EAPOL: disable timer tick
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,V/BluetoothOppNotification( 1211): new notify threadi!
,V/BluetoothOppNotification( 1211): send delay message
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42941848 on behalf of 
,V/BluetoothOppNotification( 1211): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42943480 on behalf of 
,V/BluetoothOppNotification( 1211): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1211): outbound notification was removed.
,V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@42945010 on behalf of 
,V/BluetoothOppNotification( 1211): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1211): inbound notification was removed.
V/BluetoothOppProvider( 1211): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1211): created cursor android.database.sqlite.SQLiteCursor@429465b8 on behalf of 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  272): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  272): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  272): thread 0xb2768008 type 0 TID 848 going to sleep
,E/BatteryObserver( 1155): usb Uevent not necessary.
,V/AudioFlinger(  272): thread 0xb25fd008 type 0 TID 1001 going to sleep
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.453583 Y: -0.398331 Z: 9.759613 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453583 .y:-0.398331 .z:9.759613
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.453201 Y: -0.392929 Z: 9.775482 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453201 .y:-0.392929 .z:9.775482
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4252): nl80211: Event message available
D/wpa_supplicant( 4252): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4252): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4252): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4252): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 4252): nl80211: Survey data missing
D/wpa_supplicant( 4252): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4252): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4252): wlan0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700',
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4252): wlan0: BSS: Add new id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
,D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4252): wlan0: BSS: Add new id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free',
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 4252): wlan0: BSS: Add new id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4252): wlan0: BSS: Add new id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698',
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4252): BSS: last_scan_res_used=7/32 last_scan_full=0
,D/wpa_supplicant( 4252): wlan0: New scan results available,
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4252): WPS: AP c0:ff:d4:d3:aa:4a type 0 added,
D/wpa_supplicant( 4252): WPS: AP c0:ff:d4:d3:aa:48 type 0 added,
D/wpa_supplicant( 4252): WPS: AP a0:c5:62:7a:49:97 type 0 added,
D/wpa_supplicant( 4252): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added,
D/wpa_supplicant( 4252): WPS: AP 64:7c:34:12:7f:81 type 0 added,
D/wpa_supplicant( 4252): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
,D/wpa_supplicant( 4252): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4252): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4252): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4252): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4252): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4252): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 4252): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4252): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61
D/wpa_supplicant( 4252): wlan0:    skip - SSID mismatch,
,D/wpa_supplicant( 4252): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-61 wps
D/wpa_supplicant( 4252): wlan0:    selected based on RSN IE
,D/wpa_supplicant( 4252): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4252): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4252): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4252): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4252): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4252): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 4252): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4252): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb875d5a8  current_ssid=0x0
D/wpa_supplicant( 4252): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4252): USIM:  scard_init function
D/wpa_supplicant( 4252): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4252): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4252): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4252): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4252): TDLS: TDLS is allowed in the target BSS
,I/wpa_supplicant( 4252): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4252): wlan0: Cancelling scan request
D/wpa_supplicant( 4252): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4252): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4252): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4252): RSN: PMKSA cache search - network_ctx=0xb875d5a8 try_opportunistic=0
,D/wpa_supplicant( 4252): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4252): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4252): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4252): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4252): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 4252): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 4252): wlan0: WPA: using PTK CCMP,
,D/wpa_supplicant( 4252): wlan0: WPA: using KEY_MGMT WPA-PSK,
,D/wpa_supplicant( 4252): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 4252): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 4252): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4252): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4252): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4252): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 4252): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4252): nl80211: Unsubscribe mgmt frames handle 0xb875c590 (mode change)
D/wpa_supplicant( 4252): nl80211: Subscribe to mgmt frames with non-AP handle 0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
,D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590,
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
,D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 4252): nl80211: Register frame type=0xd0 nl_handle=0xb875c590
D/wpa_supplicant( 4252): nl80211: Register frame match - hexdump(len=2): 0a 11
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 4252): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4252):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252):   * freq=2412
D/wpa_supplicant( 4252):   * SSID - hexdump(len=5): 4e 47 37 30 30,
,D/wpa_supplicant( 4252):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4252):   * Auth Type 0
D/wpa_supplicant( 4252):   * WPA Versions 0x2
D/wpa_supplicant( 4252): nl80211: Connect request send successfully
D/wpa_supplicant( 4252): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 4252): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 4252): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4252): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 a0:c5:62:7a:49:97]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 06:7c:34:12:7f:81]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 64:7c:34:12:7f:81]
D/WifiStateMachine(  966): handleMessage: E msg.what=147461
D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  966): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
,D/wpa_supplicant( 4252): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiMonitor(  966): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  966): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
,D/wpa_supplicant( 4252): nl80211: Event message available
D/wpa_supplicant( 4252): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4252): nl80211: Connect event
D/wpa_supplicant( 4252): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4252): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4252): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4252): wlan0: Association info event
D/wpa_supplicant( 4252): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4252): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4252): wlan0: freq=2412 MHz
D/wpa_supplicant( 4252): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4252): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4252): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4252): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4252): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): scard is not null..
D/wpa_supplicant( 4252): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4252): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4252): TDLS: Remove peers on association
D/wpa_supplicant( 4252): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4252): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4252): EAPOL: enable timer tick
D/wpa_supplicant( 4252): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4252): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4252): wlan0: Cancelling scan request
,D/wpa_supplicant( 4252): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
,D/wpa_supplicant( 4252): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe ...
D/wpa_supplicant( 4252): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4252): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4252): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4252): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4252): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4252):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4252):   key_nonce - hexdump(len=32): e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe db 8f 3a 8f ba 9b de 2f eb 33 23 55 be 02 df 35 05
D/wpa_supplicant( 4252):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe ...
D/wpa_supplicant( 4252): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4252): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4252): Get randomness: len=32 entropy=8
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 4252): WPA: Renewed SNonce - hexdump(len=32): bf 80 bb 25 4f cd 37 39 90 1b 93 6b 6c af 4e b4 31 ca 10 dc aa 3c 4d e9 99 da 36 6e 49 21 c6 3c
D/wpa_supplicant( 4252): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): WPA: Nonce1 - hexdump(len=32): bf 80 bb 25 4f cd 37 39 90 1b 93 6b 6c af 4e b4 31 ca 10 dc aa 3c 4d e9 99 da 36 6e 49 21 c6 3c
D/wpa_supplicant( 4252): WPA: Nonce2 - hexdump(len=32): e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe db 8f 3a 8f ba 9b de 2f eb 33 23 55 be 02 df 35 05
D/wpa_supplicant( 4252): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4252): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4252): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4252): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4252): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4252): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4252): WPA: Derived Key MIC - hexdump(len=16): cf f9 42 cc 10 b9 44 7e fa 96 ce ec e3 b1 6d e8
,D/wpa_supplicant( 4252): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 bf 80 bb 25 4f cd 37 39 90 1b 93 6b 6c af 4e ...
,W/WifiMonitor(  966): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/wpa_supplicant( 4252): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe ...
D/wpa_supplicant( 4252): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4252): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4252): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4252): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4252):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4252):   key_nonce - hexdump(len=32): e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe db 8f 3a 8f ba 9b de 2f eb 33 23 55 be 02 df 35 05
D/wpa_supplicant( 4252):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_rsc - hexdump(len=8): e8 6b 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4252):   key_mic - hexdump(len=16): 53 63 4a 3c 32 6d 04 e7 26 f6 4b 26 db f2 e1 06
D/wpa_supplicant( 4252): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e3 5a 6a 99 a3 6f 92 53 76 47 ff bd e1 0f fe ...
D/wpa_supplicant( 4252): RSN: encrypted key data - hexdump(len=56): 23 49 86 74 21 51 72 b5 35 c6 ae 70 e3 6d ae 75 43 ce b8 89 4c 08 04 d4 92 51 22 34 d6 5e c3 39 ...
D/wpa_supplicant( 4252): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4252): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4252): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4252): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e6 70 ...
D/wpa_supplicant( 4252): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4252): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4252): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4252): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4252): WPA: Derived Key MIC - hexdump(len=16): 6f 95 90 92 b4 52 ea dc 9b 8a a8 4f ec 2c c6 5c
,D/wpa_supplicant( 4252): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
E/BatteryObserver( 1155): usb Uevent not necessary.
D/wpa_supplicant( 4252): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb875cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4252):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4252): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4252): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
D/wpa_supplicant( 4252): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4252): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
,D/wpa_supplicant( 4252): WPA: RSC - hexdump(len=6): e8 6b 00 00 00 00
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ee403a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4252):    broadcast key,
I/wpa_supplicant( 4252): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: Cancelling authentication timeout
,D/wpa_supplicant( 4252): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4252): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4252): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4252): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 4252): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4252): EAPOL: External notification - EAP success=1,
D/wpa_supplicant( 4252): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4252): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4252): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4252): EAPOL: SUPP_PAE entering state AUTHENTICATED,
D/wpa_supplicant( 4252): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4252): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4252): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4252): EAPOL authentication completed successfully
,D/wpa_supplicant( 4252): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4252): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4252): nl80211: if_removed already cleared - ignore event
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
W/WifiMonitor(  966): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): Network connection established
D/WifiNative-wlan0(  966): doString: STATUS
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4252): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  966):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  966): ssid=NG700
D/WifiNative-wlan0(  966): id=0
D/WifiNative-wlan0(  966): mode=station
D/WifiNative-wlan0(  966): pairwise_cipher=CCMP
D/WifiNative-wlan0(  966): group_cipher=CCMP
D/WifiNative-wlan0(  966): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  966): wpa_state=COMPLETED
D/WifiNative-wlan0(  966): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  966): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  966): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  966): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
D/WifiStateMachine(  966): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  966): invokeExitMethods: DisconnectedState
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  966): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  966): invokeEnterMethods: ObtainingIpState
D/WifiService(  966): New client listening to asynchronous messages
,I/ActivityManager(  966): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4395 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/DhcpStateMachine(  966): StoppedState
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/DhcpStateMachine(  966): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): WaitBeforeStartState
,D/WifiStateMachine(  966): ObtainingIpState{ when=-66ms what=147462 obj=android.net.wifi.StateChangeResult@43d05ba8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-60ms what=147462 obj=android.net.wifi.StateChangeResult@43d06288 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-61ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ObtainingIpState
,D/WifiStateMachine(  966): ObtainingIpState{ when=-28ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=196612
,D/WifiStateMachine(  966): processMsg: ObtainingIpState
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiStateMachine(  966): ObtainingIpState{ when=-10ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 1
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/HyLog   ( 4395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4395): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4395): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4395): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4395): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4395): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4395): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4395): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4395): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4395): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4395): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  966): Killing 3986:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  966): doBoolean: SET ps 0
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4252): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  966):    returned null
E/WifiStateMachine(  966): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  966):    returned null
E/WifiStateMachine(  966): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/WifiStateMachine(  966): handleMessage: X
D/DhcpStateMachine(  966): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  966): DHCP Start wake lock is acquired.
D/WifiP2pService(  966): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd140 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433bd140 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  966): battery changed pluggedType: 2
,D/DhcpStateMachine(  966): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  966): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4160): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4160): 
,D/wpa_supplicant( 4252): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4252): EAPOL: disable timer tick
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131212
,D/WifiStateMachine(  966): processMsg: ObtainingIpState
,D/WifiStateMachine(  966): ObtainingIpState{ when=-1ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  966): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  966): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  966): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
,V/LgDhcpStateMachineHelper(  966): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  966): bShouldSendDhcpAction Result: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=196613
,D/WifiStateMachine(  966): processMsg: ObtainingIpState
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/WifiStateMachine(  966): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): DHCP Start/Renew wake lock is released.
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  966): doBoolean: SET ps 1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  966): RunningState
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4252): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4252): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4252): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiP2pService(  966): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): DHCP successful
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  966): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState enter
D/WifiStateMachine(  966): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,W/WifiStateTracker(  966): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  966): 
W/WifiStateTracker(  966):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  966):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=135190
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  966): processMsg: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  966): transitionTo: destState=CaptivePortalCheckState
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  966): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): CaptivePortalCheckState enter
D/WifiStateMachine(  966): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  966): handleMessage: X
D/QcConnectivityService(  966): handleConnectivityChange: preConnState=0 connState=2
D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  966): handleMessage: E msg.what=131092
D/WifiStateMachine(  966): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  966): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  966): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  966): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  966): transitionTo: destState=ConnectedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  966): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  966): handleConnectivityChange: preConnState=2 connState=1
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/        (  265): RouteController
,D/QRemote ( 4395): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,V/        (  265): RouteController
,I/QRemote ( 4395): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4395): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4395): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,V/        (  265): RouteController
,V/        (  265): RouteController
,D/PCSuite ( 4272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  265): RouteController
,D/QRemote ( 4395): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4395): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/QRemote ( 4395): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4395): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  265): RouteController
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| net type = 1
V/QCNEA   (  400): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| Received ssid= NG700
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb8d5c8dc
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,D/GpsLocationProvider(  966): NTP server returned: 1450226414867 (Wed Dec 16 01:40:14 CET 2015) reference: 115808 certainty: 27 system time offset: 1164
,E/LocSvc_afw(  966): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  966): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  966): V/time: 1450226414867
E/LocSvc_eng(  966):   timeReference: 115808
E/LocSvc_eng(  966):   uncertainty: 27
E/LocSvc_utils_q(  966): D/msg_q_snd: Sending message with handle = 0x672FC0D8
E/LocSvc_utils_ll(  966): D/linked_list_add: Adding to list data_obj = 0x672FC0D8
E/LocSvc_utils_q(  966): D/msg_q_snd: Finished Sending message with handle = 0x672FC0D8
E/LocSvc_eng(  966): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
E/LocSvc_utils_ll(  966): D/linked_list_remove: Removing from list
E/LocSvc_afw(  966): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_utils_q(  966): D/msg_q_rcv: Received message 0x672FC0D8 rv = 0
E/LocSvc_eng(  966): V/time: 1450226414867
E/LocSvc_eng(  966):   timeReference: 115808
E/LocSvc_eng(  966):   uncertainty: 27
E/LocSvc_ApiV02(  966): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 27
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 56, req_id 56 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 56, len = 16
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 56, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 56 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  966): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  966): D/msg_q_rcv: Waiting on message
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  966): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  966): handleMessage: E msg.what=131212
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/GpsLocationProvider(  966): calling native_inject_xtra_data
,E/LocSvc_afw(  966): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  966): V/length: 57650
E/LocSvc_eng(  966):   data: 0x66972008
E/LocSvc_utils_q(  966): D/msg_q_snd: Sending message with handle = 0x670EB3E8
,E/LocSvc_utils_ll(  966): D/linked_list_add: Adding to list data_obj = 0x670EB3E8
E/LocSvc_utils_ll(  966): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  966): D/msg_q_rcv: Received message 0x670EB3E8 rv = 0
E/LocSvc_eng(  966): V/length: 57650
E/LocSvc_eng(  966):   data: 0x66972008
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 57650
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/57, len = 1024, total injected = 0
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_utils_q(  966): D/msg_q_snd: Finished Sending message with handle = 0x670EB3E8
,E/LocSvc_afw(  966): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/57, len = 1024, total injected = 1024
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/57, len = 1024, total injected = 2048
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/57, len = 1024, total injected = 3072
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/57, len = 1024, total injected = 4096
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind pay,load size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/57, len = 1024, total injected = 5120
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8,
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/57, len = 1024, total injected = 6144
,E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/57, len = 1024, total injected = 7168
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/57, len = 1024, total injected = 8192
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/57, len = 1024, total injected = 9216
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/WifiStateMachine(  966): handleMessage: X
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/57, len = 1024, total injected = 10240
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/57, len = 1024, total injected = 11264
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called ,
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/57, len = 1024, total injected = 12288
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/57, len = 1024, total injected = 13312
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/57, len = 1024, total injected = 14336
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/QcConnectivityService(  966): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  966):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  966): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/57, len = 1024, total injected = 15360
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/5,7, len = 1024, total injected = 16384
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/57, len = 1024, total injected = 17408
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0,
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/57, len = 1024, total injected = 18432
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/57, len = 1024, total injected = 19456
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/57, len = 1024, total injected = 20480
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/57, len = 1024, total injected = 21504
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/57, len = 1024, total injected = 22528
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/57, len = 1024, total injected = 23552
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/57, len = 1024, total injected = 24576
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/57, len = 1024, total injected = 25600
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/57, len = 1024, total injected = 26624
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/57, len = 1024, total injected = 27648
,E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/57, len = 1024, total injected = 28672
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/57, len = 1024, total injected = 29696
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/57, len = 1024, total injected = 30720
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/57, len = 1024, total injected = 31744
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/57, len = 1024, total injected = 32768
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/57, len = 1024, total injected = 33792
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/57, len = 1024, total injected = 34816
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/57, len = 1024, total injected = 35840
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/57, len = 1024, total injected = 36864
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/57, len = 1024, total injected = 37888
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/57, len = 1024, total injected = 38912
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/57, len = 1024, total injected = 39936
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/57, len = 1024, total injected = 40960
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/57, len = 1024, total injected = 41984
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/57, len = 1024, total injected = 43008
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/57, len = 1024, total injected = 44032
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/57, len = 1024, total injected = 45056
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called ,
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/57, len = 1024, total injected = 46080
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/57, len = 1024, total injected = 47104
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/57, len = 1024, total injected = 48128
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/57, len = 1024, total injected = 49152
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/57, len = 1024, total injected = 50176
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/57, len = 1024, total injected = 51200
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/57, len = 1024, total injected = 52224
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
,E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/57, len = 1024, total injected = 53248
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/57, len = 1024, total injected = 54272
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/57, len = 1024, total injected = 55296
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
,E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/57, len = 1024, total injected = 56320
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  966): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/57, len = 306, total injected = 57344
E/LocSvc_api_v02(  966): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  966): V/loc_sync_select_ind:356]: client handle 0x6737d528, ind_id 53, req_id 53 
E/LocSvc_api_v02(  966): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  966): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  966): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  966): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  966): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  966): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
,E/LocSvc_api_v02(  966): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  966): battery changed pluggedType: 2
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,E/LocSvc_api_v02(  966): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6737d528
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  966): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  966): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6737d528, resp id = 53, client cookie ptr = 0x673894f0
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:165]: received indication, handle = 0x6737d528 ind_id = 53 
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  966): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  966): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  966): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  966): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  966): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57650
E/LocSvc_MsgTask(  966): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  966): D/msg_q_rcv: Waiting on message
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/        (  966): Setting time of day to sec=1450226417
,W/        (  966): Unable to set rtc to 1450226417: Invalid argument
,D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=-7ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1155): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226417666, nextTick: 42361, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226417671, nextTick: 42359, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,I/MusicWidget( 2101): intentReceiver onReceive() action::android.intent.action.TIME_SET
,D/WeatherService( 1873): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:40:17
,I/[LGHome]LGCalendarIcon( 1488): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 16
,I/MusicWidget( 2101): beingMusicWidget_4x2() result::false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/MusicWidget( 2101): beingMusicWidget_Lock() result::false
,I/MusicWidget( 2101): beingMusicWidget_Quick() result::false
,I/MusicWidget( 2101): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2101): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2101): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2101): performUpdate()_4x1
,I/[LGHome]LGCalendarIcon( 1488): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 16
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/MusicWidget( 2101): status::mounted
D/Tethering(  966): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/WeatherService( 1873): 2 : requestRefreshAppWidget, isUpdateStart : false
I/MusicWidget( 2101): defaultAppWidget()_4x1
I/MusicWidget( 2101): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
I/MusicWidget( 2101): setDefaultViewLayoutId()_4x1
,I/MusicWidget( 2101): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2101): linkButtons()_4x1
D/UpdateThreadPoolManager( 1873): 2 : This is isUpdating : false
D/WeatherService( 1873): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1873): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1873): 2 : Map key string is -2
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/lim     ( 1873): 2 : time = 01:40
I/WeatherReflect( 1873): Model Name : LG-D802
D/WeatherTheme( 1873): 2 : Different view - status_min_formatted : 38 != 40
D/WeatherTheme( 1873): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1873): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1873): 2 : Fixed theme : optimus
,D/WeatherTheme( 1873): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1873): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:40:17
,I/MusicWidget( 2101): pushUpdate()_4x1
,I/MusicWidget( 2101): performViewUpdater handleMessage() msg.what::3
,I/MusicWidget( 2101): beingMusicWidget_Quick() result::false
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3657): onReceive
,D/AppUp4:CustFacade( 3657): Context : android.app.ReceiverRestrictedContext@42889fb8
D/AppUp4:CustFacade( 3657): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3657): isOpenOperator : true
,D/AppUp4:CustFacade( 3657): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 3657): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3657): begin check event
,I/AppUp4:CustModeStarterReceiver( 3657): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3657): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3657): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3657): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3657): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3657): handleAsyncCustNotification do not startCustService
,I/GoogleURLConnFactory( 1531): Using platform SSLCertificateSocketFactory
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  966): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4557 uid=10063 gids={50063, 3003, 1028, 1015}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  966): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4567 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HyLog   ( 4557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4557): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiController(  966): battery changed pluggedType: 2
,D/HyLog   ( 4567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4567): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/MusicWidget( 2101): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2101): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2101): beingMusicWidget_Lock() result::false
,V/DownloadManager( 4567): DownloadService onCreate
,I/DownloadManager( 4567): in removeSpuriousFiles
,D/EAS     ( 4065): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4065): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428b2b10 on behalf of 4567
,D/eas_req ( 4065): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4567): in trimDatabase
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428b5ee8 on behalf of 4567
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428b8318 on behalf of 4567
,I/ActivityManager(  966): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4597 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/linker  ( 4065): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4065): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4065): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4065): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4065): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428bc370 on behalf of 4567
D/HtmlEditor( 4065): register_HtmlEditor, Success
D/HtmlEditor( 4065): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4065): register_HtmlEditorTimer, Success
D/HtmlEditor( 4065): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4065): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4065): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4065): register_HtmlEditorFont, Success
D/HtmlEditor( 4065): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4065): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4065): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4065): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4065): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4065): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4065): JNI_OnLoad Success
I/HubEmail( 4065): JNI_OnLoad()
I/HubEmail( 4065): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4065): registerNatives()
I/HubEmail( 4065): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4065): registerNativeMethods()
I/HubEmail( 4065): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4065): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4597): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4567): DownloadService onDestroy
,D/DelayedSyncController( 4557): Delaying sync.
,I/ConversationSkinProvider( 4597): skin provider oncreate
,W/DriveInitializer( 1948): Background init thread started
,E/[MMS]   ( 4597): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
,I/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
,D/[MMS]   ( 4597): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4597): MmsSettings: Matching Xml Data file name = 2131034168
,I/VacuumService( 1531): Vacuum at: now=1450226418135 tag=VacuumService
,E/Auth.Api.Credentials( 1948): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager(  966): Killing 4023:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 1531): GC_EXPLICIT freed 720K, 29% free 17875K/24832K, paused 1ms+3ms, total 27ms
,D/[MMS]   ( 4597): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4597): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4597): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_dr = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_size = [300]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4597): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4597): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4597): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_recipient_length = [64]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4597): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_validity_invisible = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   inline_msg_item = [1]
W/DriveInitializer( 1948): Awaiting to be initialized
D/[MMS]   ( 4597): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4597): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4597): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   addr_len_check = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   online_album_dest_num = [000]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   sms_sent_time_mode = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   save_to_draft = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4597): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4597): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
,E/[MMS]   ( 4597): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4597): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,W/DriveInitializer( 1948): Background init thread ended
,I/[MMS]   ( 4597): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4597): _DRM_ServiceGet() : Bind lgdrm service
,E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b74919d8
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,D/Finsky  ( 3730): [336] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
,E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
,D/Finsky  ( 3730): [1] 5.onFinished: Installation state replication succeeded.
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b74919f0
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
,E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4597): isDrmV1 =true
,V/DrmWrapper( 4597): isDrmV2 =false
V/MmsConfig( 4597): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4597): [setMmsEnabledWhenDataDisabled]enabled=true
,I/ActivityManager(  966): Killing 3677:com.android.contacts/u0a21 (adj 15): empty #17
,V/MmsConfigStaticVar( 4597): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4597): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4597): Contact init()_Create new insatnce
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 1948): GC_CONCURRENT freed 1138K, 23% free 19259K/24832K, paused 3ms+2ms, total 31ms
,I/MessagingNotification( 4597): registerLEDObserver
,I/MessagingNotification( 4597): registerLEDObserver REGISTER
,D/DelayedSyncController( 4557): Delaying sync.
,V/MmsConfig( 4597): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/CountryDetector(  966): The first listener is added
,I/LOG_TAG ( 4597): registerContactDBChangeObserver
I/LgeMiscReceiver( 4597): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4597): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4597): networkInfo.isConnected() = false
,V/LGRssiData( 4597): [loadRssi] File not exist 
V/LGRssiData( 4597): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4597): [loadFeatureFromXml] *** start feature loading from xml
,E/ActivityThread( 4597): Failed to find provider info for com.lge.ims.provider.uc
V/TelephonyAutoProfiling( 4597): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4597): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4597): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  966): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4650 uid=10052 gids={50052, 3003}
I/ActivityManager(  966): Killing 4082:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4650): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4650): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/LocationManagerService(  966): getProviders()=[passive, gps]
,D/HyLog   ( 4650): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationManagerService(  966): request 4296d8c8 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
,D/dalvikvm(  966): GC_EXPLICIT freed 2563K, 49% free 29144K/56808K, paused 2ms+9ms, total 108ms
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4650): [loadRssi] File not exist 
,V/LGRssiData( 4650): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4650): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4650): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4650): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4650): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4650): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4650): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4650): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4650): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4650): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  966): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4668 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  966): Killing 1861:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/CheckinService( 1948): Checking schedule, now: 1450226418409 next: 1450212574903
,I/CheckinService( 1948): active receiver: enabled
D/HyLog   ( 4668): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4668): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4668): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinService( 1948): Preparing to send checkin request
,I/EventLogService( 1948): Accumulating logs since 1450225966406
,D/DrmBroadcastReceiver( 4668): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4337): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  966): Killing 4258:com.lge.settings.easy/1000 (adj 15): empty #17
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NFS     ( 4350): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4350): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4684 uid=10104 gids={50104, 3003, 1028, 1015}
,D/dalvikvm(  269): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
D/HyLog   ( 4684): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4684): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4684): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,W/GAV2    ( 4684): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 1948): Checkin reason type: 8 attempt count: 1
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiService(  966): New client listening to asynchronous messages
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
E/ActivityThread( 1948): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4684): Binding Chromium to the main looper Looper (main, tid 1) {42874aa8}
,I/chromium( 4684): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4684): Initializing chromium process, renderers=0
,W/chromium( 4684): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4684): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4684): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4684): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4684): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4684): Remote Branch: 
I/Adreno-EGL( 4684): Local Patches: 
I/Adreno-EGL( 4684): Reconstruct Branch: 
,W/BaseRuntimeLoader( 1948): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1948): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1948): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1948): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/NSApplication( 4684): Starting up...
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/ActivityManager(  966): Killing 4046:com.lge.bnr/1000 (adj 15): empty #17
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 3708): GC_FOR_ALLOC freed 739K, 16% free 20909K/24832K, paused 15ms, total 22ms
,I/dalvikvm-heap( 3708): Grow heap (frag case) to 26.501MB for 4099024-byte allocation
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/iu.SyncManager( 1948): SYNC; picasa accounts
,D/NetworkLogImpl( 1948): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1948): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/dalvikvm( 3708): GC_CONCURRENT freed 38K, 14% free 24894K/28836K, paused 2ms+1ms, total 18ms
,I/iu.UploadsManager( 1948): num queued entries: 0
,I/iu.UploadsManager( 1948): num updated entries: 0
,I/iu.SyncManager( 1948): NEXT; no task
,W/CheckinRequestBuilder( 1948): awaiting user notification for token
I/ActivityManager(  966): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4727 uid=10010 gids={50010, 3003, 1028, 4002}
D/NotificationService(  966): updateLightListLocked :r=null, action=2
,D/HyLog   ( 4727): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4727): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4727): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/OpenGL ES Test( 4727): getCurrentLocale == en_US
,E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
,E/OpenGL ES Test( 4727): localeFound retString == en_US
,D/ALBootInit( 4727): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 4727): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4727): [setNextAlert] start
I/ActivityManager(  966): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4739 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Alarms  ( 4727): [setNextAlert] (1)
,D/Alarms  ( 4727):  minTime  = 0
D/HyLog   ( 4739): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4739): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4739): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Alarms  ( 4727):  -- OK multi -- 0
E/jeny.kim( 4727): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4727): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4727): setStatusBarIcon : false
,D/Alarms  ( 4727): Enter formatDayAndTime(final Context context, long timeInMiliSec)
W/dalvikvm( 4739): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4739): VFY: replacing opcode 0x60 at 0x000b
,D/WorldClockReceiver( 4727): ====action==>android.intent.action.TIME_SET
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
D/dalvikvm( 4739): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4739): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4739): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4739): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4739): install
,I/MultiDex( 4739): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,E/OpenGL ES Test( 4727): isExistDatabase = false
,I/MultiDex( 4739): loading existing secondary dex files
,I/MultiDex( 4739): load found 3 secondary dex files
I/MultiDex( 4739): install done
I/CommonUtil( 4727): BUILD Country: EU
E/OpenGL ES Test( 4727): loadMapCityData() -- S
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
,E/OpenGL ES Test( 4727): localeFound retString == en_US
,D/dalvikvm( 4739): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4739): VFY: unable to resolve instance field 61
,D/dalvikvm( 4739): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4739): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4739): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4739): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4739): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4739): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4739): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4739): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4739): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4739): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428712a0
D/dalvikvm( 4739): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428712a0
,D/dalvikvm( 4739): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428712a0, skipping init
,D/dalvikvm( 4739): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428712a0
D/dalvikvm( 4739): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428712a0
E/OpenGL ES Test( 4727): loadMapCityData() - While S
,V/JNIHelp ( 4739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/dalvikvm( 4739): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428712a0
,D/dalvikvm( 4739): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428712a0
D/dalvikvm( 4739): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428712a0
,D/dalvikvm( 4739): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428712a0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/OpenGL ES Test( 4727): loadMapCityData() - While E
E/OpenGL ES Test( 4727): loadMapCityData() -- E
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
E/OpenGL ES Test( 4727): getCurrentLocale == en_US
E/OpenGL ES Test( 4727): localeFound retString == en_US
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,E/OpenGL ES Test( 4727): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  966): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4756 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  966): Killing 4272:com.lge.sync/1000 (adj 15): empty #17
,D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4756): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4756): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ProviderInstaller( 4739): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/Config  ( 4756): LGCalendar ver.4.2.6
I/Config  ( 4756): start check model
,I/Config  ( 4756): start check native_ca
,E/Config  ( 4756): [setCountryAndOperator] Operator=OPEN, Country=EU
I/dalvikvm( 4739): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4739): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4739): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4739): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4739): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4739): VFY: replacing opcode 0x6e at 0x0201
,I/ConfigFetchService( 1948): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1948): running network task: configservice_periodic
,E/WakeLock( 1948): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1948): launchTask
,I/ConfigService( 1531): onCreate
,D/GCM     ( 1531): Connected
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GoogleURLConnFactory( 1531): Using platform SSLCertificateSocketFactory
,I/ConfigFetchService( 1948): service connected
,D/ConfigFetchService( 1948): ConfigApi connection successful.
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1531): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1531): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/Uploader( 1531): No account for auth token provided
,D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  272): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  272): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  272): App is not loaded in QSEE
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
D/CalendarWidget( 4756): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,I/InitNotificationRingtoneService( 4756): Start InitializeAlertRingtoneService.onHandleIntent
,D/QSEECOMAPI: (  272): Loaded image: APP id = 2
,D/DrmWidevineDash(  272): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2172000
,E/DrmWidevineDash(  272): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2172000
,I/ActivityManager(  966): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4792 uid=10016 gids={50016, 3003, 1028, 1015}
,D/DrmWidevineDash(  272): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  272): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  272): calling OEMCrypto_IsKeyboxValid...
,D/HyLog   ( 4792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4792): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/InitNotificationRingtoneService( 4756): internal content query returns 1 results.
D/DrmWidevineDash(  272): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  272): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/InitNotificationRingtoneService( 4756): Found default schedule notification : Schedule.ogg(id:42)
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,I/InitNotificationRingtoneService( 4756): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4756): End InitializeAlertRingtoneService.onHandleIntent
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,I/CalendarProvider2( 4792): Created com.android.providers.calendar.CalendarAlarmManager@4288aab8(com.android.providers.calendar.CalendarProvider2@42881a20)
D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=3098734945
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager(  966): Killing 4395:com.lge.qremote/u0a96 (adj 15): empty #17
,D/dalvikvm( 4739): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78d48
D/dalvikvm( 4739): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78d48
,D/dalvikvm( 4739): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78d48, skipping init
I/ActivityManager(  966): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4809 uid=10043 gids={50043, 3003, 1028, 1015}
I/ActivityManager(  966): Killing 3730:com.android.vending/u0a50 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4809): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4809): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4809): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,W/Uploader( 1531):  no longer exists, so no auth token.
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,E/TASKS   ( 4809): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/dalvikvm( 1531): GC_CONCURRENT freed 1767K, 28% free 18110K/24832K, paused 2ms+3ms, total 33ms
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/TASKS_APP_WIDGET( 4809): onReceive() #################################################
,I/TASKS   ( 4809): getCurrentThemeInfo START #############################
I/TASKS   ( 4809): com.lge.launcher2.theme.optimus
I/TASKS   ( 4809): com.lge.task
I/TASKS   ( 4809): getCurrentThemeInfo END #############################
I/TASKS   ( 4809): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4809): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4809): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  966): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4827 uid=10122 gids={50122}
,D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4827): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Uploader( 1531): No account for auth token provided
,D/dalvikvm( 4827): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42873ed8, skipping init
D/TimeService( 4827): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226419358
,D/        ( 4827): TimeServiceNative: User Time to be set is 1450226419358
D/QC-time-services( 4827): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4827): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4827): Lib:time_genoff_operation: pargs->ts_val = 1450226419358
D/QC-time-services(  409): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4827): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  409): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226419358
D/QC-time-services(  409): Daemon:genoff_opr: Base = 2, val = 1450226419358, operation = 0
D/QC-time-services(  409): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/22/70 12:25:7
D/QC-time-services(  409): Daemon:Value read from RTC seconds = 9635107000
D/QC-time-services(  409): Daemon:new time 1450226419358 
D/QC-time-services(  409): Daemon: delta 1440591312358 genoff 1440591312358 
D/QC-time-services(  409): Daemon:genoff_persistent_update: Writing genoff = 1440591312358 to memory
D/QC-time-services(  409): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  409): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  409): Updating the TOD offset
D/QC-time-services(  409): Daemon:genoff_persistent_update: Writing genoff = 1440591312358 to memory
D/QC-time-services(  409): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  409): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  409): Daemon:Update to modem bit set
D/QC-time-services(  409): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  409): Daemon: Base = 2, Value being sent to MODEM = 1134261619358
,E/QC-time-services( 4827): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  409): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  409): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  966): Killing 2963:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 3657): Removing dead content provider:android.content.ContentProviderProxy@428c6280
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3657): onReceive
,D/AppUp4:CustFacade( 3657): Context : android.app.ReceiverRestrictedContext@42889fb8
D/AppUp4:CustFacade( 3657): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3657): isOpenOperator : true
,D/AppUp4:CustFacade( 3657): isPhone : true
,W/Uploader( 1531): No account for auth token provided
,I/ActivityManager(  966): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=4841 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/dalvikvm( 4739): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4853): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,W/Uploader( 1531): No account for auth token provided
D/dalvikvm( 4739): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4739): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 66ms
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/Adreno-EGL( 4739): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4739): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4739): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4739): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4739): Remote Branch: 
I/Adreno-EGL( 4739): Local Patches: 
I/Adreno-EGL( 4739): Reconstruct Branch: 
W/ProcessCpuTracker(  966): Skipping unknown process pid 4853
,D/dalvikvm(  966): GC_EXPLICIT freed 1129K, 49% free 29418K/56808K, paused 2ms+7ms, total 108ms
,D/HyLog   ( 4841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4841): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,I/LicenseContentProvider( 4841): start selecting data
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 4841): simInfo1
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/AppUp4:EulaManager( 3657): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3657): begin check event
,I/AppUp4:CustModeStarterReceiver( 3657): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4567): DownloadService onCreate
,I/DownloadManager( 4567): in removeSpuriousFiles
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428c35d0 on behalf of 4567
D/EAS     ( 4065): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/EAS     ( 4065): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4567): in trimDatabase
V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428c5420 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428c7158 on behalf of 4567
I/LgeMiscReceiver( 4597): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4597): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4597): networkInfo.isConnected() = true
,D/PhoneState( 4597): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4650): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4650): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4065): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmBroadcastReceiver( 4668): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4668): 1  network is available. Sync DRM Time with NTP
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  272): PrepareKeyRequest: nonce=2975464300
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
V/DrmService( 4668): Service onCreate
,D/DrmService( 4668): Received new request = 2
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 4668): Start Sync process
,D/DrmSntpClient( 4668): Server : 0
,E/DataScheduler( 4668): isDataSchedulerEnabled():false
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/LGDMSGCM( 4337): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/DownloadManager( 4567): DownloadService onDestroy
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4350): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4350): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3708): GC_FOR_ALLOC freed 9K, 14% free 24888K/28836K, paused 10ms, total 10ms
,I/dalvikvm-heap( 3708): Grow heap (frag case) to 30.387MB for 4099024-byte allocation
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/dalvikvm( 3708): GC_CONCURRENT freed 4K, 13% free 28892K/32840K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 3708): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received.
,I/dalvikvm-heap( 3708): Grow heap (frag case) to 34.297MB for 4099024-byte allocation
W/ActivityThread(  966): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/WeatherAncestor( 1873): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:19
,D/UpdateThreadPoolManager( 1873): 2 : This is isUpdating : false
,D/Weather_cast( 1873): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1873): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:19
,D/WeatherService( 1873): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,D/WeatherQuickCover( 1873): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1873): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1873): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : false
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1531): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1948): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/ActivityManager(  966): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4867 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/LocationInitializer( 1948): Restart initialization of location
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
D/HyLog   ( 4867): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4867): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4867): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4883 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,W/dalvikvm( 4867): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4867): VFY: replacing opcode 0x60 at 0x000b
D/HyLog   ( 4883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4883): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm( 4867): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4867): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4867): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4867): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4867): install
,I/MultiDex( 4867): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4867): loading existing secondary dex files
,I/MultiDex( 4867): load found 3 secondary dex files
,I/MultiDex( 4867): install done
,D/dalvikvm( 4867): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4867): VFY: unable to resolve instance field 61
,D/dalvikvm( 4867): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4867): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4867): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4867): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4867): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4867): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4867): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4867): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4867): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4867): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42877488
D/dalvikvm( 4867): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42877488
,D/dalvikvm( 4867): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42877488, skipping init
,D/dalvikvm( 4867): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42877488
D/dalvikvm( 4867): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42877488
,V/JNIHelp ( 4867): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WifiServiceExtension(  966): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Babel   ( 4883): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4883): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4883): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4883): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 4883): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4883): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
D/dalvikvm( 4867): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42877488
,D/dalvikvm( 4867): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42877488
D/dalvikvm( 4867): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42877488
,D/dalvikvm( 4867): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42877488
I/Babel   ( 4883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4883): MmsConfig.loadFromDatabase
,W/Settings( 4883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4883): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4883): MmsConfig.loadFromResources
,V/LGRssiData( 4883): [loadRssi] File not exist 
V/LGRssiData( 4883): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4883): [loadFeatureFromXml] *** start feature loading from xml
,E/Babel   ( 4883): canonicalizeMccMnc: invalid mccmnc nullnull
V/TelephonyAutoProfiling( 4883): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 4883): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4883): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/Babel   ( 4883): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3657): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3657): onReceive
D/AppUp4:CustFacade( 3657): Context : android.app.ReceiverRestrictedContext@42889fb8
D/AppUp4:CustFacade( 3657): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3657): isOpenOperator : true
,D/AppUp4:CustFacade( 3657): isPhone : true
,I/LicenseContentProvider( 4841): start selecting data
,D/SIMObserver( 4841): simInfo1
,I/AppUp4:EulaManager( 3657): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3657): begin check event
,I/AppUp4:CustModeStarterReceiver( 3657): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4567): DownloadService onCreate
D/EAS     ( 4065): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4065): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4567): in removeSpuriousFiles
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428cb2e0 on behalf of 4567
,I/LgeMiscReceiver( 4597): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4597): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4597): networkInfo.isConnected() = true
,D/PhoneState( 4597): setPdpRejectCasuse : false
,I/DownloadManager( 4567): in trimDatabase
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/MobileConnectivityChangeReceiver( 4650): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4650): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4065): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428cccd8 on behalf of 4567
,I/ProviderInstaller( 4867): Installed default security provider GmsCore_OpenSSL
D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428cee48 on behalf of 4567
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4337): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4567): DownloadService onDestroy
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,I/NFS     ( 4350): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4350): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/CalendarWidget( 4756): Agenda AppWidgetService init broadcastReceiver
D/CalendarWidget( 4756): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/dalvikvm( 4867): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4867): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
D/dalvikvm( 4867): VFY: replacing opcode 0x6e at 0x003f
D/TASKS_APP_WIDGET( 4809): onReceive() #################################################
I/TASKS   ( 4809): getCurrentThemeInfo START #############################
I/TASKS   ( 4809): com.lge.launcher2.theme.optimus
I/TASKS   ( 4809): com.lge.task
I/TASKS   ( 4809): getCurrentThemeInfo END #############################
I/TASKS   ( 4809): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4809): loadLocalResId #############################
D/TASKS_APP_WIDGET( 4809): intentAction : com.lge.task.APPWIDGET_UPDATE
D/CalendarWidget( 4756): Agenda AppWidgetService init broadcastReceiver
D/CalendarWidget( 4756): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/WearableService( 4867): callingUid 10006, callindPid: 4867
E/dalvikvm( 4867): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
D/GCM     ( 1531): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/dalvikvm( 4867): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
D/dalvikvm( 4867): VFY: replacing opcode 0x1f at 0x0054
W/dalvikvm( 4867): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 3708): GC_CONCURRENT freed 7K, 11% free 33053K/36844K, paused 2ms+13ms, total 38ms
D/AuthorizationBluetoothService( 1531): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1531): Proximity feature is not enabled.
V/GmsCoreStatsServiceLauncher( 1948): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.,stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 4867): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4867): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4867): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4867): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4867): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4867): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1948): Restart initialization of location
,E/MDM     ( 1423): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1423): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Adreno-EGL( 4739): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4739): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4739): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4739): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4739): Remote Branch: 
I/Adreno-EGL( 4739): Local Patches: 
I/Adreno-EGL( 4739): Reconstruct Branch: 
,I/Adreno-EGL( 4739): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4739): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4739): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4739): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4739): Remote Branch: 
I/Adreno-EGL( 4739): Local Patches: 
I/Adreno-EGL( 4739): Reconstruct Branch: 
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4883): UserRecoverableAuthException.
,E/Babel   ( 4883): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4883): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4883): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4883): Error getting auth token
,E/Babel   ( 4883): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4883): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4883): Account registration failedRedacted-21
,E/Babel   ( 4883): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4883): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4883): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4883): Account sign in complete with state 106account: Redacted-21
,W/Settings( 4739): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1948): Classify the device as Phone.
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/LGDrmService( 4668): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  276): [DRM] SET TIME : YR=2015, MON=12, DAY=16
,I/LGDRM   (  276): [DRM] SET TIME : HR=0, MIN=40, SEC=20
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/DrmSntpClient( 4668): Synched
D/DrmService( 4668): Completed !! request = 2
D/DrmService( 4668): Request count = 0
,V/DrmService( 4668): Service onDestroy
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/ActivityManager(  966): Killing 3692:com.android.gallery3d/u0a27 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,E/Babel   ( 4883): Unexpected exception while authenticating.
,E/Babel   ( 4883): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4883): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4883): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4883): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4883): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4883): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4883): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4883): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4883): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x432ae8c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/CalendarProvider2( 4792): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4792): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4756): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/CalendarWidget( 4756): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
D/AlertService( 4756): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 4756): Beginning updateAlertNotification
,D/AlertService( 4756): No fired or scheduled alerts
,D/CalendarWidget( 4756): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4756): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/ActivityManager(  966): Killing 4727:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1948): Sending checkin request (11659 bytes)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinResponseProcessor( 1948): From server: 3 gservices updates and 0 deletes
,I/CertBlacklister(  966): Certificate blacklist changed, updating...
,I/CertBlacklister(  966): Certificate blacklist updated
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GservicesProvider( 1531): main difference update completed
,I/ActivityManager(  966): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4940 uid=10003 gids={50003, 3003, 2001}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1948): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1948): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4940): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4940): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4940): Update started
,D/DownloadManager( 4567): DB Update : deleted 1
,V/DownloadManager( 4567): DownloadService onCreate
I/DownloadManager( 4567): in removeSpuriousFiles
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428d7970 on behalf of 4567
,I/DownloadManager( 4567): in trimDatabase
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/UpdateRequestReceiver( 4940): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428d9328 on behalf of 4567
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): initiating download with UID 10003
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428de300 on behalf of 4567
,V/DownloadManager( 4567): processing inserted download 181
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:190
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm( 1948): GC_CONCURRENT freed 1716K, 22% free 19468K/24832K, paused 2ms+4ms, total 42ms
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428e1b58 on behalf of 4567
,D/DownloadManager( 4567): DB Update : status 192
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428e51f0 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428e6360 on behalf of 4567
,I/UpdateFetcherService( 4940): Update started
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4433b6a8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,V/DownloadManager( 4567): processing updated download 181, status: 192
,D/DownloadManager( 4567): DB Update : deleted 1
,W/CheckinRequestBuilder( 1948): awaiting user notification for token
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): DownloadService onStartCommand
,I/DownloadManager( 4567): Download 181 starting
,E/UpdateRequestReceiver( 4940): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@428ea618 on behalf of 4567
,E/UpdateRequestReceiver( 4940): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4567): initiating download with UID 10003
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/CheckinRequestBuilder( 1948): Classify the device as Phone.
,D/DownloadManager( 4567): fileSize : -1state.mContinuingDownload :false
,E/DataScheduler( 4567): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  966): GC_EXPLICIT freed 2095K, 49% free 29499K/56808K, paused 4ms+6ms, total 87ms
,V/DownloadManager( 4567): DownloadService onStartCommand
,E/UpdateRequestReceiver( 4940): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429045b0 on behalf of 4567
,I/ActivityManager(  966): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4997 uid=10009 gids={50009, 3003}
V/DownloadManager( 4567): processing updated download 181, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@4290bab0 on behalf of 4567
,D/dalvikvm(  269): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
D/HyLog   ( 4997): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4997): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4997): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4567): processing inserted download 182
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=182:190
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42911a10 on behalf of 4567
,D/DownloadManager( 4567): DB Update : status 192
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,I/CheckinTask( 1948): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@4291ca80 on behalf of 4567
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,V/DownloadManager( 4567): processing updated download 181, status: 192
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@4291d5b0 on behalf of 4567
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@4291f6c0 on behalf of 4567
,I/DownloadManager( 4567): Download 182 starting
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/CheckinService( 1948): Checking schedule, now: 1450226421298 next: 1450803817285
I/CheckinService( 1948): active receiver: disabled
,V/DownloadManager( 4567): processing updated download 182, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=182:192
,D/DownloadManager( 4567): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42924510 on behalf of 4567
,W/BaseRuntimeLoader( 4997): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4997): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4997): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4997): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/ContactAccountLoggerTas( 2657): canRun() : Opted Out
I/CheckinService( 1948): Checking schedule, now: 1450226421357 next: 1450803817285
,I/CheckinService( 1948): active receiver: disabled
,I/Search.GservicesUpdateTask( 2657): Updating Gservices keys
,I/DownloadManager( 4567): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4567): Content-Disposition: null
V/DownloadManager( 4567): Content-Length: -1
,V/DownloadManager( 4567): Content-Location: null
V/DownloadManager( 4567): Content-Type: text/plain
V/DownloadManager( 4567): ETag: null
V/DownloadManager( 4567): Transfer-Encoding: chunked
,V/DownloadManager( 4567): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4567): Min update size = 16384
V/DownloadManager( 4567): getting filename from uri
,I/DownloadManager( 4567): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
V/DownloadManager( 4567): keeping extension
,V/DownloadManager( 4567): target file: /cache/10152015-sms-metadata.txt
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429823e0 on behalf of 4567
,D/DownloadManager( 4567): DB Update : title 10152015-sms-metadata.txt
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4567): DB Update : total_bytes -1
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@4298cbf0 on behalf of 4567
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4567): processing updated download 181, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/LGDrmService( 4567): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42996e30 on behalf of 4567
,D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): DB Update : current_bytes 383
,D/DownloadManager( 4567): DB Update : total_bytes 383
,V/DownloadManager( 4567): processing updated download 182, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=182:192
,D/dalvikvm( 1531): GC_EXPLICIT freed 1517K, 28% free 18089K/24832K, paused 1ms+4ms, total 50ms
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429a6200 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429acda0 on behalf of 4567
,V/LFT     ( 4567): notifyThroughDatabase after updateDB  id :  182, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4567): notifyThroughDatabase start id : 182 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): processing updated download 181, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429b0950 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429b1c60 on behalf of 4567
,D/DownloadManager( 4567): DB Update : numfailed 0
,D/DownloadManager( 4567): DB Update : method 0
D/DownloadManager( 4567): DB Update : lastmod 1450226421449
,D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4567): DB Update : status 200
,V/DownloadManager( 4567): processing updated download 182, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=182:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 1948): Checking schedule, now: 1450226421468 next: 1450803817285
,I/CheckinService( 1948): active receiver: disabled
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429b9d78 on behalf of 4567
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/DownloadManager( 4567): Download 182 finished with status SUCCESS
D/DownloadManager( 4567): checkStatusUpdate current status 192 is changed to 200
I/SystemUpdateService( 1948): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/DownloadManager( 4567): checkStatusUpdate return true mID : mStatus = 182 : 200 => 200
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429cb068 on behalf of 4567
,V/DownloadManager( 4567): processing updated download 181, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/SystemUpdateService( 1948): onCreate
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/ActivityManager(  966): Killing 4827:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,D/WifiController(  966): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@429cccd8 on behalf of 4567
,D/SystemUpdateService( 1948): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ContactAccountLoggerTas( 2657): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2657): canRun() : Opted Out
,D/SystemEventReceiver( 1948): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1948): Updating ocr activity enabled=false
,I/SystemUpdateService( 1948): cancelUpdate (empty URL)
,I/SystemUpdateService( 1948): active receiver: disabled
,D/GCM     ( 1531): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1423): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ContactAccountLoggerTas( 2657): canRun() : Opted Out
,D/SystemUpdateService( 1948): onDestroy
,I/GCoreUlr( 1423): DispatchingService.onCreate()
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
W/ActivityThread( 4567): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4311d100: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/Search.LoginHelper( 2657): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/Search.LoginHelper( 2657): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/ContactAccountLoggerTas( 2657): canRun() : Opted Out
,I/GCoreUlr( 1423): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/DownloadManager( 4567): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 4567): Content-Disposition: null
V/DownloadManager( 4567): Content-Length: -1
V/DownloadManager( 4567): Content-Location: null
V/DownloadManager( 4567): Content-Type: text/plain
V/DownloadManager( 4567): ETag: null
V/DownloadManager( 4567): Transfer-Encoding: chunked
,V/DownloadManager( 4567): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4567): Min update size = 16384
V/DownloadManager( 4567): getting filename from uri
I/DownloadManager( 4567): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 4567): keeping extension
,V/DownloadManager( 4567): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a86ce8 on behalf of 4567
,D/DownloadManager( 4567): DB Update : title 08202014-metadata.txt
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4567): DB Update : total_bytes -1
,I/GCoreUlr( 1423): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a897a8 on behalf of 4567
,D/dalvikvm( 1531): GC_EXPLICIT freed 465K, 28% free 18053K/24832K, paused 1ms+3ms, total 26ms
,I/GCoreUlr( 1423): Unbound from all location providers
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
,V/DownloadManager( 4567): processing updated download 181, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a94ef0 on behalf of 4567
D/DownloadManager( 4567): DB Update : current_bytes 384
,D/DownloadManager( 4567): DB Update : total_bytes 384
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4567): notifyThroughDatabase after updateDB  id :  181, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4567): notifyThroughDatabase start id : 181 name : /cache/08202014-metadata.txt status : 200
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a98ac0 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a99ad8 on behalf of 4567
,V/DownloadManager( 4567): processing updated download 181, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=181:192
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4567): DB Update : numfailed 0
D/DownloadManager( 4567): DB Update : method 0
,D/DownloadManager( 4567): DB Update : lastmod 1450226421714
D/DownloadManager( 4567): DB Update : mimetype text/plain
,D/DownloadManager( 4567): DB Update : _data /cache/08202014-metadata.txt
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a9c110 on behalf of 4567
,D/DownloadManager( 4567): DB Update : status 200
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/GCoreUlr( 1423): DispatchingService.onDestroy()
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42a9f030 on behalf of 4567
,I/DownloadManager( 4567): Download 181 finished with status SUCCESS
,I/GCoreUlr( 1423): Unbound from all location providers
,V/DownloadManager( 4567): DownloadService onDestroy
I/ActivityManager(  966): Killing 4841:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 3657): Removing dead content provider:android.content.ContentProviderProxy@428ddd68
,D/dalvikvm( 1948): GC_EXPLICIT freed 697K, 22% free 19452K/24832K, paused 3ms+5ms, total 44ms
,D/dalvikvm(  966): GC_EXPLICIT freed 1161K, 49% free 29521K/56808K, paused 2ms+7ms, total 111ms
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1531): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 182; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42aa3fe8 on behalf of 4940
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 182; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42aa7780 on behalf of 4940
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4567): initiating download with UID 10003
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/DownloadManager( 4567): DownloadService onCreate
I/DownloadManager( 4567): in removeSpuriousFiles
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42aadb78 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42aafe50 on behalf of 4567
I/DownloadManager( 4567): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 4567): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
V/DownloadManager( 4567): processing inserted download 181
I/DownloadManager( 4567): in trimDatabase
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ab2610 on behalf of 4567
,V/DownloadManager( 4567): processing inserted download 182
,V/DownloadManager( 4567): processing inserted download 183
V/LFT     ( 4567): isReadyToDownload mId, mStatus=183:190
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ab5560 on behalf of 4567
,D/DownloadManager( 4567): DB Update : status 192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 181; sort is lastmod DESC.
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42abb3c8 on behalf of 4940
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ab83f0 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 181; sort is lastmod DESC.
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42abd140 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ac0500 on behalf of 4940
,W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
V/DownloadManager( 4567): processing updated download 183, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=183:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ac2e18 on behalf of 4567
,I/DownloadManager( 4567): Download 183 starting
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 4567): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4567): initiating download with UID 10003
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ad1f58 on behalf of 4567
,V/DownloadManager( 4567): processing updated download 183, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=183:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ad4560 on behalf of 4567
I/DownloadManager( 4567): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 4567): Content-Disposition: null
V/DownloadManager( 4567): Content-Length: -1
V/DownloadManager( 4567): Content-Location: null
V/DownloadManager( 4567): Content-Type: text/plain
V/DownloadManager( 4567): processing inserted download 184
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:190
V/DownloadManager( 4567): ETag: null
V/DownloadManager( 4567): Transfer-Encoding: chunked
V/DownloadManager( 4567): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): Min update size = 16384
V/DownloadManager( 4567): getting filename from uri
I/DownloadManager( 4567): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
V/DownloadManager( 4567): keeping extension
,V/DownloadManager( 4567): target file: /cache/10152015-sms-blacklist.txt
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ad8200 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4567): DB Update : status 192
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ad9e00 on behalf of 4567
,D/DownloadManager( 4567): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4567): DB Update : total_bytes -1
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42adccc0 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42adf4b0 on behalf of 4567
,I/DownloadManager( 4567): Download 184 starting
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/LGDRM   (  276): [DRM] Part_DetectType() : Buffer contains XML Prologue
,D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,V/DownloadManager( 4567): processing updated download 183, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=183:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4567): transferData threadNum : -1
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ae32e8 on behalf of 4567
,D/DownloadManager( 4567): fileSize : -1state.mContinuingDownload :false
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4567): DB Update : current_bytes 13383
D/DownloadManager( 4567): DB Update : total_bytes 13383
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42aeff38 on behalf of 4567
,V/LFT     ( 4567): notifyThroughDatabase after updateDB  id :  183, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4567): notifyThroughDatabase start id : 183 name : /cache/10152015-sms-blacklist.txt status : 200
V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42af5428 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42af5658 on behalf of 4567
,D/DownloadManager( 4567): DB Update : numfailed 0
D/DownloadManager( 4567): DB Update : method 0
D/DownloadManager( 4567): DB Update : lastmod 1450226422084
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4567): DB Update : status 200
V/DownloadManager( 4567): processing updated download 183, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=183:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42af8c38 on behalf of 4567
D/DownloadManager( 4567): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4567): checkStatusUpdate return true mID : mStatus = 183 : 200 => 200
,V/DownloadManager( 4567): processing updated download 184, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4567): Download 183 finished with status SUCCESS
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42afad98 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42afd6a8 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 183; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b0a248 on behalf of 4940
,V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b0cb88 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 183; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b10440 on behalf of 4940
,W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4940): Update downloaded, starting installation
,I/UpdateFetcherService( 4940): Started installation
,D/DownloadManager( 4567): DB Update : deleted 1
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): DownloadService onStartCommand
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b3c9a8 on behalf of 4567
,D/DownloadManager( 4567): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4567): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b66090 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b68218 on behalf of 4567
,V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b6a218 on behalf of 4567
I/DownloadManager( 4567): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4567): Content-Disposition: null
V/DownloadManager( 4567): Content-Length: -1
V/DownloadManager( 4567): Content-Location: null
V/DownloadManager( 4567): Content-Type: text/plain
V/DownloadManager( 4567): ETag: null
,V/DownloadManager( 4567): Transfer-Encoding: chunked
V/DownloadManager( 4567): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4567): Min update size = 16384
V/DownloadManager( 4567): getting filename from uri
I/DownloadManager( 4567): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
,V/DownloadManager( 4567): keeping extension
,V/DownloadManager( 4567): target file: /cache/08202014-pins.txt
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b6dd28 on behalf of 4567
,D/DownloadManager( 4567): DB Update : title 08202014-pins.txt
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4567): DB Update : total_bytes -1
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4567): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b70b18 on behalf of 4567
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
V/DownloadManager( 4567): processing updated download 184, status: 192
,V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
D/DownloadManager( 4567): transferData threadNum : -1
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b7c560 on behalf of 4567
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): DB Update : current_bytes 32768
,V/DownloadManager( 4567): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b80d70 on behalf of 4567
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
D/DownloadManager( 4567): transferData threadNum : -1
,D/DownloadManager( 4567): transferData threadNum : -1
V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4567): DB Update : current_bytes 39938
,D/DownloadManager( 4567): DB Update : total_bytes 39938
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b83d10 on behalf of 4567
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4567): notifyThroughDatabase after updateDB  id :  184, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4567): notifyThroughDatabase start id : 184 name : /cache/08202014-pins.txt status : 200
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b87558 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b88458 on behalf of 4567
D/DownloadManager( 4567): DB Update : numfailed 0
D/DownloadManager( 4567): DB Update : method 0
D/DownloadManager( 4567): DB Update : lastmod 1450226422194
D/DownloadManager( 4567): DB Update : mimetype text/plain
D/DownloadManager( 4567): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4567): DB Update : status 200
,V/DownloadManager( 4567): processing updated download 184, status: 192
V/LFT     ( 4567): isReadyToDownload mId, mStatus=184:192
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b8b638 on behalf of 4567
,I/DownloadManager( 4567): Download 184 finished with status SUCCESS
,D/DownloadManager( 4567): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4567): checkStatusUpdate return true mID : mStatus = 184 : 200 => 200
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 184; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b8fac0 on behalf of 4940
,V/DownloadManager( 4567): DownloadService onDestroy
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 184; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b934e8 on behalf of 4940
,W/ContextImpl( 4940): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4940): Update downloaded, starting installation
,I/UpdateFetcherService( 4940): Started installation
,D/DownloadManager( 4567): DB Update : deleted 1
,V/DownloadManager( 4567): DownloadService onCreate
,I/DownloadManager( 4567): in removeSpuriousFiles
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b96fd8 on behalf of 4567
I/DownloadManager( 4567): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 4567): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
V/DownloadManager( 4567): DownloadService onStartCommand
,I/DownloadManager( 4567): in trimDatabase
V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4567): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b9ab48 on behalf of 4567
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42b9a930 on behalf of 4567
V/DownloadManager( 4567): processing inserted download 181
,D/DownloadManager( 4567): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 4567): processing inserted download 184
,D/DownloadManager( 4567): deleteFileIfExists() deleting /cache/08202014-pins.txt
,I/ConfigUpdateInstallReceiver(  966): Not installing, new version is <= current version
V/DownloadManager( 4567): DownloadService onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1155): GC_CONCURRENT freed 2912K, 11% free 25448K/28536K, paused 37ms+2ms, total 82ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.471619 Y: -0.401291 Z: 9.744034 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471619 .y:-0.401291 .z:9.744034
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.470184 Y: -0.422485 Z: 9.759644 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470184 .y:-0.422485 .z:9.759644
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/GAV2    ( 4684): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.,
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  966): Killing 3657:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  966): Killing 4065:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  966): Killing 4883:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GAV2    ( 3708): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  966): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  966): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  966): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  966): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  966): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,E/SlideAside( 3572): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3572): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  966): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5123 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,D/administrator(  966): Handling package changes for user 0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
E/SlideAside( 3572): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3572): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5123): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5123): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5123): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/AppUp4  ( 5123):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5123):  [AppBoxDatabaseHelper] construct
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 5123):  setFingerPrint start
,I/AppUp4  ( 5123):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5123):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5123):  beforefinger == newfinger no write in DB
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AppUp4:AppBoxApplication( 5123): AppBoxApplication onCreate()
,D/AppBoxBlacklist( 5123): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "sms"
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  966): Handling package changes for user 0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/PackageParser( 5123): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
D/AppUp4:Utils( 5123): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 5123): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5123): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/PackageParser( 5123): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/AppUp4:CustModeStarterReceiver( 5123): onReceive
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
D/AppUp4:CustFacade( 5123): Context : android.app.ReceiverRestrictedContext@42880340
,D/AppUp4:CustFacade( 5123): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5123): isOpenOperator : true
,D/AppUp4:CustFacade( 5123): isPhone : true
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  966): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5157 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5157): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LicenseContentProvider( 5157): start selecting data
,W/BaseRuntimeLoader( 5157): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5157): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5157): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5157): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5157): simInfo1
,I/AppUp4:EulaManager( 5123): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5123): begin check event
D/AppUp4:Utils( 5123): [getPackageName] uri : package:com.google.android.talk
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppUp4:CustModeStarterReceiver( 5123): Event For Nothing, skip.
,I/ActivityManager(  966): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5170 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  966): Killing 4557:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  966): Killing 4597:com.android.mms/u0a35 (adj 15): empty #18
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/ConfigFetchTask( 1948): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ULIOpdduooGVs14QivgvmUdblg41ZgkQVrzFiJu1SpXI6vqWZKnMso8upYm5n-hUSpO7PYNZsMfMMsRxLWfJJvn7JeupMW7F4zhISNdA-taM7eM6FZaXL-BHEnDwE4kAkM6GguJv22Ppm8CoqS1DA1hFX9G6oMxap7An0Psg2yNv4_Eztm2NcU_5-YvEXxozFF4prerDsYe7gvUnwH0i_HIldmXW3Pw5YYXOckhlggnF7POD4
D/CountryDetector(  966): No listener is left
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/HyLog   ( 5170): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5170): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5170): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/GmsNetworkLocationProvi( 1423): DISABLE
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5170): BUILD Country: EU
,I/SystemConfig( 5170): BUILD Operator: OPEN
I/SystemConfig( 5170): systemFeature RCS result false
,D/SystemConfig( 5170): refreshRcsSupport() :false
I/ActivityManager(  966): Killing 4668:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/GoogleURLConnFactory( 1948): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  966): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5191 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
I/LocationManagerService(  966): remove 4296d8c8
D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
D/LocationProviderProxy(  966): applying state to connected service
D/LocationProviderProxy(  966): applying state to connected service
,D/HyLog   ( 5191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5191): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  966): Killing 4337:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  966): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5208 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5208): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5208): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5208): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2657): UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
,I/dalvikvm( 5208): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5208): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x000b
,I/ConfigFetchTask( 1948): updating config table for com.google.android.gms
,D/dalvikvm(  966): GC_EXPLICIT freed 2500K, 48% free 29665K/56808K, paused 5ms+13ms, total 151ms
,I/ConfigFetchService( 1948): fetch service done; releasing wakelock
,I/ConfigFetchService( 1948): stopping self
,D/Finsky  ( 5208): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5208): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 5208): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5208): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5208): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5208): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5208): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5208): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5208): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5208): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5208): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5208): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5208): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5208): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5208): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5208): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x029a
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42ba4f70 on behalf of 5208
,I/dalvikvm( 5208): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5208): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5208): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5208): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5208): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5208): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5208): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5208): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1948): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 5208): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5248 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/ActivityManager(  966): Killing 4350:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,D/HyLog   ( 5248): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5248): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5248): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/PeopleContactsSync( 1948): CP2 sync disabled
,I/Babel   ( 5248): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5248): MmsConfig.loadMmsSettings
,I/Babel   ( 5248): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5248): MmsConfig.loadFromDatabase
I/MediaCodecList( 5248): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5248): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5248): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5248): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5248): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5248): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5248): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5248): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5248): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5248): MmsConfig.loadFromResources
E/Babel   ( 5248): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5248): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5248): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5248): [loadRssi] File not exist 
,V/LGRssiData( 5248): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5248): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 5123): [getPackageName] uri : package:com.google.android.gms
,V/TelephonyAutoProfiling( 5248): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5248): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5248): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4  ( 5123): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5123): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5123): onReceive
D/AppUp4:CustFacade( 5123): Context : android.app.ReceiverRestrictedContext@42880340
,D/AppUp4:CustFacade( 5123): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5123): isOpenOperator : true
D/AppUp4:CustFacade( 5123): isPhone : true
,I/LicenseContentProvider( 5157): start selecting data
,D/SIMObserver( 5157): simInfo1
,I/AppUp4:EulaManager( 5123): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5123): begin check event
D/AppUp4:Utils( 5123): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5123): Event For Nothing, skip.
,I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ConfigFetchService( 1948): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1948): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1948): GmsCore config value changed; rescheduling
,D/PackageBroadcastService( 1948): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1948): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  966): Delaying start of: ServiceRecord{44dd8aa8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ConfigFetchService( 1948): service connected
W/ConfigFetchService( 1948): ConfigApi client is not connected. Falling back to defaultfetch interval.
D/ConfigFetchService( 1948): ConfigApi connection successful.
,I/ConfigFetchService( 1948): stopping self
,I/ActivityManager(  966): Killing 4684:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 2 tasks}
,I/Icing   ( 1948): updateResources: need to parse f{com.google.android.gms}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2657): UpdateCorporaTask done [took 240 ms] updated apps [took 240 ms] 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5208): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5208): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5208): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5208): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm( 1531): GC_EXPLICIT freed 311K, 28% free 18059K/24832K, paused 3ms+10ms, total 59ms
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5208): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5208): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 5208): Total arena pages for JIT: 11
,I/dalvikvm( 5208): Total arena pages for JIT: 12
I/dalvikvm( 5208): Total arena pages for JIT: 13
,I/dalvikvm( 5208): Total arena pages for JIT: 14
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5208): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5208): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5208): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5208): [1] DailyHygiene.reschedule: Giving up. (failures=6)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  966): Skipping PackageSetting{42d23d70 com.example.hello/10312} due to missing metadata
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,W/ProcessCpuTracker(  966): Skipping unknown process pid 5324
,W/ProcessCpuTracker(  966): Skipping unknown process pid 5325
,I/GAV4    ( 5248): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1531): onDestroy
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.465759 Y: -0.393814 Z: 9.768127 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465759 .y:-0.393814 .z:9.768127
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.457397 Y: -0.389572 Z: 9.759018 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457397 .y:-0.389572 .z:9.759018
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4252): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9121 usec
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  966): hal_acquire_resources
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.462158 Y: -0.403061 Z: 9.767990 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462158 .y:-0.403061 .z:9.767990
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.455917 Y: -0.417770 Z: 9.755005 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455917 .y:-0.417770 .z:9.755005
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  365): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.451401 Y: -0.426117 Z: 9.754318 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451401 .y:-0.426117 .z:9.754318
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.454727 Y: -0.407257 Z: 9.752914 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454727 .y:-0.407257 .z:9.752914
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.454163 Y: -0.389633 Z: 9.766388 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454163 .y:-0.389633 .z:9.766388
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.450119 Y: -0.419830 Z: 9.775284 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450119 .y:-0.419830 .z:9.775284
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@430bf0e0)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb76f5450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,I/WindowManager(  966): No lock screen! windowToken=null
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.439362 Y: -0.388382 Z: 9.783539 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.451584 Y: -0.406174 Z: 9.750198 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.439362 .y:-0.388382 .z:9.783539
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4252): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,D/wpa_supplicant( 4252): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131127
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=132097
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  966): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4252): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4252): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  966): handleMessage: X
,E/SlideAside( 3572): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,D/WeatherAncestor( 1873): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:40:37
,I/SlideAside( 3572): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
,V/SRS_Proc(  272): ParamSet string: screen_state=on
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{431a05b8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1873): 2 : This is isUpdating : false
,D/WeatherAncestor( 1873): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:40:37
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1873): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
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
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 399ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226437610, nextTick: 22421, mDrawingTime: 1
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226437649, nextTick: 22382, mDrawingTime: 1
D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/WeatherService( 1873): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:37
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1873): 2 : ACTION screen on
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1873): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:37
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,I/LGImmersionVibrator(  966): Vibrator off
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 true
,D/UsbSettings( 2586): [AUTORUN] onDestroy() : getDefaultFunction =boot
,D/WifiNative-wlan0(  966): doBoolean: DRIVER SETSUSPENDMODE 1
V/UsbSettings( 2586): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2586): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2586): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{43d30eb8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/wpa_supplicant( 4252): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4252): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  272): ParamSet string: screen_state=off
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1155): clear
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,D/wpa_supplicant( 4252): wpa_driver_nl80211_driver_cmd  len = 0, 0
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4316a268 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
D/WeatherService( 1873): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:37
D/WeatherService( 1873): 2 : ACTION screen off
D/WeatherService( 1873): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:37
V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_OFF
D/NfcService( 1473): NFC-C OFF
D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  365): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5208): [438] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5208): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226455733482329; DSPS: 5273252; Offset: 1450226294806602447
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226460050, nextTick: 59981, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226460052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226475735399509; DSPS: 5928674; Offset: 1450226294806627537
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226495737140595; DSPS: 6584092; Offset: 1450226294806598603
,I/rmt_storage(  411): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb7021178
I/rmt_storage(  411): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  411): wakelock acquired: 1, error no: 42
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1224601032)
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1224601032) wakelock released: 1, error no: 0
I/rmt_storage(  411): 
I/rmt_storage(  411): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb7021178
,E/Diag_Lib(  671): [IMS_FATAL]| 2912 | 675 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226515738730743; DSPS: 7239504; Offset: 1450226294806601837
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226520053, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226520056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226535740522560; DSPS: 7894922; Offset: 1450226294806623635
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226555742013853; DSPS: 8550331; Offset: 1450226294806619566
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226575743335721; DSPS: 9205735; Offset: 1450226294806598661
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226580065, nextTick: 59967, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226580066, nextTick: 59966, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226595744938005; DSPS: 9861147; Offset: 1450226294806614031
,D/wpa_supplicant( 4252): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Remove id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4252): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4252): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226615746426539; DSPS: 10516556; Offset: 1450226294806607204
,D/dalvikvm(  966): GC_EXPLICIT freed 1605K, 48% free 29685K/56808K, paused 3ms+7ms, total 104ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 2642): GC_CONCURRENT freed 7669K, 33% free 16870K/24832K, paused 3ms+3ms, total 62ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Killing 4809:com.lge.task/u0a43 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432603b8 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226635748021323; DSPS: 11171968; Offset: 1450226294806615073
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226640035, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226640057, nextTick: 59973, mDrawingTime: 1
,D/dalvikvm( 2642): GC_FOR_ALLOC freed 1630K, 32% free 17053K/24832K, paused 23ms, total 25ms
,D/dalvikvm( 2642): GC_CONCURRENT freed 1805K, 31% free 17271K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2642): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Mlt MonitorService( 2642): parseLastkmsg to dump
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226655749978503; DSPS: 11827392; Offset: 1450226294806619128
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226675751685579; DSPS: 12482808; Offset: 1450226294806617220
,I/jxcore-log( 4160): Connected to the server!
I/jxcore-log( 4160): 
,I/chromium( 4160): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226695753396404; DSPS: 13138224; Offset: 1450226294806619061
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226700027, nextTick: 59996, mDrawingTime: 7
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226700064, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226715755005250; DSPS: 13793637; Offset: 1450226294806610475
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4310b078: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1531): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1531): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1531): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1531): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1531): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1531): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5208): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5208): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5208): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5208): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5208): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5208): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5208): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5208): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5208): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5208): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226735756807325; DSPS: 14449056; Offset: 1450226294806612013
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226755758661225; DSPS: 15104477; Offset: 1450226294806604341
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226760043, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226760047, nextTick: 59981, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226775760729291; DSPS: 15759905; Offset: 1450226294806597211
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226795762327354; DSPS: 16415317; Offset: 1450226294806608360
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226815764325213; DSPS: 17070742; Offset: 1450226294806622577
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226820046, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226820054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226835765955412; DSPS: 17726156; Offset: 1450226294806604827
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226855767819207; DSPS: 18381577; Offset: 1450226294806607049
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226875769769719; DSPS: 19037001; Offset: 1450226294806604436
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226880043, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226880049, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226895771117995; DSPS: 19692405; Offset: 1450226294806609939
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226915772685331; DSPS: 20347816; Offset: 1450226294806620878
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226935774379281; DSPS: 21003232; Offset: 1450226294806605844
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226940041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450226940048, nextTick: 59981, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226955776269482; DSPS: 21658654; Offset: 1450226294806603955
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226975778069214; DSPS: 22314073; Offset: 1450226294806603150
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450226995780360872; DSPS: 22969508; Offset: 1450226294806605990
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227000046, nextTick: 59958, mDrawingTime: 11
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227000064, nextTick: 59967, mDrawingTime: 1
,D/dalvikvm( 1141): GC_CONCURRENT freed 6482K, 11% free 68529K/76640K, paused 20ms+9ms, total 91ms
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227015782247792; DSPS: 23624930; Offset: 1450226294806600820
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227035784023202; DSPS: 24280348; Offset: 1450226294806606210
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227055785903767; DSPS: 24935770; Offset: 1450226294806594685
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227060046, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227060054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227075787513654; DSPS: 25591182; Offset: 1450226294806617658
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227095789396304; DSPS: 26246604; Offset: 1450226294806608219
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227115791483118; DSPS: 26902032; Offset: 1450226294806619837
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227120042, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227120048, nextTick: 59981, mDrawingTime: 1
,D/dalvikvm( 2642): GC_CONCURRENT freed 2460K, 33% free 16733K/24832K, paused 30ms+2ms, total 62ms
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/QcConnectivityService(  966): Setting timer for 720seconds
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227135793395611; DSPS: 27557455; Offset: 1450226294806609723
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227155795265760; DSPS: 28212876; Offset: 1450226294806618300
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227175796693408; DSPS: 28868283; Offset: 1450226294806611621
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227180043, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227180049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227195798246162; DSPS: 29523694; Offset: 1450226294806607979
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227215799833238; DSPS: 30179106; Offset: 1450226294806608141
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227235801736457; DSPS: 30834528; Offset: 1450226294806619270
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227240073, nextTick: 59957, mDrawingTime: 2
D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227240075, nextTick: 59958, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227255803361191; DSPS: 31489942; Offset: 1450226294806596055
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227275807111860; DSPS: 32145424; Offset: 1450226294806623579
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227295808977061; DSPS: 32800846; Offset: 1450226294806596690
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227300051, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227300060, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227315810847939; DSPS: 33456267; Offset: 1450226294806605996
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227335811962045; DSPS: 34111663; Offset: 1450226294806621469
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227355813572141; DSPS: 34767076; Offset: 1450226294806614134
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227360074, nextTick: 59957, mDrawingTime: 2
D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227360075, nextTick: 59958, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227375815357810; DSPS: 35422495; Offset: 1450226294806599266
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227395816210876; DSPS: 36077883; Offset: 1450226294806597839
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227415820706702; DSPS: 36733390; Offset: 1450226294806607581
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227420036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227420061, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227435821871122; DSPS: 37388788; Offset: 1450226294806612333
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227455823347885; DSPS: 38044196; Offset: 1450226294806624253
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227475827926992; DSPS: 38699707; Offset: 1450226294806595205
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227480049, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227480056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227495829735474; DSPS: 39355126; Offset: 1450226294806603150
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227515830997810; DSPS: 40010527; Offset: 1450226294806614266
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227535832100094; DSPS: 40665923; Offset: 1450226294806617917
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227540052, nextTick: 59970, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227540059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227555834043525; DSPS: 41321347; Offset: 1450226294806608223
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227575835606433; DSPS: 41976758; Offset: 1450226294806614734
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227595836031790; DSPS: 42632132; Offset: 1450226294806612845
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227600040, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227600046, nextTick: 59958, mDrawingTime: 10
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227615836962042; DSPS: 43287523; Offset: 1450226294806597052
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227635838527034; DSPS: 43942934; Offset: 1450226294806605648
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227655840877236; DSPS: 44598371; Offset: 1450226294806605996
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227660046, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227660059, nextTick: 59967, mDrawingTime: 4
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227675845869779; DSPS: 45253894; Offset: 1450226294806624174
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227695847788469; DSPS: 45909317; Offset: 1450226294806620257
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227715850273411; DSPS: 46564759; Offset: 1450226294806602757
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227720050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227720053, nextTick: 59969, mDrawingTime: 5
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227735851099757; DSPS: 47220146; Offset: 1450226294806605129
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227755852588604; DSPS: 47875555; Offset: 1450226294806598614
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227775853726773; DSPS: 48530952; Offset: 1450226294806607633
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227780042, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227780048, nextTick: 59978, mDrawingTime: 3
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227795854585672; DSPS: 49186340; Offset: 1450226294806612040
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227815855770663; DSPS: 49841739; Offset: 1450226294806606845
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227835857380500; DSPS: 50497152; Offset: 1450226294806599250
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227840038, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227840048, nextTick: 59981, mDrawingTime: 2
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/GCM     ( 1531): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): Setting timer for 720seconds
,I/EventLogService( 1948): Aggregate from 1450226418530 (log), 1450225966406 (data)
,D/dalvikvm( 1948): GC_CONCURRENT freed 1822K, 22% free 19557K/24832K, paused 5ms+7ms, total 77ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227855859182940; DSPS: 51152571; Offset: 1450226294806601153
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227875861816994; DSPS: 51808017; Offset: 1450226294806610696
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227895863796572; DSPS: 52463442; Offset: 1450226294806606631
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227900032, nextTick: 59996, mDrawingTime: 3
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227900061, nextTick: 59968, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227915865346876; DSPS: 53118853; Offset: 1450226294806600539
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227935865876972; DSPS: 53774230; Offset: 1450226294806611836
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227955866902955; DSPS: 54429624; Offset: 1450226294806600221
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227960043, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450227960049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227975868654249; DSPS: 55085041; Offset: 1450226294806612013
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450227995870573044; DSPS: 55740464; Offset: 1450226294806608201
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228015871076421; DSPS: 56395840; Offset: 1450226294806623296
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228020052, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228020055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228035872997246; DSPS: 57051264; Offset: 1450226294806590996
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228055874820364; DSPS: 57706683; Offset: 1450226294806613577
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228075875904367; DSPS: 58362079; Offset: 1450226294806598948
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228080049, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228080055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228095881216286; DSPS: 59017613; Offset: 1450226294806600808
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228115883070446; DSPS: 59673034; Offset: 1450226294806593396
,I/ProcessStatsService(  966): Prepared write state in 25ms
,I/ProcessStatsService(  966): Prepared write state in 34ms
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-20-00.bin
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42baaa10 on behalf of 1948
,I/GLSUser ( 1531): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1531): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1531): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1531): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1531): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1531): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42bae7c8 on behalf of 1948
,V/DownloadManager( 4567): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 4567): created cursor android.database.sqlite.SQLiteCursor@42bb1e80 on behalf of 1948
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228135884566324; DSPS: 60328442; Offset: 1450226294806624430
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228140036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228140039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228155885715378; DSPS: 60983840; Offset: 1450226294806613816
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228175887340319; DSPS: 61639253; Offset: 1450226294806621325
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228195888872237; DSPS: 62294664; Offset: 1450226294806596847
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228200046, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450228200064, nextTick: 59966, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450228215890021397; DSPS: 62950061; Offset: 1450226294806616856
,TIME-OUT KILL (timeout was 1800000ms)
```
