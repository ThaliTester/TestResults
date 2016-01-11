#### Test 55613145dd493c6_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1943): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1943): launchTask
W/dalvikvm( 1943): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
W/GAV2    ( 3983): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 3321:com.google.android.music:main/u0a107 (adj 15): empty #17
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1943): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1943): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1943): No vision deps
F/ActivityManager(  960): Service ServiceRecord{43b46040 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43af08f0 3321:com.google.android.music:main/u0a107} not same as in map: null
V/ConfigFetchTask( 1943): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VqW9ejs01K80ot6uYJc3LDoBmd_EaC-CROSbUU3q5B7DckbEx4JqgDOOiPAZvLJVkBVWuI3JBY6nfTX0IgSYe0HR6Ugi9Anl80Ws3ynfJvdRBsJwCvjwXE7f4nDkp5I2ZPspSQ_Gd65gwLbotHAnHGW68-4h4O01RjJE-bgmoHvACCrfC2iJn0w2FKSFJvM-g1lciS
I/GoogleURLConnFactory( 1943): Using platform SSLCertificateSocketFactory
F/ActivityManager(  960): Service ServiceRecord{43abad10 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43af08f0 3321:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2}
I/PeopleContactsSync( 1943): CP2 sync disabled
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 1943): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1943): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1943): VFY: replacing opcode 0x6e at 0x000e
E/DataScheduler( 1943): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1943): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/dalvikvm(  960): Jit: resizing JitTable from 8192 to 16384
I/ConfigFetchService( 1943): fetch service done; releasing wakelock
I/ConfigFetchService( 1943): stopping self
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
D/AndroidRuntime( 4024): 
D/AndroidRuntime( 4024): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4024): CheckJNI is OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4024): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4024): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4024): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4024): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4024): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1943): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 4024): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/dalvikvm( 1943): GC_CONCURRENT freed 1613K, 26% free 18451K/24832K, paused 3ms+4ms, total 40ms
D/dalvikvm( 1943): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 1943): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1943): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1943): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1943): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4024): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4024): failed to load memtrack module: -2
D/AndroidRuntime( 4024): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4024
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (132 us)
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  960): GC_FOR_ALLOC freed 22511K, 51% free 28157K/57104K, paused 124ms, total 124ms
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/AndroidRuntime( 4024): Shutting down VM
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/dalvikvm( 4024): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/UsbSettingsControl( 2507): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2507): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/ActivityManager(  960): startService SlideAside
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3505): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4061 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3505): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3505): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4061): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4061): Binding Chromium to the background looper Looper (main, tid 1) {430f61f8}
I/chromium( 4061): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4061): Initializing chromium process, renderers=0
W/chromium( 4061): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4061): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4061): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4061): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4061): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4061): Remote Branch: 
I/Adreno-EGL( 4061): Local Patches: 
I/Adreno-EGL( 4061): Reconstruct Branch: 
I/dalvikvm( 4061): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4061): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4061): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4061): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4061): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4061): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4061): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4061): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4061): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4061): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4061): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4061): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4061): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4061): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4061): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4061): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4061): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4061): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4061): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4061): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4061): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4061): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4061): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4061): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4061): Enabling debug mode 0
,W/AwContents( 4061): nativeOnDraw failed; clearing to background color.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputMethodManagerService(  960): IME STATUS OFF
W/AwContents( 4061): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +342ms
,I/ActivityManager( 4061): Timeline: Activity_idle id: android.os.BinderProxy@430f78d8 time:107235
,D/JsMessageQueue( 4061): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4061): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x430fb9b8
,D/dalvikvm( 4061): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x430fb9b8
,D/jxcore_app_log( 4061): JniHelper::setJavaVM(0x420a4808), pthread_self() = 1632446896
,D/JX-Cordova( 4061): jxcore cordova android initializing
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3} time:107654
D/ActivityManager(  960): no-history finish of ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{43965118 ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,D/UsbSettings( 2507): [AUTORUN] onStop()
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4061): GC_CONCURRENT freed 2784K, 12% free 21868K/24832K, paused 2ms+1ms, total 46ms
,D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 133K, 12% free 21878K/24832K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 23.600MB for 64402-byte allocation
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 134K, 13% free 21891K/24896K, paused 22ms, total 22ms
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 181K, 12% free 21925K/24896K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 23.723MB for 144892-byte allocation
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 254K, 13% free 21973K/25040K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 23.838MB for 217334-byte allocation
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 371K, 13% free 22047K/25256K, paused 41ms, total 41ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 24.015MB for 325996-byte allocation
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 571K, 14% free 22169K/25576K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 24.290MB for 488990-byte allocation
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 869K, 15% free 22346K/26056K, paused 24ms, total 24ms
I/dalvikvm-heap( 4061): Grow heap (frag case) to 24.695MB for 733480-byte allocation
D/dalvikvm( 4061): GC_FOR_ALLOC freed 1288K, 16% free 22603K/26776K, paused 24ms, total 24ms
D/dalvikvm( 4061): GC_CONCURRENT freed 1675K, 15% free 22975K/26776K, paused 2ms+2ms, total 31ms
D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 4061): GC_FOR_ALLOC freed 379K, 15% free 22933K/26776K, paused 27ms, total 28ms
I/dalvikvm-heap( 4061): Grow heap (frag case) to 26.143MB for 1650320-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4061): GC_CONCURRENT freed 1763K, 18% free 23509K/28388K, paused 1ms+2ms, total 39ms
D/dalvikvm( 4061): GC_FOR_ALLOC freed 1276K, 17% free 23564K/28388K, paused 25ms, total 25ms
I/dalvikvm-heap( 4061): Grow heap (frag case) to 27.545MB for 2475476-byte allocation
D/dalvikvm( 4061): GC_CONCURRENT freed 1731K, 22% free 24304K/30808K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4061): GC_CONCURRENT freed 2398K, 21% free 24519K/30808K, paused 2ms+4ms, total 44ms
,D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 704K, 21% free 24385K/30808K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4061): Grow heap (frag case) to 29.528MB for 3713210-byte allocation
,D/dalvikvm( 4061): GC_CONCURRENT freed 371K, 19% free 27913K/34436K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 4061): GC_FOR_ALLOC freed 3036K, 26% free 25516K/34436K, paused 27ms, total 27ms
,W/jxcore-log( 4061): Initializing JXcore engine
,W/jxcore-log( 4061): JXcore engine is ready
,D/dalvikvm( 4061): GC_CONCURRENT freed 366K, 19% free 28146K/34436K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 4061): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4061): Starting JXcore engine
,W/jxcore-log( 4061): Platform android
W/jxcore-log( 4061): 
,W/jxcore-log( 4061): Process ARCH arm
W/jxcore-log( 4061): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4061): JXcore Cordova bridge is ready!
I/jxcore-log( 4061): 
,W/jxcore-log( 4061): JXcore engine is started
,I/chromium( 4061): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4061): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4061): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3983): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1546): onDestroy
,I/jxcore-log( 4061): Toggling radios to true
I/jxcore-log( 4061): 
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a14af8:true
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  960): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  960): Message: 1
,D/BluetoothManagerService(  960): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  960): New client listening to asynchronous messages
,D/WifiService(  960): setWifiEnabled: true pid=4061, uid=10304
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1229): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1125245760)( 1229): onCreate
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothAdapterState( 1229): make
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@439fac40:true
I/bluedroid( 1229): init ready=0
,D/bt-btif ( 1229): in initialized:0
D/bt-btif ( 1229): root, p->name:Bluedroid, child/value:0x606967c0, bytes:160
D/bt-btif ( 1229): p->used:0, type:0, p->flag:0
,I/BluetoothAdapterState( 1229): Entering OffState
,D/WifiStateMachine(  960): setting operational mode to 1
,I/jxcore-log( 4061): Radios toggled
I/jxcore-log( 4061): 
,I/bte_conf( 1229): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,D/btif_config_util( 1229): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/BT_PROF ( 1229): set profile trace flags 0x0
D/BTIF_CORE( 1229): [BTUI] lge_load_bluetooth_address
D/WifiStateMachine(  960): handleMessage: E msg.what=131145
D/WifiStateMachine(  960): processMsg: InitialState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131083
D/WifiStateMachine(  960): processMsg: InitialState
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/bt-btif ( 1229):  [BTUI] Load_abtddress
D/bt-btif ( 1229): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
,D/bt-btif ( 1229): Got prior random BDA 34:FC:EF:9D:93:0B
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/WifiHW  (  960): Wifi MAC Address = 34:fc:ef:de:0a:e2
,E/WifiHW  (  960): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  960): ": cur_etheraddr=34:fc:ef:de:0a:e2
D/lge_bdaddr_loader( 4117): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 4117): [BTUI] bluetooth_load_bdaddress
D/WifiService(  960): disconnect pid=4061, uid=10304
,D/WifiService(  960): reconnect pid=4061, uid=10304
D/lge_bdaddr_loader( 4117): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
D/SoftapController(  264): Softap fwReload - Ok
I/jxcore-log( 4061): Received device characteristics:
I/jxcore-log( 4061): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4061): Bluetooth name: Thali Test's G2
I/jxcore-log( 4061): Device name: LGE-LG-D802
I/jxcore-log( 4061): 
I/jxcore-log( 4061): Perf Test app loaded loaded
I/jxcore-log( 4061): 
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring down wlan0
I/Choreographer( 4061): Skipped 81 frames!  The application may be doing too much work on its main thread.
D/WifiMonitor(  960): WifiMonitorSingleton gotten
,I/chromium( 4061): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4061): check test folder
I/jxcore-log( 4061): 
,I/jxcore-log( 4061): found test : ./testFindPeers.js
I/jxcore-log( 4061): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/lge_bdaddr_loader( 4117): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
D/lge_bdaddr_loader( 4117): [BTUI] bdaddr_loader ::: END
I/jxcore-log( 4061): found test : ./testSendData.js
I/jxcore-log( 4061): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/WifiStateMachine(  960): setWifiState: enabling
E/WifiStateMachine(  960): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  960): useWiFiOffloading() : false
E/WifiStateMachine(  960): CONFIG_LGE_WLAN_PATH : true
D/WifiStateMachine(  960): Supplicant start successful
D/WifiMonitor(  960): WifiMonitorSingleton gotten
D/WifiMonitor(  960): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  960): connecting to supplicant
V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  960): WIFI_STATE_CHANGED_ACTION [2]
,I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4134 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/wpa_supplicant( 4131): wpa_supplicant v2.1-devel-4.4.2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
D/wpa_supplicant( 4131): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4131): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4131): Get randomness: len=20 entropy=1
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,D/wpa_supplicant( 4131): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4131): Global control interface '@android:wpa_wlan0'
,D/wpa_supplicant( 4131): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4131): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4131): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4131): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4131): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4131): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4131): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4131): disable_scan_offload=1
D/wpa_supplicant( 4131): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4131): update_config=1
D/wpa_supplicant( 4131): device_name='g2_open_com'
D/wpa_supplicant( 4131): manufacturer='LGE'
D/wpa_supplicant( 4131): model_name='LG-D802'
D/wpa_supplicant( 4131): model_number='LG-D802'
D/wpa_supplicant( 4131): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4131): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4131): p2p_disabled=1
D/wpa_supplicant( 4131): p2p_no_group_iface=1
D/wpa_supplicant( 4131): Line: 15 - start of a new network block
D/wpa_supplicant( 4131): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4131): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4131): key_mgmt: 0x2
,D/wpa_supplicant( 4131): priority=1 (0x1)
,D/HyLog   ( 4134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4134): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4134): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/PCSuite ( 4134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  960): Killing 2121:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
,I/bluedroid( 1229): get_profile_interface socket
I/GKI_LINUX( 1229): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1229): btif task starting
D/bt-btif ( 1229): btif_associate_evt: notify ASSOCIATE_JVM
,I/bt-btif ( 1229): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1229): btif_get_adapter_property 2
I/bt-btif ( 1229): btif_get_adapter_property 1
I/bt-btif ( 1229): execute storage request event : 3
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:2 
,I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService(1125245760)( 1229): onBind
I/bt-btif ( 1229): execute storage request event : 3
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1229): in, bd addr:, prop type:1, len:512
,I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  960): Bluetooth Adapter name changed to Thali Test's G2
D/wpa_supplicant( 4131): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4131): Priority group 1
D/wpa_supplicant( 4131):    id=0 ssid='NG700'
,D/wpa_supplicant( 4131): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/wpa_supplicant( 4131): disable_scan_offload=1
D/wpa_supplicant( 4131): Priority group 1
D/wpa_supplicant( 4131):    id=0 ssid='NG700'
D/BluetoothManagerService(  960): Stored Bluetooth name: Thali Test's G2
I/wpa_supplicant( 4131): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4131): nl80211: RFKILL status not available
,D/wpa_supplicant( 4131): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4131): nl80211: TDLS supported
D/wpa_supplicant( 4131): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4131): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4131): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4131): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4131): nl80211: interface wlan0 in phy phy0
D/BluetoothManagerService(  960): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/wpa_supplicant( 4131): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/BluetoothManagerService(  960): Message: 40
,D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/wpa_supplicant( 4131): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0d
,D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
I/bluedroid( 1229): config_hci_snoop_log
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=1): 06
D/BluetoothManagerService(  960): Calling onBluetoothServiceUp callbacks
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
,D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/BluetoothManagerService(  960): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/dalvikvm( 1229): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothAdapterService(1125245760)( 1229): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1229): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1229): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1229): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  960): Message: 60
,D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothAdapterService(1125245760)( 1229): processStart()
,D/BluetoothManagerService(  960): Bluetooth State Change Intent: 10 -> 11
,D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1125245760)( 1229): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1229): make
,D/BluetoothAdapterService( 1229): setAdapterService(): set to: null
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
D/LGBluetoothServiceAdapter( 1229): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
D/LGBluetoothServiceAdapter( 1229): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1229): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1229): StableState(): Entering Off State
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,W/BluetoothAdapterService( 1229): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.a2dp.A2dpService
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,D/BluetoothHeadset(  960): Proxy object connected
D/BluetoothHeadset( 1447): Proxy object connected
,D/BluetoothHeadset( 1447): Proxy object connected
D/BluetoothHeadset( 1447): Proxy object connected
,D/BrcmHeadsetService( 1229): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1229): classInitNative: succeeds
,D/HeadsetStateMachine( 1229): make
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.hid.HidService
D/LGBluetoothXmlHandler( 2507): dvice configuraion start
,D/LGBluetoothXmlHandler( 2507): startDocument!
D/LGBluetoothXmlHandler( 2507): startElement - elet = Device
D/LGBluetoothXmlHandler( 2507): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2507): startElement - elet = OLDHELP
,D/LGBluetoothXmlHandler( 2507): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2507): startElement - elet = OPP_DIRECTORY_BLUETOOTH
,D/LGBluetoothXmlHandler( 2507): endDocument!
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
I/LGBluetoothHeadsetServiceJni( 1229): classInitNative: succeeds
,D/LGBluetoothHfpAdapter( 1229): Version 1.5
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.hdp.HealthService
I/bluedroid( 1229): get_profile_interface handsfree
,I/bt-btif ( 1229): btif_hf_get_interface
I/bt-btif ( 1229): init
D/bt-btif ( 1229): btif_enable_service: current services:0x40
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.pan.PanService
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.map.BluetoothMapService
V/AudioPolicyService(  271): getOutput()
V/AudioPolicyManagerBase(  271): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  271): getOutput() returns output 2
V/AudioSystem( 1229): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  271): registerClient() client 0xb7292840, pid 1229
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
,V/AudioFlinger(  271): thread 0xb2723008 type 0 TID 929 waking up
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
,V/AudioFlinger(  271): thread 0xb25b8008 type 0 TID 1001 waking up
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb2723008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem(  960): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb25b8008, event 0, param 0
V/AudioSystem(  960): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 3
,V/AudioSystem(  271): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1229): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1599): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1229): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1599): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1599): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1229): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1229): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem(  960): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  960): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1599): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1229): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1229): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1229): streamType 8
V/AudioTrack( 1229): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyService(  271): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  271): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1229): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
E/BluetoothAdapterService( 1229): File transfer profiels supported!!
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
D/HeadsetStateMachine( 1229): Enter Disconnected: -2
D/HeadsetPhoneState( 1229): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1229): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1229): [BTUI] change sampling rate to 8000 when device is disconnected
,E/AudioSystem( 1229): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  271): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1229
V/SRS_Proc(  271): ParamSet string: bt_samplerate=8000
,W/BluetoothAdapterService( 1229): Starting service com.android.bluetooth.gatt.GattService
D/audio_hw_primary(  271): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: bt_samplerate=8000
,V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,D/BluetoothA2dp(  960): Proxy object connected
,D/A2dpService( 1229): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1229): classInitNative: succeeds
D/A2dpStateMachine( 1229): make
E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,I/bluedroid( 1229): get_profile_interface a2dp
I/bt-btif ( 1229): btif_av_get_interface
I/bt-btif ( 1229): init
I/bt-btif ( 1229): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1229): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1229): UIPC_Init
I/bt-btif ( 1229): ### uipc_main_init ###
D/bt-btif ( 1229): UIPC_Open : ch_id 0, p_cback 60b29b25
I/bt-btif ( 1229): SETUP CHANNEL SERVER 0
I/bt-btif ( 1229): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1229): created socket fd 69
I/bt-btif ( 1229): ADD SERVER FD TO ACTIVE SET 69
,I/bt-btif ( 1229): UIPC SEND WAKE UP
I/bt-btif ( 1229): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1229): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1229): btif_enable_service: current services:0x48
D/bt-btif ( 1229): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1229): ## ON A2DP IDLE ##
W/BluetoothAdapterService( 1229): Starting service com.broadcom.bt.service.sap.SapService
D/bt-btif ( 1229): UIPC_Close : ch_id 1
,I/bt-btif ( 1229): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1229): classInitNative: succeeds
,I/LGBluetoothA2dpAdapter( 1229): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,D/A2dpStateMachine( 1229): Enter Disconnected: -2
I/BluetoothAVRCP1.3ServiceJni( 1229): classInitNativeAVRCP
,V/Avrcp   ( 1229): make
,D/LGBluetoothAvrcpManager( 1229): [BTUI] initAvcrpManager
,E/BluetoothAdapterService( 1229): File transfer profiels supported!!
,D/LGBluetoothAvrcpManager( 1229): [BTUI] initPlayStatus() : isMusicActive = false
,W/BluetoothAdapterService( 1229): Starting service com.broadcom.bt.service.ftp.FTPService
D/LGBluetoothAvrcpAdapter( 1229): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1229): initNativeAVRCP
,I/bluedroid( 1229): get_profile_interface avrcp
I/bt-btif ( 1229): btif_rc_get_interface
I/bt-btif ( 1229): ## init ##
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,V/BluetoothPbapReceiver( 1229): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1229): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1229): ***********state = 11
,I/BluetoothHidServiceJni( 1229): classInitNative: succeeds
,D/HidService( 1229): Received start request. Starting profile...
D/dalvikvm( 1229): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/bluedroid( 1229): get_profile_interface hidhost
I/bt-btif ( 1229): btif_hh_get_interface
I/bt-btif ( 1229): init
D/bt-btif ( 1229): btif_enable_service: current services:0x100048
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,I/BluetoothHealthServiceJni( 1229): classInitNative: succeeds
D/HealthService( 1229): Received start request. Starting profile...
D/BluetoothPermissionRequest( 2507): onReceive
,I/bluedroid( 1229): get_profile_interface health
I/bt-btif ( 1229): btif_hl_get_interface
I/bt-btif ( 1229): init
D/bt-btif ( 1229): Process name (droid.bluetooth)
D/bt-btif ( 1229): btif_hl_soc_thread_init
D/bt-btif ( 1229): create_thread: entered
D/bt-btif ( 1229): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1229): classInitNative: succeeds
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
D/HeadsetStateMachine( 1229): Proxy object connected
D/bt-btif ( 1229): entered btif_hl_select_thread
D/bt-btif ( 1229): btif_hl_select_wakeup_init
D/bt-btif ( 1229): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1229): max_s=79 
D/bt-btif ( 1229): set curr_set = org_set 
,I/BluetoothPanServiceJni( 1229): classInitNative(L105): succeeds
,D/BluetoothPan(  960): BluetoothPAN Proxy object connected
D/PanService( 1229): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1229): initializeNative(L110): pan
I/bluedroid( 1229): get_profile_interface pan
D/bt-btif ( 1229): stack_initialized = 0, btpan_cb.enabled:0
,I/BluetoothAdapterState( 1229): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4364b5d0:true
D/BluetoothTethering(  960): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
I/LGBluetoothMapAdapter( 1229): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1229): BluetoothMapBinder()
D/LGBluetoothResetSettingReceiver( 2507): [BTUI] Loading JNI Library
,D/BluetoothMapService( 1229): Received start request. Starting profile...
D/BluetoothMapService( 1229): start()
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
I/BtGatt.JNI( 1229): classInitNative(L685): classInitNative: Success!
,E/BluetoothSettings_JNI( 2507): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/LGBluetoothResetSettingReceiver( 2507): return without doing reset settings.
D/HeadsetPhoneState( 1229): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 1229): Disconnected process message: 11
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BtGatt.DebugUtils( 1229): handleDebugAction() action=null
D/BtGatt.GattService( 1229): Received start request. Starting profile...
D/BtGatt.GattService( 1229): start()
,I/bluedroid( 1229): get_profile_interface gatt
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,I/BluetoothSAPServiceJni( 1229): classInitNative(L170): succeeds
D/SapService( 1229): Received start request. Starting profile...
,D/BluetoothSAPServiceJni( 1229): initializeNative(L175): sap
I/bluedroid( 1229): get_profile_interface sap
I/bt-btif ( 1229): btif_sc_get_interface
I/bt-btif ( 1229): init
D/bt-btif ( 1229): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1229): [BTUI] getInstance : create [LGBluetoothSapAdapter]
,I/LGBluetoothSapAdapter( 1229): [BTUI] Create LGBluetoothSapManager Instance
,D/LGBluetoothSapManager( 1229): [BTUI] initSapManager
,D/LgeBluetoothSimManager( 1447): [BTUI] SAP_ENABLE_EVT
,D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,V/BluetoothFTPServiceJni( 1229): classInitNative
I/BluetoothFTPServiceJni( 1229): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,D/BluetoothFTPService( 1229): BluetoothFtpBinder()
D/**BluetoothFTPService( 1229): Received start request. Starting profile...
,V/BluetoothFTPService( 1229): FTP-Server Service start
D/BluetoothFTPServiceJni( 1229): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1229): get_profile_interface ftp
,I/bt-btif ( 1229): btif_fts_get_interface
I/bt-btif ( 1229): init
D/bt-btif ( 1229): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1229): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
,D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1229): Handler(): got msg=1
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
,D/BluetoothAdapterService( 1229): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1125245760)( 1229): Message: 1
D/BluetoothAdapterService(1125245760)( 1229): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1229): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1229): All profile services started.
D/BluetoothAdapterState( 1229): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1229): enable 1
I/bt-btif ( 1229): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1229): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/bt_hci_bdroid( 1229): init
I/bt_vendor( 1229): init
I/bt_vnd_conf( 1229): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 1229): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1229): libbt-hci init returns 0
I/GKI_LINUX( 1229): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 1229): bt_hc_worker_thread started
,I/ActivityManager(  960): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4165 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 2ms+2ms, total 18ms
,D/AuthorizationBluetoothService( 1546): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  960): Killing 3198:com.android.mms/u0a35 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
,I/LocationManagerService(  960): remove 434b7980
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  960): No listener is left
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/bt_userial_vendor( 1229): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1229): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1229): device fd = 84 open
,D/bt_hwcfg( 1229): Chipset BCM4335A0
,D/bt_hwcfg( 1229): Target name = [BCM4335A0]
D/bt_hwcfg( 1229): Target name = [BCM4335]
I/bt_hwcfg( 1229): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1229): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1229): bt vendor lib: set UART baud 4000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt_hwcfg( 1229): Releasing 4335 AXI BRIDGE lock
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4131): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4131): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4131): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4131): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4131): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4131): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4131): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4131): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4131): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  960): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  960): sendTetherStateChangedBroadcast 1, 0, 0
D/wpa_supplicant( 4131): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4131): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4131): wlan0: Setting scan request: 0 sec 100000 usec
,D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2507): [AUTORUN] sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2507): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2507): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2507): getOperator() : OPEN
,D/UsbSettingsControl( 2507): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 2507): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsReceiver( 2507): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2507): [AUTORUN] setTetherStatus() : status=false
,D/wpa_supplicant( 4131): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4131): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4131): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4131): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
,D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 4131): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): Using existing control interface directory.
I/wpa_supplicant( 4131): 0xb7183cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4131): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4131): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4131): lge_eap_carrier_var_init
D/wpa_supplicant( 4131): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4131): wlan0: Added interface wlan0
D/wpa_supplicant( 4131): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4131): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4131): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4131): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 4131): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4131): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4131): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4131): update_config=1
D/wpa_supplicant( 4131): device_name='Thali Test's G2'
D/wpa_supplicant( 4131): config_methods='virtual_push_button physical_display keypad'
,D/wpa_supplicant( 4131): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4131): persistent_reconnect=1
,D/wpa_supplicant( 4131): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4131): update_config=1
D/wpa_supplicant( 4131): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4131): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4131): eapol_version=1
D/wpa_supplicant( 4131): ap_scan=1
,D/wpa_supplicant( 4131): fast_reauth=1
D/wpa_supplicant( 4131): p2p_disabled=0
D/wpa_supplicant( 4131): p2p_no_group_iface=0
I/wpa_supplicant( 4131): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4131): nl80211: RFKILL status not available
D/wpa_supplicant( 4131): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4131): nl80211: TDLS supported
D/wpa_supplicant( 4131): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4131): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4131): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4131): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4131): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4131): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
,D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7193c28
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4131): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4131): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4131): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4131): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4131): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4131): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4131): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4131): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4131): nl80211: 5735-5835 @ 40 MHz
D/wpa_supplicant( 4131): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4131): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4131): nl80211: Flush PMKIDs
D/wpa_supplicant( 4131): p2p0: State: DISCONNECTED -> INACTIVE
D/wpa_supplicant( 4131): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4131): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4131): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4131): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4131): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): Using existing control interface directory.
I/wpa_supplicant( 4131): 0xb7193098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4131): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4131): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4131): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4131): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4131): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4131): [ITEC] USE NON-INET
I/wpa_supplicant( 4131): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4131): HY wiflus comm channel initialized
D/wpa_supplicant( 4131): P2P: Own listen channel: 6
I/wpa_supplicant( 4131): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4131): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4131): P2P: Add operating class 81
D/wpa_supplicant( 4131): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4131): P2P: Add operating class 115
D/wpa_supplicant( 4131): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4131): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4131): p2p0: Added interface p2p0
D/wpa_supplicant( 4131): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4131): random: Got 16/20 bytes from /dev/random
D/wpa_supplicant( 4131): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): random: Got 4/4 bytes from /dev/random
D/wpa_supplicant( 4131): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4131): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/WifiStateMachine(  960): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  960): invokeExitMethods: InitialState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  960): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131144
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): deferMessage: msg=131144
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131085
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): deferMessage: msg=131085
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131149
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): setSuspendOptimizations: 2 true
D/WifiStateMachine(  960): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131146
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131101
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): processMsg: DefaultState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147457
D/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/WifiStateMachine(  960): Supplicant connection established
D/WifiNative-wlan0(  960): doString: DRIVER MACADDR
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER MACADDR'
D/WifiNative-wlan0(  960):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  960): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  960): setWifiState: enabled
D/WifiOffDelayIfNotUsed(  960): setPowerSaveActivated(false)
D/WifiActivationWhileCharging(  960): unregister : we don't need to unregister
E/WifiStateMachine(  960): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  960): useWiFiOffloading() : false
E/WifiStateMachine(  960): CONFIG_LGE_WLAN_PATH : true
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiConfigStore(  960): Loading config and enabling all networks
D/WifiNative-wlan0(  960): doString: LIST_NETWORKS
I/WifiServiceExtension(  960): WIFI_STATE_CHANGED_ACTION [3]
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/PCSuite ( 4134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WfdService( 1157): Waiting for WifiP2p enabling
I/WifiServiceExtension(  960): batteryPsActivateMsgHandler : state:0 event:3
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
I/bt_hwcfg( 1229): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1229): Settlement delay -- 100 ms
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4131): wlan0: Control interface command 'LIST_NETWORKS'
D/WifiNative-wlan0(  960):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  960): 0	NG700	any	
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'bssid'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4131): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'phase1'
D/wpa_supplicant( 4131): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4131): wlan0: nl80211: scan request
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 4131): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiConfigStore(  960): ***WAPI : not WAPI
D/WifiNative-wlan0(  960): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4131): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4131): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4131): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4131): CTRL_IFACE: Failed to get network variable 'private_key'
D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4131): wlan0: nl80211: Scan trigger
E/WifiConfigStore(  960): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  960): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4131): device_name='g2_open_com'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4131): manufacturer='LGE'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4131): model_name='LG-D802'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4131): model_number='LG-D802'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
D/wpa_supplicant( 4131): serial_number='022678fb504e29b0'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4131): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  960):    returned true
W/Settings( 3443): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  960): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  960): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  960): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  960): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4131): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4131): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  960): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setDetailed state, old =IDLE and new state=DISCONNECTED
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-REMOVE 3
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  960): doBoolean: RECONNECT
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4131): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doString: STATUS
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4131): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  960):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleScreenStateChanged: true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiP2pService(  960): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  960): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131144
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131085
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132106
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  960): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4131): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132096
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  960): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4131): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4131): disconnect_rssi_lvl: -100
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131127
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  960): handleMessage: X
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up p2p0
D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/WifiMonitor(  960): WifiMonitorSingleton gotten
D/WifiMonitor(  960): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  960): P2pEnablingState
D/WifiP2pService(  960): P2pEnablingState{ when=-2ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2p socket connection successful
D/WifiP2pService(  960): P2pEnabledState
V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiNative-p2p0(  960): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  960): handleMessage: E msg.what=143371
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4131): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4131): persistent_reconnect=1
D/wpa_supplicant( 4131): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  960):    returned true
I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4195 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  960): sending p2p connection changed broadcast
D/WifiNative-p2p0(  960): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4131): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4131): device_name='Thali Test's G2'
D/WifiNative-p2p0(  960):    returned true
D/WifiServiceExtension(  960): postfix byte check : 15
D/WifiNative-p2p0(  960): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4131): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4131): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4131): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4131): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4131): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4131): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4131): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4131): Single channel concurrency preference: sta
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doString: STATUS
D/wpa_supplicant( 4131): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  960):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  960): p2p_state=IDLE
D/WifiNative-p2p0(  960): wifi_display=1
D/WifiNative-p2p0(  960): ifname=p2p0
D/WifiNative-p2p0(  960): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  960): ifname=wlan0
D/WifiNative-p2p0(  960): address=34:fc:ef:de:0a:e2
D/WifiNative-p2p0(  960): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4131): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4131): P2P: Stopping find
D/wpa_supplicant( 4131): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4131): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4131): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doBoolean: P2P_SERVICE_FLUSH
I/WfdStateTracker( 1157): handleP2pThisDeviceChanged
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4131): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  960):    returned true
D/WifiNative-p2p0(  960): doString: LIST_NETWORKS
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4131): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  960):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  960): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4131): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4131): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  960): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  960): before postfix = Thali Test's G2
D/WifiP2pService(  960): after postfix = Thali Test's G2
,D/WifiP2pService(  960): DeviceAddress: 36:fc:ef:de:0a:e2
D/HyLog   ( 4195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4195): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4195): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 4131): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4131): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/LGDMSGCM( 4195): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-p2p0(  960):    returned true
E/WifiServiceExtension(  960): No p2p device connected
D/WifiP2pService(  960): sending p2p persistent groups changed broadcast
D/WifiP2pService(  960): InactiveState
D/WifiP2pService(  960): InactiveState{ when=-36ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=-36ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): DefaultState{ when=-36ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): InactiveState{ when=-36ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=-36ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): DefaultState{ when=-36ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4195): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/bt_hwcfg( 1229): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1229): Setting local bd addr to 34:FC:EF:9D:93:0B
I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4209 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  960): Killing 3748:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443146 Y: -0.408707 Z: 9.811295 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443146 .y:-0.408707 .z:9.811295
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/HyLog   ( 4209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4209): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
I/bt_hwcfg( 1229): vendor lib fwcfg completed
I/bt-btif ( 1229): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1229): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1229): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1229): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1229): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1229): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1229): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1229): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1229): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1229): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1229): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1229): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1229): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1229): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1229): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1229): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1229): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1229): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1229): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1229): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1229): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1229): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1229): bta_dm_sm_execute event:0x0
I/bt-btif ( 1229): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1229): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1229): bta_sys_sm_execute state:1, event:0x1
I/bt-btif ( 1229): bta_sys_hw_evt_enabled for 0
,I/Wireless_Storage( 4209): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 3952): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 3952): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/bt-btif ( 1229):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1229): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1229):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1229):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1229): ##################################
D/bt-btif ( 1229): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1229): ##################################
D/bt-btif ( 1229): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1229): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b7e4c5 
I/bt-smp  ( 1229): SMP_Register state=0
E/bt-btm  ( 1229): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b7e4c5 
D/bt-btif ( 1229): bta_gattc_register state 0
D/bt-btif ( 1229): bta_gattc_enable
I/bt-att  ( 1229): GATT_Register
D/bt-att  ( 1229): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1229): allocated gatt_if=3
D/bt-btif ( 1229): bta_dm_gattc_callback event = 0
D/bt-btif ( 1229): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1229): GATT_StartIf gatt_if=3
D/bt-att  ( 1229): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1229): gatt_find_the_connected_bda found=0 found_idx=7
I/ActivityManager(  960): Killing 3443:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.442154 Y: -0.403015 Z: 9.810257 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442154 .y:-0.403015 .z:9.810257
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  960): battery changed pluggedType: 2
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1229): Disconnected process message: 10
I/bt-btif ( 1229): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1229): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1229): bta_dm_sm_execute event:0x2
D/bt-btif ( 1229): BTA is generating EIR
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1229): Adding UUID=0x110C into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1229): nsc_mask: 0x6
D/bt-btif ( 1229): bta_av_co_audio_init
D/bt-btif ( 1229): bta_av_co_audio_init: 0
D/bt-btif ( 1229): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1229): bta_av_co_audio_init
D/bt-btif ( 1229): bta_av_co_audio_init: 1
D/bt-btif ( 1229): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1229): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1229): A2D_AddRecord uuid: 110a
I/bt-btif ( 1229): Adding UUID=0x110A into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1229): rc_acp_handle:0 idx:1
D/bt-btif ( 1229): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1229): reg_audio: 0x1
D/bt-btif ( 1229): bta_ag_scb_alloc 1
I/bt-btif ( 1229): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1229): bta_ag_add_record uuid: 1112
I/bt-btif ( 1229): Adding UUID=0x1112 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1229): bta_ag_add_record uuid: 111f
I/bt-btif ( 1229): Adding UUID=0x111F into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1229): getAccess buffer->st_uid:1000 buffer->st_gid:1028
D/bt-btif ( 1229): bta_fts_api_enable srm:1
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1229): Adding UUID=0x1106 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1229): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1229): bta_fts_ci_resume status:1
I/bt-btif ( 1229): FTP SERVER enabled with Root Path [/storage]
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1229): Adding UUID=0x112D into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1229): bte_sap_evt: event=0
E/bt-btif ( 1229): Calling BTA_HhEnable
D/bt-btif ( 1229): bta_gattc_register state 2
I/bt-att  ( 1229): GATT_Register
D/bt-att  ( 1229): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1229): allocated gatt_if=4
D/bt-btif ( 1229): bta_hh_gattc_callback event = 0
I/bt-att  ( 1229): GATT_StartIf gatt_if=4
D/bt-att  ( 1229): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1229): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1229): in add:1
D/bt-btif ( 1229): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1229): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1229): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1229): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1229): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1229): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1229): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1229): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1229): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1229): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1229): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1229): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1229): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1229): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1229): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1229): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1229): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1229): Remote device:e0:db:10:14:e2:c0, size:18
I/bt-btif ( 1229): bta_dm_sm_execute event:0x9
D/bt-btif ( 1229): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1229): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1229): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1229): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1229): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1229): bta_dm_sm_execute event:0x9
D/bt-btif ( 1229): Remote device:, size:128
E/bt-btif ( 1229): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1229): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1229): out
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1229): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1229): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1229): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1229): Unknow prop type:16
I/bt-btif ( 1229): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1229): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1229): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1229): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1229): btif_storage_get_adapter_property property->type:3 devicemode 0
I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  960): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  960): Stored Bluetooth name: Thali Test's G2
E/BluetoothAdapterProperties( 1229): Property change not handled in Java land:16
I/bt-btif ( 1229): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1229): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1229): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1229): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1229): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
D/bt-btif ( 1229): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
I/bt-btif ( 1229): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 1229): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1229): [BTUI] remoteDeviceSetProperties
I/LGRemoteDevicePropertySetting( 1229): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1229): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1229): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1229): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1229): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1229): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
I/bt-btif ( 1229): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 1229): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1229): [BTUI] remoteDeviceSetProperties
I/LGRemoteDevicePropertySetting( 1229): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1229): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1229): hw_sco_config...
E/bt_hwcfg( 1229): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1229): HC lpm_result_cb 1
I/bt-btif ( 1229): HC lib lpm enable=1 return 0
I/bt-btif ( 1229): BTA_BrcmInit
E/bt-gki  ( 1229): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
D/IOP_DB_BT( 1229): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1229): db_open: db_open : handle 1623636524l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1229): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1229): db_query: result 1
I/        ( 1229): iop_db_open: iop_db_open status 0
D/bt-btif ( 1229): btsock initializing...
D/bt-btif ( 1229): in initialized:1
D/bt-btif ( 1229): ts[7].used:1
D/bt-btif ( 1229): ts[6].used:0
D/bt-btif ( 1229): alloc_thread_slot ret:6
D/bt-btif ( 1229): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1229): h:6, thread id:1626797448
I/bt-btif ( 1229): BTA_JvEnable
D/bt-btif ( 1229): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1229): unhandled event:0, slot id:0
D/bt-btif ( 1229): btsock successfully initialized
D/bt-btif ( 1229): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1229): Enabling PAN....
I/bt-btif ( 1229): bta_pan_co_init
D/bt-btif ( 1229): local_role:3
D/bt-btif ( 1229): btpan_role:0x3
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1229): Adding UUID=0x1116 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1229): Adding UUID=0x1115 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1229): Adding UUID=0x1116 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1229): Removing UUID=0x1117 from EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1229): Adding UUID=0x1115 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1229): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bt-btif ( 1229): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1229): Adding UUID=0x1200 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1229): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1229): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1229): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1229): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1229): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1229): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1229): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1229): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1229): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
D/BluetoothAdapterState( 1229): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1229): ScanMode =  20
D/BluetoothAdapterProperties( 1229): State =  11
D/BluetoothAdapterProperties( 1229): mDiscoverableTimeout =  120
I/bt-btif ( 1229): btif_set_adapter_property type: 7, len 4, 0x43187340
I/bt-btif ( 1229): set property scan mode : 1
I/bt-btif ( 1229): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1229): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1229): onFtpServerEnabled: /storage
D/bt-btif ( 1229): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1229): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1229): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1229): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1229): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1229): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1229): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1229): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1229): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1229): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1229): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1229): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1229): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1229): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1229): Remote device:f8:cf:c5:d9:e5:61, size:18
I/bt-btif ( 1229): Remote device:f8:cf:c5:d9:
I/bt-btif ( 1229): bta_dm_sm_execute event:0x3
I/bt-btif ( 1229): btif_in_storage_request_copy_cb
I/bt-btif ( 1229): btif_set_adapter_property type: 9, len 4, 0x43187560
I/bt-btif ( 1229): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1229): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1229): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  960): Message: 60
D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  960): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  960): onBluetoothStateChange(on) call bindService
V/BluetoothAdapterService( 1229): startPbapService
D/bt-btif ( 1229): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1229): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1229): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1229): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1229): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1229): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1229): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1229): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1229): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1229): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1229): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1229): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1229): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1229): Remote device:, size:18
E/bt-btif ( 1229): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1229): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1229): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1229): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1229): execute storage request event : 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/bt-btif ( 1229): type: 7, len 4, 0x60ad403a
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
D/bt-btif ( 1229): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1229): Entering On State
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
D/BluetoothHeadset(  960): onBluetoothStateChange: up=true
D/BluetoothA2dp(  960): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1229): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1229): [BTUI]         global_name: Thali Test's G2
I/bt-btif ( 1229): execute storage request event : 2
D/BluetoothManagerService(  960): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 1229): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4311e340
V/BluetoothPbapService( 1229): Pbap Service onCreate
V/BluetoothPbapService( 1229): Starting PBAP service
D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1157): Message: 1
I/bt-btif ( 1229): type: 9, len 4, 0x60ad4086
D/bt-btif ( 1229): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1229): HAL bt_hal_cbacks->adapter_properties_cb
D/LGBluetoothAPIService( 1157): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(1125245760)( 1229): Get Bonded Devices being called
I/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothServiceAdapter( 1229): [BTUI]         local_name: Thali Test's G2
D/BluetoothAdapterService(1125245760)( 1229): Quiet mode Enabled = false
D/BluetoothAdapterService(1125245760)( 1229): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1229): [BTUI] autoConnect() : not allowed
D/LGBluetoothPbapAdapter( 1229): [BTUI] getInstance : create
V/BluetoothPbapService( 1229): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1229): state: 12
D/BluetoothManagerService(  960): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  960): Message: 40
D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1229): onReceive
D/BluetoothMapService( 1229): STATE_ON
V/BluetoothPbapService( 1229): Handler(): got msg=1
V/BluetoothPbapService( 1229): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIServer( 1229): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1229): [BTUI] onBind()
V/BluetoothPbapService( 1229): Pbap Service initSocket
D/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothMapService( 1229): Handler(): got msg=1
D/LGBluetoothAPIService( 1157): Message: 100
D/BluetoothMapService( 1229): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1157): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/bt_h4   ( 1229): vendor lib postload completed
I/bt-btif ( 1229): HC postload_cb 0
D/BluetoothMapService( 1229): Map Service initSocket
V/BluetoothPbapReceiver( 1229): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1229): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1229): ***********state = 12
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1229): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1229): SOCK FLAG = 1 ***********************
D/bt-btif ( 1229): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1229): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1229): BTA_JvCreateRecordByUser
D/bt-btif ( 1229): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1229): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1229): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1229): Adding UUID=0x112F into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1229): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1229): BTA_JvRfcommStartServer
D/bt-btif ( 1229): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1229): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1229): [BTUI] createSocketChannel FD=90 mFd=0
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 1229): Succeed to create listening socket 
V/BluetoothPbapService( 1229): Accepting socket connection...
D/LocalBluetoothProfileManager( 2507): Adding local A2DP profile
W/BluetoothAdapter( 1229): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  960): Message: 30
E/BluetoothServiceJni( 1229): SOCK FLAG = 1 ***********************
D/bt-btif ( 1229): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1229): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1229): BTA_JvCreateRecordByUser
D/bt-btif ( 1229): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1229): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1229): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1229): Adding UUID=0x1132 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1229): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1229): BTA_JvRfcommStartServer
D/bt-btif ( 1229): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1229): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1229): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1229): Succeed to create listening socket 
D/BluetoothMapService( 1229): Accepting socket connection...
D/LocalBluetoothProfileManager( 2507): Adding local HEADSET profile
D/BluetoothManagerService(  960): Message: 30
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
D/BluetoothManagerService(  960): Message: 30
D/BluetoothManagerService(  960): Message: 30
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
D/LocalBluetoothProfileManager( 2507): Adding local MAP profile
D/BluetoothMap( 2507): Create BluetoothMap proxy object
D/BluetoothManagerService(  960): Message: 30
D/BluetoothManagerService(  960): Message: 30
V/BluetoothPbapService( 1229): Pbap Service onBind
D/LocalBluetoothProfileManager( 2507): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 2507): [BTUI] initUserBindClient
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
W/ContextImpl( 2507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2507): finishStartingService: stopping service
D/BluetoothA2dp( 2507): Proxy object connected
D/A2dpProfile( 2507): Bluetooth service connected
D/BluetoothHeadset( 2507): Proxy object connected
D/HeadsetProfile( 2507): Bluetooth service connected
D/BluetoothInputDevice( 2507): Proxy object connected
D/HidProfile( 2507): Bluetooth service connected
D/BluetoothPan( 2507): BluetoothPAN Proxy object connected
D/PanProfile( 2507): Bluetooth service connected
D/BluetoothMap( 2507): Proxy object connected
D/MapProfile( 2507): Bluetooth service connected
D/BluetoothMap( 2507): getConnectedDevices()
V/BluetoothMapService( 1229): getConnectedDevices()
D/BluetoothPbap( 2507): Proxy object connected
D/PbapServerProfile( 2507): Bluetooth service connected
D/LGBluetoothUserBindClient( 2507): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2507): onReceive
D/LGBluetoothFeatureConfig( 2507): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2507): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2507): return without doing reset settings.
V/BluetoothOppReceiver( 1229): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1229): [BTUI] startOppService()
V/BluetoothOppManager( 1229): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 1229): isPrivacyLogsEnabled : true
V/BtOppService( 1229): onCreate
D/LGBluetoothOppAdapter( 1229): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppNotification( 1229): send message
V/BtOppService( 1229): Starting RfcommListener
D/BluetoothOppPreference( 1229): Dumping Names:  
D/BluetoothOppPreference( 1229): {}
D/BluetoothOppPreference( 1229): Dumping Channels:  
D/BluetoothOppPreference( 1229): {}
V/BtOppService( 1229): onStartCommand
V/BtOppService( 1229): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 1229): new notify threadi!
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 1229): send delay message
V/BtOppService( 1229): start RfcommListener
V/BtOppService( 1229): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 1229): RfcommListener started
V/BtOppService( 1229): ContentObserver received notification
V/BtOppService( 1229): ContentObserver received notification
V/BtOppService( 1229): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1229): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 1229): Starting RFCOMM listener....
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431b9198 on behalf of 
W/BluetoothAdapter( 1229): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431b9d20 on behalf of 
E/BluetoothServiceJni( 1229): SOCK FLAG = 0 ***********************
D/AuthorizationBluetoothService( 1546): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt-btif ( 1229): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1229): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1229): BTA_JvCreateRecordByUser
E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
D/bt-btif ( 1229): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1229): name:OBEX Object Push, scn:12
D/bt-btif ( 1229): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1229): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1229): Adding UUID=0x1105 into EIR
D/bt-btif ( 1229): BTA is generating EIR
I/bt-btif ( 1229): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1229): BTA_JvRfcommStartServer
D/bt-btif ( 1229): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1229): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
D/LGBluetoothServiceAdapter( 1229): [BTUI] createSocketChannel FD=96 mFd=92
V/BtOppRfcommListener( 1229): Started RFCOMM listener....
I/BtOppRfcommListener( 1229): Accept thread started.
V/BtOppRfcommListener( 1229): Accepting connection...
V/BtOppService( 1229): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431bda48 on behalf of 
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431bd458 on behalf of 
V/BluetoothOppNotification( 1229): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431bfc28 on behalf of 
V/BluetoothOppNotification( 1229): update too frequent, put in queue
V/BtOppService( 1229): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 1229): outbound: succ-0  fail-0
V/BluetoothOppNotification( 1229): outbound notification was removed.
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c2020 on behalf of 
V/BluetoothOppNotification( 1229): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1229): inbound notification was removed.
V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c3708 on behalf of 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 4131): EAPOL: disable timer tick
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: disable timer tick
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1229): new notify threadi!
,V/BluetoothOppNotification( 1229): send delay message
,V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c5198 on behalf of 
,V/BluetoothOppNotification( 1229): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c6dd0 on behalf of 
,V/BluetoothOppNotification( 1229): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1229): outbound notification was removed.
,V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c8960 on behalf of 
,V/BluetoothOppNotification( 1229): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1229): inbound notification was removed.
,V/BluetoothOppProvider( 1229): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1229): created cursor android.database.sqlite.SQLiteCursor@431c9f08 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  271): thread 0xb25b8008 type 0 TID 1001 going to sleep
,V/AudioFlinger(  271): thread 0xb2723008 type 0 TID 929 going to sleep
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4131): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4131): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4131): nl80211: Received scan results (10 BSSes)
,D/wpa_supplicant( 4131): nl80211: Survey data missing
D/wpa_supplicant( 4131): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4131): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 7 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free',
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB',
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 9 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): BSS: last_scan_res_used=10/32 last_scan_full=0,
,D/wpa_supplicant( 4131): wlan0: New scan results available,
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4131): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 4131): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4131): WPS: AP 64:7c:34:12:7f:81 type 0 added,
,D/wpa_supplicant( 4131): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 4131): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4131): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4131): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4131): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4131): WPS: AP[4] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 4131): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4131): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4131): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-49,
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch,
,D/wpa_supplicant( 4131): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-49 wps
D/wpa_supplicant( 4131): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4131): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 4131): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 4131): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb71855a8  current_ssid=0x0
D/wpa_supplicant( 4131): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
,E/wpa_supplicant( 4131): USIM:  scard_init function
D/wpa_supplicant( 4131): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00,
,D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 4131): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4131): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 4131): wlan0: Cancelling scan request
D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4131): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 4131): RSN: PMKSA cache search - network_ctx=0xb71855a8 try_opportunistic=0
D/wpa_supplicant( 4131): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4131): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4131): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2,
,D/wpa_supplicant( 4131): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4131): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4131): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 4131): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4131): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4131): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 4131): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4131): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a],
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 4131): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4131): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 4131): nl80211: Unsubscribe mgmt frames handle 0xb7184590 (mode change)
D/wpa_supplicant( 4131): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590,
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590,
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0c
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11],
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
,D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590,
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
,D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 11,
D/wpa_supplicant( 4131): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 4131):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131):   * freq=2412
D/wpa_supplicant( 4131):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4131):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131):   * Auth Type 0,
D/wpa_supplicant( 4131):   * WPA Versions 0x2,
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 a0:c5:62:7a:49:97]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 06:7c:34:12:7f:81]
D/wpa_supplicant( 4131): nl80211: Connect request send successfully
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4131): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 64:7c:34:12:7f:81],
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:38:27:cc]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ab]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 44:e9:dd:10:c0:ad],
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState,
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4131): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4131): nl80211: Connect event
D/wpa_supplicant( 4131): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4131): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4131): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4131): wlan0: Association info event
D/wpa_supplicant( 4131): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4131): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4131): wlan0: freq=2412 MHz
D/wpa_supplicant( 4131): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4131): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4131): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4131): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): scard is not null..
D/wpa_supplicant( 4131): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4131): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4131): TDLS: Remove peers on association
D/wpa_supplicant( 4131): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4131): EAPOL: enable timer tick
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4131): wlan0: Cancelling scan request
,D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,D/wpa_supplicant( 4131): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 ...
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4131): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4131): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4131): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4131): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4131):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4131):   key_nonce - hexdump(len=32): fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 28 33 b3 95 3b 11 2f ae d9 77 85 23 b5 25 18 cb 43
D/wpa_supplicant( 4131):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 ...
D/wpa_supplicant( 4131): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4131): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4131): Get randomness: len=32 entropy=11
,D/wpa_supplicant( 4131): WPA: Renewed SNonce - hexdump(len=32): 4a da 1d 96 51 f7 6d 36 77 5f 5b 54 26 74 fc d1 f0 28 40 10 2d c2 7b e2 c1 15 b3 59 56 ef 22 2f
,D/wpa_supplicant( 4131): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): WPA: Nonce1 - hexdump(len=32): 4a da 1d 96 51 f7 6d 36 77 5f 5b 54 26 74 fc d1 f0 28 40 10 2d c2 7b e2 c1 15 b3 59 56 ef 22 2f
D/wpa_supplicant( 4131): WPA: Nonce2 - hexdump(len=32): fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 28 33 b3 95 3b 11 2f ae d9 77 85 23 b5 25 18 cb 43
D/wpa_supplicant( 4131): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4131): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4131): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4131): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4131): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4131): WPA: Derived Key MIC - hexdump(len=16): 02 60 55 67 08 5d e7 78 1d bd 7a 36 6c 9e 68 84,
D/wpa_supplicant( 4131): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 4a da 1d 96 51 f7 6d 36 77 5f 5b 54 26 74 fc ...
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,D/wpa_supplicant( 4131): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 ...
D/wpa_supplicant( 4131): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4131): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4131): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4131): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4131):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4131):   key_nonce - hexdump(len=32): fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 28 33 b3 95 3b 11 2f ae d9 77 85 23 b5 25 18 cb 43
D/wpa_supplicant( 4131):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_rsc - hexdump(len=8): e6 09 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_mic - hexdump(len=16): 29 c2 b4 08 7d d6 ac 63 ca 30 15 5d 82 79 6b 98
D/wpa_supplicant( 4131): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 fb 30 6a a1 a0 43 14 15 0c 05 6a bf 4a 8f 53 ...
D/wpa_supplicant( 4131): RSN: encrypted key data - hexdump(len=56): 98 fa cf cf 92 60 8e 7c b7 14 3d fe be 2c 30 e3 fe 08 2a 4c 81 69 0b c6 bb d3 eb d8 fe 21 d2 6e ...
D/wpa_supplicant( 4131): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4131): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4131): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4131): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 4131): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4131): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4131): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4131): WPA: Derived Key MIC - hexdump(len=16): 83 9d 8c 15 87 0c 19 74 b3 3c 8b 90 c0 a9 fd e4
,D/wpa_supplicant( 4131): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 4131): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7184c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4131):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4131): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4131): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4131): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4131): WPA: Group Key - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 4131): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16),
D/wpa_supplicant( 4131): WPA: RSC - hexdump(len=6): e6 09 00 00 00 00
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f6903a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4131):    broadcast key
I/wpa_supplicant( 4131): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 4131): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4131): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4131): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP),
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state SUCCESS,
D/wpa_supplicant( 4131): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4131): EAPOL authentication completed successfully
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]],
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection established
,D/WifiNative-wlan0(  960): doString: STATUS
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4131): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/WifiService(  960): New client listening to asynchronous messages
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@451ffca0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/DhcpStateMachine(  960): StoppedState
D/DhcpStateMachine(  960): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@43ab6730 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-25ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-14ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4263 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/HyLog   ( 4263): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4263): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4263): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QRemote ( 4263): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4263): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4263): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4263): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4263): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4263): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4263): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  960): Killing 3876:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiStateMachine(  960): handleMessage: X
,D/DhcpStateMachine(  960): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4511a8c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4511a8c8 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
,D/WifiStateMachine(  960): ObtainingIpState{ when=-1ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  960): handleMessage: X
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
,V/LgDhcpStateMachineHelper(  960): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: true
,D/WifiStateMachine(  960): handleMessage: E msg.what=196613
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
,D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 1
,D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
,D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  960): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): DHCP successful
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
,D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=0 connState=2
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  960): CaptivePortalCheckState enter
,D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/WifiStateMachine(  960): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QRemote ( 4263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  960): handleMessage: X
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
I/QRemote ( 4263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/wpa_supplicant( 4131): EAPOL: startWhen --> 0
D/wpa_supplicant( 4131): EAPOL: disable timer tick
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
D/QRemote ( 4263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/PCSuite ( 4134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,D/QRemote ( 4263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4263): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4263): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4263): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  612): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  612): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  612): |CAC| updateNetCfgInfo
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC|                   Netconfig               
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  612): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  612): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  612): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  612): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  612): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  612): |CAC| 	NetConfig: Default    =true
,V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  612): |CAC| net type = 1
V/QCNEA   (  612): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  612): |CAC| Received ssid= NG700
V/QCNEA   (  612): |CAC| 	ssid           =NG700
V/QCNEA   (  612): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  612): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  612): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  612): |CAC| dispatchNetCfg: updating:0xb8e9f8dc
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GpsLocationProvider(  960): NTP server returned: 1452517018935 (Mon Jan 11 13:56:58 CET 2016) reference: 116434 certainty: 28 system time offset: -139
E/LocSvc_afw(  960): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
,E/LocSvc_eng(  960): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  960): V/time: 1452517018935
E/LocSvc_eng(  960):   timeReference: 116434
E/LocSvc_eng(  960):   uncertainty: 28
E/LocSvc_utils_q(  960): D/msg_q_snd: Sending message with handle = 0x6B6AEBF8
E/LocSvc_utils_ll(  960): D/linked_list_add: Adding to list data_obj = 0x6B6AEBF8
E/LocSvc_utils_ll(  960): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  960): D/msg_q_rcv: Received message 0x6B6AEBF8 rv = 0
E/LocSvc_eng(  960): V/time: 1452517018935
E/LocSvc_eng(  960):   timeReference: 116434
E/LocSvc_eng(  960):   uncertainty: 28
E/LocSvc_ApiV02(  960): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 28
E/LocSvc_utils_q(  960): D/msg_q_snd: Finished Sending message with handle = 0x6B6AEBF8
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 56, req_id 56 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 56, len = 16
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_eng(  960): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
,E/LocSvc_afw(  960): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
,E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 56, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 56 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  960): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  960): D/msg_q_rcv: Waiting on message
,D/GpsLocationProvider(  960): calling native_inject_xtra_data
,E/LocSvc_afw(  960): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  960): V/length: 59687
E/LocSvc_eng(  960):   data: 0x6a188898
E/LocSvc_utils_q(  960): D/msg_q_snd: Sending message with handle = 0x65FD0E18
E/LocSvc_utils_ll(  960): D/linked_list_add: Adding to list data_obj = 0x65FD0E18
E/LocSvc_utils_q(  960): D/msg_q_snd: Finished Sending message with handle = 0x65FD0E18
E/LocSvc_utils_ll(  960): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  960): D/msg_q_rcv: Received message 0x65FD0E18 rv = 0
E/LocSvc_eng(  960): V/length: 59687
E/LocSvc_eng(  960):   data: 0x6a188898
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 59687
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/59, len = 1024, total injected = 0
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_afw(  960): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/59, len = 1024, total injected = 1024
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/59, len = 1024, total injected = 2048
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/59, len = 1024, total injected = 3072
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/59, len = 1024, total injected = 4096
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/59, len = 1024, total injected = 5120
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/59, len = 1024, total injected = 6144
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/59, len = 1024, total injected = 7168
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/59, len = 1024, total injected = 8192
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/59, len = 1024, total injected = 9216
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/59, len = 1024, total injected = 10240,
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/59, len = 1024, total injected = 11264
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/59, len = 1024, total injected = 12288
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/59, len = 1024, total injected = 13312
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/59, len = 1024, total injected = 14336
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 ,
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
,E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/59, len = 1024, total injected = 15360
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/59, len = 1024, total injected = 16384
,E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408,
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/59, len = 1024, total injected = 17408
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/59, len = 1024, total injected = 18432
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 ,
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456,
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/59, len = 1024, total injected = 19456
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044,
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0),
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/59, len = 1024, total injected = 20480
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/59, len = 1024, total injected = 21504
,E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0,
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0),
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/59, len = 1024, total injected = 22528
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
I/dalvikvm( 4061): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4061): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4061): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4061): Shutting down VM
W/dalvikvm( 4061): threadid=1: thread exiting with uncaught exception (group=0x420b5e48)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/59, len = 1024, total injected = 23552
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/AndroidRuntime( 4061): FATAL EXCEPTION: main
E/AndroidRuntime( 4061): Process: com.test.thalitest, PID: 4061
E/AndroidRuntime( 4061): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4061): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4061): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4061): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4061): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4061): 	,at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4061): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4061): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4061): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4061): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4061): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4061): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4061): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4061): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4061): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4061): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4061): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4061): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4061): 	at dalvik.system.NativeStart.main(Native Method)
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/59, len = 1024, total injected = 24576
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/59, len = 1024, total injected = 25600
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/59, len = 1024, total injected = 26624
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
W/ActivityManager(  960):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f}
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/59, len = 1024, total injected = 27648
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/59, len = 1024, total injected = 28672
,E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/59, len = 1024, total injected = 29696
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/59, len = 1024, total injected = 30720
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/59, len = 1024, total injected = 31744
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
,E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/59, len = 1024, total injected = 32768
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/59, len = 1024, total injected = 33792
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/59, len = 1024, total injected = 34816
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/59, len = 1024, total injected = 35840
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
,E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/59, len = 1024, total injected = 36864
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/59, len = 1024, total injected = 37888
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/59, len = 1024, total injected = 38912
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/59, len = 1024, total injected = 39936
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/59, len = 1024, total injected = 40960
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/59, len = 1024, total injected = 41984
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/59, len = 1024, total injected = 43008
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/59, len = 1024, total injected = 44032
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/59, len = 1024, total injected = 45056
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/59, len = 1024, total injected = 46080
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/59, len = 1024, total injected = 47104
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/59, len = 1024, total injected = 48128
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/59, len = 1024, total injected = 49152
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/59, len = 1024, total injected = 50176
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/59, len = 1024, total injected = 51200
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/59, len = 1024, total injected = 52224
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/59, len = 1024, total injected = 53248
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/59, len = 1024, total injected = 54272
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/59, len = 1024, total injected = 55296
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/59, len = 1024, total injected = 56320
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/59, len = 1024, total injected = 57344
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/59, len = 1024, total injected = 58368
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59392
E/LocSvc_ApiV02(  960): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 59/59, len = 295, total injected = 59392
E/LocSvc_api_v02(  960): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  960): V/loc_sync_select_ind:356]: client handle 0x6732d058, ind_id 53, req_id 53 
E/LocSvc_api_v02(  960): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  960): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  960): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  960): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  960): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  960): V/convertQmiResponseToLocStatus:681]: result = 0, error = 104, status = 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm(  960): GC_FOR_ALLOC freed 1672K, 49% free 29126K/57104K, paused 117ms, total 117ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1229): Disconnected process message: 10
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
,E/LocSvc_api_v02(  960): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6732d058
,E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  960): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  960): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6732d058, resp id = 53, client cookie ptr = 0x6732a070
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:165]: received indication, handle = 0x6732d058 ind_id = 53 
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  960): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  960): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  960): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  960): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  960): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59687
,E/LocSvc_MsgTask(  960): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  960): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  960): Activity pause timeout for ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311dfa0 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  960): moveHomeStack:
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  960): resumeTopActivityLocked: Resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1848): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:56:59
,D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1848): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1848): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1848): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1848): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1848): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:56:59
,D/WeatherService( 1848): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1848): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1848): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
,D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1848): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1848): 2 : Map key string is -2
,D/lim     ( 1848): 2 : time = 13:56
,I/WeatherReflect( 1848): Model Name : LG-D802
D/WeatherTheme( 1848): 2 : Different view - status_min_formatted : 55 != 56
,D/WeatherTheme( 1848): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1848): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1848): 2 : Fixed theme : optimus
,D/WeatherTheme( 1848): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WeatherService( 1848): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:57:0
,D/WeatherService( 1848): 2 : TimeTick Intent And Screen On
D/WeatherService( 1848): 2 : SDK version : 19
,D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1848): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1848): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1848): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1848): 2 : Map key string is -2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/lim     ( 1848): 2 : time = 13:57
I/WeatherReflect( 1848): Model Name : LG-D802
,D/WeatherTheme( 1848): 2 : Different view - status_min_formatted : 56 != 57
,D/WeatherTheme( 1848): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WeatherTheme( 1848): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WeatherTheme( 1848): 2 : Fixed theme : optimus
D/WeatherTheme( 1848): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517020031, nextTick: 60000, mDrawingTime: 1
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/WeatherService( 1848): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:57:0
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517020053, nextTick: 59980, mDrawingTime: 0
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 7323K, 12% free 69145K/78256K, paused 46ms, total 46ms
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/dalvikvm( 1487): GC_CONCURRENT freed 5404K, 9% free 61001K/66588K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/WifiController(  960): battery changed pluggedType: 2
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/WifiController(  960): battery changed pluggedType: 2
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 5009K, 9% free 61609K/67512K, paused 20ms, total 20ms
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1} time:117886
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@430f2fa8 time:117918
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f}
,D/UsbSettings( 2507): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2507): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2507): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2507): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/ActivityManager(  960): Killing 3924:com.google.android.partnersetup/u0a9 (adj 15): empty #17
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{438fb310 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
D/HeadsetStateMachine( 1229): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/        (  960): Unable to set rtc to 1452517021: Invalid argument
,D/        (  960): Setting time of day to sec=1452517021
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WeatherService( 1848): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:57:1
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1157): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,I/[LGHome]LGCalendarIcon( 1487): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517021713, nextTick: 58318, mDrawingTime: 1
,I/[LGHome]LGCalendarIcon( 1487): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517021719, nextTick: 58314, mDrawingTime: 0
,I/MusicWidget( 2086): intentReceiver onReceive() action::android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/CalendarProvider2( 2835): onReceive() android.intent.action.TIME_SET
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/MusicWidget( 2086): beingMusicWidget_4x2() result::false
E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdateStart : false
I/MusicWidget( 2086): beingMusicWidget_Lock() result::false
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/MusicWidget( 2086): beingMusicWidget_Quick() result::false
I/MusicWidget( 2086): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2086): performViewUpdater handleMessage() msg.what::0
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/MusicWidget( 2086): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2086): performUpdate()_4x1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QCNEA   (  612): |CAC| readCallback: read len:0, ret:-1, errno:11
D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
D/WeatherService( 1848): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1848): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1848): 2 : Map key string is -2
D/lim     ( 1848): 2 : time = 13:57
I/WeatherReflect( 1848): Model Name : LG-D802
D/WeatherTheme( 1848): 2 : exactly same view!
D/WeatherTheme( 1848): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 1848): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:57:1
I/MusicWidget( 2086): status::mounted
I/MusicWidget( 2086): defaultAppWidget()_4x1
I/MusicWidget( 2086): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
I/MusicWidget( 2086): setDefaultViewLayoutId()_4x1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/MusicWidget( 2086): appWidgetViewUpdate()_4x1
I/MusicWidget( 2086): linkButtons()_4x1
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
D/AppUp4:CustFacade( 3589): isPhone : true
I/LicenseContentProvider( 2904): start selecting data
D/SIMObserver( 2904): simInfo1
I/MusicWidget( 2086): pushUpdate()_4x1
I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3589): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/MusicWidget( 2086): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2086): beingMusicWidget_Quick() result::false
D/AppUp4:CustModeStarterReceiver( 3589): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3589): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3589): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 3589): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4441 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4441): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4441): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4441): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  960): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4456 uid=10063 gids={50063, 3003, 1028, 1015}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 4456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4456): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4441): DownloadService onCreate
,D/eas_req ( 3964): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4441): in removeSpuriousFiles
,V/DownloadManager( 4441): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@431331c8 on behalf of 4441
,I/DownloadManager( 4441): in trimDatabase
,V/DownloadManager( 4441): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43134a38 on behalf of 4441
,V/DownloadManager( 4441): DownloadService onStartCommand
,V/DownloadManager( 4441): DownloadService onStartCommand
,V/DownloadManager( 4441): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43138960 on behalf of 4441
,V/DownloadManager( 4441): DownloadService onDestroy
,W/linker  ( 3964): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 3964): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 3964): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 3964): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/ActivityManager(  960): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4479 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/dalvikvm( 3964): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 3964): register_HtmlEditor, Success
D/HtmlEditor( 3964): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 3964): register_HtmlEditorTimer, Success
D/HtmlEditor( 3964): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 3964): register_HtmlEditorDownloader, Success
D/HtmlEditor( 3964): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 3964): register_HtmlEditorFont, Success
D/HtmlEditor( 3964): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 3964): register_HtmlEditorDrawText, Success
D/HtmlEditor( 3964): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 3964): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 3964): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 3964): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 3964): JNI_OnLoad Success
I/HubEmail( 3964): JNI_OnLoad()
I/HubEmail( 3964): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 3964): registerNatives()
I/HubEmail( 3964): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 3964): registerNativeMethods()
I/HubEmail( 3964): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 3964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 4479): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4479): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4479): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicWidget( 2086): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2086): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2086): beingMusicWidget_Lock() result::false
I/ActivityManager(  960): Killing 3609:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/ConversationSkinProvider( 4479): skin provider oncreate
,E/[MMS]   ( 4479): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 4479): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4479): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4479): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4479): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 4479): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4479): MmsSettings: Matching Xml Data file name = 2131034168
,D/DelayedSyncController( 4456): Delaying sync.
,W/DriveInitializer( 1943): Background init thread started
,D/[MMS]   ( 4479): MmsSettings: [LGE]parseDTMF() file doesn't exist
,D/[MMS]   ( 4479): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4479): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_char = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_priority = [1]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4479): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4479): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   del_old = [1]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4479): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4479): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   send_msg_enter_key = [1]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4479): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_char_invisible = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4479): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_message_setting = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4479): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   wificalling_feature_set = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4479): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   sms_sent_time_mode = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4479): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4479): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 4479): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 4479): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,E/Auth.Api.Credentials( 1943): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager(  960): Killing 3983:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
I/[MMS]   ( 4479): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4479): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b72c29d8
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
,E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
,E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
E/Diag_Lib(  275):  Message ID ............... 37 
E/Diag_Lib(  275): qmi_service_release called, user_handle=20200
E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  275): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  275): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  275): qmi_service_delete_client_txns : EXIT
,E/Diag_Lib(  275): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
,E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b72c29f0
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
,E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
,E/Diag_Lib(  275):  Message ID ............... 37 
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
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4479): isDrmV1 =true
,V/DrmWrapper( 4479): isDrmV2 =false
V/MmsConfig( 4479): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4479): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 4479): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,W/DriveInitializer( 1943): Awaiting to be initialized
,D/CmasFeatures( 4479): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4479): Contact init()_Create new insatnce
,I/MessagingNotification( 4479): registerLEDObserver
,I/MessagingNotification( 4479): registerLEDObserver REGISTER
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,W/DriveInitializer( 1943): Background init thread ended
V/MmsConfig( 4479): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/LocationManagerService(  960): getProviders()=[passive, gps]
,D/LocationManagerService(  960): request 43c80ff8 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  960): The first listener is added
E/ActivityThread( 4479): Failed to find provider info for com.lge.ims.provider.uc
,I/LOG_TAG ( 4479): registerContactDBChangeObserver
I/LgeMiscReceiver( 4479): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4479): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4479): networkInfo.isConnected() = false
,V/LGRssiData( 4479): [loadRssi] File not exist 
V/LGRssiData( 4479): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4479): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4479): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4479): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4479): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4524 uid=10052 gids={50052, 3003}
I/ActivityManager(  960): Killing 3662:com.android.vending/u0a50 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/HyLog   ( 4524): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4524): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4524): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  960): GC_CONCURRENT freed 2244K, 48% free 30019K/57104K, paused 5ms+6ms, total 92ms
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DelayedSyncController( 4456): Delaying sync.
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4524): [loadRssi] File not exist 
V/LGRssiData( 4524): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4524): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4524): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4524): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4524): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4524): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4524): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4524): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4524): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4524): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4524): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4541 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  960): Killing 1890:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/HyLog   ( 4541): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4541): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4541): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1943): Checking schedule, now: 1452517022328 next: 1452511824974
,I/CheckinService( 1943): active receiver: enabled
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/CheckinService( 1943): Preparing to send checkin request
,I/EventLogService( 1943): Accumulating logs since 1452516113373
,D/DrmBroadcastReceiver( 4541): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  960): Killing 4195:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 1943): GC_CONCURRENT freed 1202K, 23% free 19252K/24832K, paused 3ms+4ms, total 39ms
,I/NFS     ( 4209): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4209): CONNECT : WIFI_CONNECT
,D/dalvikvm( 1546): GC_EXPLICIT freed 257K, 29% free 17824K/24832K, paused 1ms+5ms, total 28ms
I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4556 uid=10104 gids={50104, 3003, 1028, 1015}
,D/HyLog   ( 4556): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4556): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4556): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4556): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
D/WifiService(  960): New client listening to asynchronous messages
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4556): Binding Chromium to the main looper Looper (main, tid 1) {430f3d48}
,W/BaseRuntimeLoader( 1943): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1943): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/chromium( 4556): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
W/BaseRuntimeLoader( 1943): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1943): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/BrowserProcessMain( 4556): Initializing chromium process, renderers=0
,W/chromium( 4556): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4556): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4556): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4556): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4556): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4556): Remote Branch: 
I/Adreno-EGL( 4556): Local Patches: 
I/Adreno-EGL( 4556): Reconstruct Branch: 
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NSApplication( 4556): Starting up...
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/ActivityManager(  960): Killing 3952:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm( 3643): GC_FOR_ALLOC freed 741K, 16% free 20910K/24832K, paused 13ms, total 13ms
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 26.502MB for 4099024-byte allocation
D/NotificationService(  960): updateLightListLocked :r=null, action=2
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 3643): GC_CONCURRENT freed 24K, 14% free 24900K/28836K, paused 3ms+5ms, total 18ms
,I/iu.SyncManager( 1943): SYNC; picasa accounts
,D/NetworkLogImpl( 1943): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1943): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1943): num queued entries: 0
,I/iu.UploadsManager( 1943): num updated entries: 0
,I/iu.SyncManager( 1943): NEXT; no task
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4601 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  960): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4613 uid=10010 gids={50010, 3003, 1028, 4002}
,D/HyLog   ( 4601): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4601): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4601): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/HyLog   ( 4613): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4613): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4613): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/dalvikvm( 4601): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4601): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4601): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4601): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4601): VFY: replacing opcode 0x62 at 0x005e
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
I/MultiDex( 4601): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4601): install
,I/MultiDex( 4601): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
,E/OpenGL ES Test( 4613): localeFound retString == en_US
,D/ALBootInit( 4613): ====action==>android.intent.action.TIME_SET
I/MultiDex( 4601): loading existing secondary dex files
,D/ALBootInit( 4613): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4613): [setNextAlert] start
,I/MultiDex( 4601): load found 3 secondary dex files
,I/MultiDex( 4601): install done
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
,D/Alarms  ( 4613): [setNextAlert] (1)
,D/Alarms  ( 4613):  minTime  = 0
,D/Alarms  ( 4613):  -- OK multi -- 0
E/jeny.kim( 4613): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4613): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4613): setStatusBarIcon : false
,D/Alarms  ( 4613): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/dalvikvm( 4601): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4601): VFY: unable to resolve instance field 61
,D/dalvikvm( 4601): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4601): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4601): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4601): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4601): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4601): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4601): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4601): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4601): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4601): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430fd388
D/dalvikvm( 4601): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430fd388
D/dalvikvm( 4601): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430fd388, skipping init
,D/WorldClockReceiver( 4613): ====action==>android.intent.action.TIME_SET
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
D/dalvikvm( 4601): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430fd388
D/dalvikvm( 4601): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430fd388
V/JNIHelp ( 4601): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
,E/OpenGL ES Test( 4613): localeFound retString == en_US
,E/OpenGL ES Test( 4613): isExistDatabase = false
I/CommonUtil( 4613): BUILD Country: EU
E/OpenGL ES Test( 4613): loadMapCityData() -- S
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
,E/OpenGL ES Test( 4613): localeFound retString == en_US
,D/dalvikvm( 4601): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430fd388
D/dalvikvm( 4601): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430fd388
,D/dalvikvm( 4601): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430fd388
,D/dalvikvm( 4601): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430fd388
,E/OpenGL ES Test( 4613): loadMapCityData() - While S
,I/ProviderInstaller( 4601): Installed default security provider GmsCore_OpenSSL
,E/OpenGL ES Test( 4613): loadMapCityData() - While E
E/OpenGL ES Test( 4613): loadMapCityData() -- E
,E/OpenGL ES Test( 4613): getCurrentLocale == en_US
E/OpenGL ES Test( 4613): localeFound retString == en_US
E/OpenGL ES Test( 4613): getCurrentLocale == en_US
,E/OpenGL ES Test( 4613): localeFound retString == en_US
,E/OpenGL ES Test( 4613): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/dalvikvm( 4601): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4601): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4601): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4601): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4601): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4601): VFY: replacing opcode 0x6e at 0x0201
,I/ActivityManager(  960): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4631 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4165:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
D/HyLog   ( 4631): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4631): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4631): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Config  ( 4631): LGCalendar ver.4.2.6
I/Config  ( 4631): start check model
,I/Config  ( 4631): start check native_ca
,E/Config  ( 4631): [setCountryAndOperator] Operator=OPEN, Country=EU
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  271): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  271): App is not loaded in QSEE
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
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,D/QSEECOMAPI: (  271): Loaded image: APP id = 2
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2f000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2f000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/CalendarWidget( 4631): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,D/GCM     ( 1546): Connected
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/dalvikvm( 4601): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43304cb8
D/dalvikvm( 4601): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43304cb8
,D/Tethering(  960): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 4601): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43304cb8, skipping init
D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,I/VacuumService( 1546): Vacuum at: now=1452517023048 tag=VacuumService
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1546): Message class com.google.f.a.a.p
D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1139604046
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/InitNotificationRingtoneService( 4631): Start InitializeAlertRingtoneService.onHandleIntent
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/ActivityManager(  960): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4664 uid=10043 gids={50043, 3003, 1028, 1015}
,I/InitNotificationRingtoneService( 4631): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4631): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4631): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4631): End InitializeAlertRingtoneService.onHandleIntent
,D/HyLog   ( 4664): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4664): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4664): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
I/ActivityManager(  960): Killing 4134:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,W/Settings( 4601): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/TASKS   ( 4664): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4664): onReceive() #################################################
,I/TASKS   ( 4664): getCurrentThemeInfo START #############################
,I/TASKS   ( 4664): com.lge.launcher2.theme.optimus
I/TASKS   ( 4664): com.lge.task
I/TASKS   ( 4664): getCurrentThemeInfo END #############################
I/TASKS   ( 4664): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4664): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4664): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  960): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4682 uid=10122 gids={50122}
,I/ActivityManager(  960): Killing 4263:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4601): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
D/HyLog   ( 4682): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4682): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4682): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4682): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x430f4ea0, skipping init
,D/TimeService( 4682): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452517023253
D/        ( 4682): TimeServiceNative: User Time to be set is 1452517023253
D/QC-time-services( 4682): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4682): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4682): Lib:time_genoff_operation: pargs->ts_val = 1452517023253
D/QC-time-services(  623): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4682): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  623): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452517023253
D/QC-time-services(  623): Daemon:genoff_opr: Base = 2, val = 1452517023253, operation = 0
D/QC-time-services(  623): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/19/70 0:41:30
D/QC-time-services(  623): Daemon:Value read from RTC seconds = 11925690000
D/QC-time-services(  623): Daemon:new time 1452517023253 
D/QC-time-services(  623): Daemon: delta 1440591333253 genoff 1440591333253 
D/QC-time-services(  623): Daemon:genoff_persistent_update: Writing genoff = 1440591333253 to memory
D/QC-time-services(  623): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  623): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QC-time-services(  623): Updating the TOD offset
D/QC-time-services(  623): Daemon:genoff_persistent_update: Writing genoff = 1440591333253 to memory
D/QC-time-services(  623): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  623): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  623): Daemon:Update to modem bit set
D/QC-time-services(  623): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  623): Daemon: Base = 2, Value being sent to MODEM = 1136552223253
,E/QC-time-services( 4682): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  623): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  623): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  960): Killing 4061:com.test.thalitest/u0a304 (adj 15): empty #17
,D/dalvikvm( 4694): DexOpt: load 2ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4601): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4601): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 62ms
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4601): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4601): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4601): Remote Branch: 
I/Adreno-EGL( 4601): Local Patches: 
I/Adreno-EGL( 4601): Reconstruct Branch: 
I/WindowState(  960): WIN DEATH: Window{430e7d68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  960): Client connection lost with reason: 4
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{456addf8 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  960): IME STATUS OFF
,W/Binder  ( 1316): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1316): java.lang.NullPointerException
W/Binder  ( 1316): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1316): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1316): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1316): 	at dalvik.system.NativeStart.run(Native Method)
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 4061 uid 10304
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 2904): start selecting data
,D/SIMObserver( 2904): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
,I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4441): DownloadService onCreate
,I/DownloadManager( 4441): in removeSpuriousFiles
V/DownloadManager( 4441): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4479): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4479): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4479): networkInfo.isConnected() = true
,D/PhoneState( 4479): setPdpRejectCasuse : false
,W/Settings( 3964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
,D/DrmBroadcastReceiver( 4541): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4541): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 4541): Service onCreate
,D/DrmService( 4541): Received new request = 2
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4601): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4601): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4601): Remote Branch: 
I/Adreno-EGL( 4601): Local Patches: 
I/Adreno-EGL( 4601): Reconstruct Branch: 
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DrmSntpClient( 4541): Start Sync process
,D/DrmSntpClient( 4541): Server : 0
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/DataScheduler( 4541): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4705 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4705): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/LGDMSGCM( 4705): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 4209): connectivityManager.getNetworkInfo = TYPE_WIFI
D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/Wireless_Storage( 4209): CONNECT : WIFI_CONNECT
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
W/ContextImpl( 4705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,I/LGDrmService( 4541): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  275): [DRM] SET TIME : YR=2016, MON=1, DAY=11
,I/LGDRM   (  275): [DRM] SET TIME : HR=12, MIN=57, SEC=3
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=6284542
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/DrmSntpClient( 4541): Synched
D/DrmService( 4541): Completed !! request = 2
D/DrmService( 4541): Request count = 0
,D/dalvikvm( 3643): GC_FOR_ALLOC freed 22K, 14% free 24894K/28836K, paused 24ms, total 25ms
,V/DrmService( 4541): Service onDestroy
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 30.393MB for 4099024-byte allocation
,D/dalvikvm(  960): GC_EXPLICIT freed 1139K, 47% free 30368K/57104K, paused 3ms+10ms, total 131ms
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43141b90 on behalf of 4441
,I/DownloadManager( 4441): in trimDatabase
V/DownloadManager( 4441): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4441): DownloadService onStartCommand
,V/DownloadManager( 4441): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43143500 on behalf of 4441
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43144d90 on behalf of 4441
,V/DownloadManager( 4441): DownloadService onDestroy
,D/WeatherAncestor( 1848): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:57:3
,I/ActivityManager(  960): Killing 3625:com.android.gallery3d/u0a27 (adj 15): empty #17
D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
D/Weather_cast( 1848): 2 : Request from alarm is Canceled
D/WeatherAncestor( 1848): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:57:3
D/WeatherService( 1848): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
D/WeatherQuickCover( 1848): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1848): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/dalvikvm( 3643): GC_CONCURRENT freed 5K, 13% free 28891K/32840K, paused 2ms+2ms, total 33ms
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
D/AuthorizationBluetoothService( 1546): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/ActivityManager(  960): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4725 uid=10050 gids={50050, 3003, 1028, 1015}
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,I/ActivityManager(  960): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4737 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/LocationInitializer( 1943): Restart initialization of location
D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4725): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Adreno-EGL( 4601): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4601): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4601): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4601): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4601): Remote Branch: 
I/Adreno-EGL( 4601): Local Patches: 
I/Adreno-EGL( 4601): Reconstruct Branch: 
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4751 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4737): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4751): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4737): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4737): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4725): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 4725): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x000b
D/dalvikvm( 4737): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4737): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4737): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4737): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4737): install
,I/MultiDex( 4737): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4737): loading existing secondary dex files
,I/MultiDex( 4737): load found 3 secondary dex files
,I/MultiDex( 4737): install done
,D/Finsky  ( 4725): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/dalvikvm( 4737): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4737): VFY: unable to resolve instance field 61
,D/dalvikvm( 4737): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4737): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4737): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4737): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4737): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4737): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4737): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4737): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4737): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4737): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f9498
,D/dalvikvm( 4737): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f9498
,D/dalvikvm( 4737): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f9498, skipping init
,D/dalvikvm( 4737): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f9498
D/dalvikvm( 4737): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f9498
,V/JNIHelp ( 4737): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/dalvikvm( 4725): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 4725): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/dalvikvm( 4737): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f9498
,D/dalvikvm( 4737): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430f9498
D/dalvikvm( 4737): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f9498
,D/dalvikvm( 4737): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430f9498
,D/Finsky  ( 4725): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/MediaCodecList( 4751): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4751): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4751): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4751): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 4751): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4751): MmsConfig.loadMmsSettings
,I/Babel   ( 4751): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4751): MmsConfig.loadFromDatabase
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,W/BaseRuntimeLoader( 4751): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4751): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4751): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4751): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 4751): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4751): MmsConfig.loadFromResources
,W/Settings( 4751): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityThread(  960): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/Babel   ( 4751): canonicalizeMccMnc: invalid mccmnc nullnull
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
I/Babel   ( 4751): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/LGRssiData( 4751): [loadRssi] File not exist 
V/LGRssiData( 4751): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4751): [loadFeatureFromXml] *** start feature loading from xml
W/Settings( 4725): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4725): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/TelephonyAutoProfiling( 4751): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4751): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4751): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/dalvikvm( 4725): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4725): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 4725): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4725): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4725): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4725): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x029a
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
,D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 2904): start selecting data
,D/SIMObserver( 2904): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
,I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/dalvikvm( 4725): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4725): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4441): DownloadService onCreate
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 3964): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/dalvikvm( 4725): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 4725): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0049
,I/LgeMiscReceiver( 4479): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4479): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4479): networkInfo.isConnected() = true
D/PhoneState( 4479): setPdpRejectCasuse : false
,W/Settings( 3964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4441): in removeSpuriousFiles
,V/DownloadManager( 4441): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4441): DownloadService onStartCommand
,V/DownloadManager( 4441): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@43149d28 on behalf of 4441
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@4314ba30 on behalf of 4441
D/LGDMSGCM( 4705): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 4441): in trimDatabase
,V/DownloadManager( 4441): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@4314ceb0 on behalf of 4441
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4209): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4209): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4705): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4441): DownloadService onDestroy
,I/ProviderInstaller( 4737): Installed default security provider GmsCore_OpenSSL
,V/DownloadManager( 4441): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4441): created cursor android.database.sqlite.SQLiteCursor@431520c0 on behalf of 4725
,D/dalvikvm( 3643): GC_FOR_ALLOC freed 2K, 13% free 28891K/32840K, paused 13ms, total 13ms
,D/Finsky  ( 4725): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4725): [1] 2.run: Finished loading 1 libraries.
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 34.297MB for 4099024-byte allocation
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/Finsky  ( 4725): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/dalvikvm( 4737): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 4737): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4737): VFY: replacing opcode 0x6e at 0x003f
,D/Finsky  ( 4725): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WearableService( 4737): callingUid 10006, callindPid: 4737
D/CalendarWidget( 4631): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4631): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,E/dalvikvm( 4737): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4737): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4737): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4737): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 3643): GC_CONCURRENT freed 4K, 11% free 33053K/36844K, paused 8ms+1ms, total 39ms
D/TASKS_APP_WIDGET( 4664): onReceive() #################################################
,I/TASKS   ( 4664): getCurrentThemeInfo START #############################
I/TASKS   ( 4664): com.lge.launcher2.theme.optimus
I/TASKS   ( 4664): com.lge.task
I/TASKS   ( 4664): getCurrentThemeInfo END #############################
I/TASKS   ( 4664): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4664): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4664): intentAction : com.lge.task.APPWIDGET_UPDATE
,D/CalendarWidget( 4631): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4631): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/dalvikvm( 4737): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4737): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4737): VFY: replacing opcode 0x6e at 0x000d
,D/AuthorizationBluetoothService( 1546): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
,I/dalvikvm( 4737): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4737): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4737): VFY: replacing opcode 0x6e at 0x0201
,V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1422): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1422): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1943): Restart initialization of location
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,I/dalvikvm( 4725): Total arena pages for JIT: 11
,I/dalvikvm( 4725): Total arena pages for JIT: 12
I/dalvikvm( 4725): Total arena pages for JIT: 13
,I/dalvikvm( 4725): Total arena pages for JIT: 14
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4725): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4725): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  960): Killing 4613:com.lge.clock/u0a10 (adj 15): empty #17
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4751): UserRecoverableAuthException.
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
E/Babel   ( 4751): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4751): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4751): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
E/Babel   ( 4751): Error getting auth token
E/Babel   ( 4751): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4751): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
E/Babel   ( 4751): Account registration failedRedacted-21
E/Babel   ( 4751): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4751): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4751): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 4751): Account sign in complete with state 106account: Redacted-21
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x439572d8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/Babel   ( 4751): Unexpected exception while authenticating.
,E/Babel   ( 4751): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4751): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4751): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4751): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4751): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4751): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4751): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4725): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4725): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4725): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4725): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1546): GC_EXPLICIT freed 1771K, 29% free 17853K/24832K, paused 3ms+6ms, total 48ms
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Finsky  ( 4725): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4725): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Finsky  ( 4725): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4725): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4725): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4725): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1943): Sending checkin request (11634 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
,D/dalvikvm(  960): GC_EXPLICIT freed 1684K, 47% free 30545K/57104K, paused 6ms+22ms, total 213ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x43b718a8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,I/CheckinTask( 1943): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1943): Checking schedule, now: 1452517027146 next: 1453094423144
,I/CheckinService( 1943): active receiver: disabled
,I/CheckinService( 1943): Checking schedule, now: 1452517027177 next: 1453094423144
,I/CheckinService( 1943): active receiver: disabled
,D/dalvikvm( 1943): GC_CONCURRENT freed 1698K, 22% free 19514K/24832K, paused 2ms+4ms, total 36ms
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4556): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.462143 Y: -0.425110 Z: 9.829590 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462143 .y:-0.425110 .z:9.829590
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.458969 Y: -0.427383 Z: 9.820999 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458969 .y:-0.427383 .z:9.820999
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/ActivityManager(  960): Killing 4682:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Killing 2904:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityThread( 3589): Removing dead content provider:android.content.ContentProviderProxy@43148538
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  960): Killing 4751:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3505): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3505): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,D/administrator(  960): Handling package changes for user 0
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.talk
E/SlideAside( 3505): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3505): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/AppUp4  ( 3589): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3589): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
,D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=4913 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 6296K, 13% free 68757K/78256K, paused 40ms, total 40ms
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4913): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/LicenseContentProvider( 4913): start selecting data
,W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 4913): simInfo1
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 3589): Event For Nothing, skip.
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  960): Handling package changes for user 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4928 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  960): Killing 4441:android.process.media/u0a23 (adj 15): empty #17
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  960):   Scheme: "mmsto"
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/WifiController(  960): battery changed pluggedType: 2
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/SystemConfig( 4928): BUILD Country: EU
,I/SystemConfig( 4928): BUILD Operator: OPEN
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/ActivityManager(  960): Killing 3964:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4943 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,I/SystemConfig( 4928): systemFeature RCS result false
,D/SystemConfig( 4928): refreshRcsSupport() :false
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4943): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IcingCorporaProvider( 2600): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  960): Killing 4479:com.android.mms/u0a35 (adj 15): empty #17
D/CountryDetector(  960): No listener is left
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/LocationManagerService(  960): remove 43c80ff8
D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
,D/LocationProviderProxy(  960): applying state to connected service
,D/LocationProviderProxy(  960): applying state to connected service
,I/IcingCorporaProvider( 2600): UpdateCorporaTask done [took 40 ms] updated apps [took 40 ms] 
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4961 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PeopleContactsSync( 1943): CP2 sync disabled
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/HyLog   ( 4961): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4961): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4961): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/Babel   ( 4961): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4961): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4961): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4961): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 4961): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/MediaCodecList( 4961): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 4961): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 4961): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4961): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4961): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4961): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4961): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4961): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4961): MmsConfig.loadFromResources
,E/Babel   ( 4961): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4961): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4961): [loadRssi] File not exist 
V/LGRssiData( 4961): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4961): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 4961): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4961): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4961): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3589): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3589): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 4913): start selecting data
,D/SIMObserver( 4913): simInfo1
I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3589): begin check event
D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3589): Event For Nothing, skip.
,I/IcingCorporaProvider( 2600): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  960): Delaying start of: ServiceRecord{45635db0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  960): Killing 4524:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,I/IcingCorporaProvider( 2600): UpdateCorporaTask done [took 203 ms] updated apps [took 203 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1229): Disconnected process message: 10
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 4961): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4131): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/PowerManagerService(  960): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  960): [updateScreenState] screen on = false
,D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  960): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8985 usec
,D/qcom_sensors_hal(  960): hal_acquire_resources
,I/qcom_sensors_hal(  960): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  960): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  960): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  960): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  960): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  960): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.451553 Y: -0.403564 Z: 9.825516 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451553 .y:-0.403564 .z:9.825516
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  960): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.453415 Y: -0.397354 Z: 9.832535 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453415 .y:-0.397354 .z:9.832535
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Sensors (  596): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  960): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  960): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  960): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  960): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  960): proximitySensorChanged  positive = true
I/KnockOnPowerController(  960): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.454041 Y: -0.399246 Z: 9.820541 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454041 .y:-0.399246 .z:9.820541
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.456406 Y: -0.406815 Z: 9.809647 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456406 .y:-0.406815 .z:9.809647
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.453964 Y: -0.406113 Z: 9.819473 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453964 .y:-0.406113 .z:9.819473
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/Finsky  ( 4725): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4725): [1] 5.onFinished: Installation state replication succeeded.
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.450638 Y: -0.405701 Z: 9.824493 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450638 .y:-0.405701 .z:9.824493
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  960): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44c185f0)
D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  960): **** SHOWN CALLED ****
,D/WifiStateMachine(  960): handleScreenStateChanged: true
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4131): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  960): sendKtScanInterval  mRtspPlay : false
,I/WindowManager(  960): No lock screen! windowToken=null
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8b6d450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
D/WeatherAncestor( 1848): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:57:20
D/wpa_supplicant( 4131): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131127
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132097
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  960): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4131): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4131): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  960): handleMessage: X
D/UpdateThreadPoolManager( 1848): 2 : This is isUpdating : false
D/WeatherAncestor( 1848): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:57:20
D/WeatherService( 1848): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WifiOffDelayIfNotUsed(  960): stopMonitoring
E/SlideAside( 3505): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/SlideAside( 3505): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WeatherService( 1848): 2 : TimeTick Receiver Unregister
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.456390 Y: -0.421219 Z: 9.808304 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456390 .y:-0.421219 .z:9.808304
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43c68650 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/dalvikvm( 1157): GC_CONCURRENT freed 2846K, 11% free 25470K/28496K, paused 2ms+2ms, total 20ms
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in blankDisplay() while turning screen off: 418ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517040914, nextTick: 39117, mDrawingTime: 1
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517040961, nextTick: 39072, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/WeatherService( 1848): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:57:20
,D/WeatherService( 1848): 2 : ACTION screen on
,D/WeatherService( 1848): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/WeatherService( 1848): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:57:21
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
,I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, enabled=0
,D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
,I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  960): hal_acquire_resources
D/qcom_sensors_hal(  960): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,I/LGImmersionVibrator(  960): Vibrator off
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  960): handleScreenStateChanged: false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  960): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  960): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: Rcvd success response from request
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{43a260f0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1157): clear
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
D/WeatherService( 1848): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:57:21
,D/WeatherService( 1848): 2 : ACTION screen off
,D/WeatherService( 1848): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:57:21
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
,D/NfcService( 1472): NFC-C OFF
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  596): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517049190317897; DSPS: 4946086; Offset: 1452516898247751980
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517069190753693; DSPS: 5601460; Offset: 1452516898247760529
,I/GoogleURLConnFactory( 1546): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1546): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1546):  no longer exists, so no auth token.
,W/Uploader( 1546): No account for auth token provided
,W/Uploader( 1546): No account for auth token provided
,W/Uploader( 1546): No account for auth token provided
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517080040, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517080054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517089191662134; DSPS: 6256850; Offset: 1452516898247753443
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2,
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517109192128177; DSPS: 6912225; Offset: 1452516898247761722
,I/rmt_storage(  625): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb8c9b178
I/rmt_storage(  625): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  625): wakelock acquired: 1, error no: 42
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194741192)
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194741192) wakelock released: 1, error no: 0
I/rmt_storage(  625): 
I/rmt_storage(  625): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb8c9b178
,E/Diag_Lib(  733): [IMS_FATAL]| 2912 | 748 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517129193820093; DSPS: 7567640; Offset: 1452516898247775172
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517140034, nextTick: 59992, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517140045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517149194707605; DSPS: 8223029; Offset: 1452516898247777674
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517169195158583; DSPS: 8878404; Offset: 1452516898247770888
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517189199697223; DSPS: 9533913; Offset: 1452516898247762409
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517200049, nextTick: 59970, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517200057, nextTick: 59976, mDrawingTime: 0
,D/dalvikvm(  960): GC_CONCURRENT freed 3185K, 46% free 30765K/55956K, paused 19ms+12ms, total 190ms
,D/wpa_supplicant( 4131): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 7 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 9 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:38:27:cc]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517209200159234; DSPS: 10189288; Offset: 1452516898247766656
,D/dalvikvm( 2586): GC_CONCURRENT freed 7767K, 33% free 16759K/24832K, paused 15ms+2ms, total 86ms
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517229201131068; DSPS: 10844680; Offset: 1452516898247761928
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517249202036269; DSPS: 11500070; Offset: 1452516898247751602
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517260051, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517260056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517269203536189; DSPS: 12155479; Offset: 1452516898247756160
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517289204454013; DSPS: 12810869; Offset: 1452516898247758457
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517309205757143; DSPS: 13466272; Offset: 1452516898247749331
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517320047, nextTick: 59981, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517320054, nextTick: 59979, mDrawingTime: 0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1546): GC_CONCURRENT freed 1702K, 28% free 18123K/24832K, paused 4ms+5ms, total 47ms
,D/dalvikvm( 1546): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/GLSActivity( 1546): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1546): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1546): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1546): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1546): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1546): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1546): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1546): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x434cc238: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/PlayEventLogger( 4725): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4725): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4725): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4725): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4725): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517329208824278; DSPS: 14121732; Offset: 1452516898247764708
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517349210189947; DSPS: 14777137; Offset: 1452516898247757086
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517369211494655; DSPS: 15432540; Offset: 1452516898247749538
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517380033, nextTick: 59996, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517380040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517389213476994; DSPS: 16087964; Offset: 1452516898247778752
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517409214414735; DSPS: 16743355; Offset: 1452516898247770448
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517429215698861; DSPS: 17398757; Offset: 1452516898247772836
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517440039, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517440047, nextTick: 59985, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517449217058153; DSPS: 18054162; Offset: 1452516898247758837
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517469218416682; DSPS: 18709566; Offset: 1452516898247774593
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517489219713171; DSPS: 19364969; Offset: 1452516898247758826
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517500040, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517500052, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517509220700444; DSPS: 20020361; Offset: 1452516898247769536
,I/ActivityManager(  960): Killing 4456:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517529221595944; DSPS: 20675751; Offset: 1452516898247749509
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517549223493381; DSPS: 21331173; Offset: 1452516898247754856
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517560039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517560041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517569224390756; DSPS: 21986562; Offset: 1452516898247767221
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517589225330514; DSPS: 22641953; Offset: 1452516898247760934,
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517609226632035; DSPS: 23297355; Offset: 1452516898247780717
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517620039, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517620047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517629227535164; DSPS: 23952745; Offset: 1452516898247768319
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517649228507720; DSPS: 24608137; Offset: 1452516898247764312
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517669229827065; DSPS: 25263540; Offset: 1452516898247771401
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517680053, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517680054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517689230743215; DSPS: 25918930; Offset: 1452516898247772024
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517709232099726; DSPS: 26574334; Offset: 1452516898247785762
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517729234232073; DSPS: 27229764; Offset: 1452516898247781878
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  960): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  960): Done.
,D/QcConnectivityService(  960): Setting timer for 720seconds
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517740032, nextTick: 59994, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517740056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517749235589246; DSPS: 27885169; Offset: 1452516898247765760
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517769236938487; DSPS: 28540573; Offset: 1452516898247772228
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517789238294754; DSPS: 29195978; Offset: 1452516898247755204
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517800050, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517800057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517809239240572; DSPS: 29851369; Offset: 1452516898247754977
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517829240166409; DSPS: 30506759; Offset: 1452516898247765286
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517849241472023; DSPS: 31162162; Offset: 1452516898247758645
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517860029, nextTick: 59979, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517860057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517869242417192; DSPS: 31817553; Offset: 1452516898247757769
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517889243898064; DSPS: 32472961; Offset: 1452516898247773797
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517909245227180; DSPS: 33128365; Offset: 1452516898247760139
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517920046, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517920062, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517929246582841; DSPS: 33783769; Offset: 1452516898247773027
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517949247510474; DSPS: 34439160; Offset: 1452516898247754615
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517969248835466; DSPS: 35094563; Offset: 1452516898247767351
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517980029, nextTick: 59979, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452517980057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452517989249726381; DSPS: 35749952; Offset: 1452516898247773256
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518009250659632; DSPS: 36405343; Offset: 1452516898247760463
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518029251966651; DSPS: 37060746; Offset: 1452516898247755226
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518040033, nextTick: 59994, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518040035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518049253452726; DSPS: 37716154; Offset: 1452516898247776457
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518069254431096; DSPS: 38371547; Offset: 1452516898247747747
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518089255744778; DSPS: 39026949; Offset: 1452516898247779691
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518100046, nextTick: 59976, mDrawingTime: 5,
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518100054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518109256683480; DSPS: 39682340; Offset: 1452516898247772348
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518129257616040; DSPS: 40337731; Offset: 1452516898247758863
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518149258937303; DSPS: 40993134; Offset: 1452516898247767870
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518160032, nextTick: 59994, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518160035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518169259871342; DSPS: 41648525; Offset: 1452516898247755864
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518189260804260; DSPS: 42303915; Offset: 1452516898247773255
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518209262175145; DSPS: 42959320; Offset: 1452516898247770849
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518220048, nextTick: 59974, mDrawingTime: 5,
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518220054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518229263665342; DSPS: 43614729; Offset: 1452516898247765684
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518249265003057; DSPS: 44270133; Offset: 1452516898247760626
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518269266306119; DSPS: 44925535; Offset: 1452516898247781950
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518280032, nextTick: 59994, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518280035, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518289267203549; DSPS: 45580925; Offset: 1452516898247763852
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518309268131016; DSPS: 46236315; Offset: 1452516898247775792
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518329269433914; DSPS: 46891718; Offset: 1452516898247766434
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518340034, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518340044, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518349270380552; DSPS: 47547109; Offset: 1452516898247767027
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518369271263089; DSPS: 48202498; Offset: 1452516898247764554
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518389272547371; DSPS: 48857900; Offset: 1452516898247767098
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518400044, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518400055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518409273943393; DSPS: 49513306; Offset: 1452516898247759311
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518429274888108; DSPS: 50168697; Offset: 1452516898247757982
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518449276186280; DSPS: 50824099; Offset: 1452516898247774415
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  960): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  960): Done.
,D/QcConnectivityService(  960): Setting timer for 720seconds
,I/EventLogService( 1943): Aggregate from 1452517022477 (log), 1452516113373 (data)
,D/GCM     ( 1546): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518460046, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518460055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518469277531230; DSPS: 51479504; Offset: 1452516898247746074
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518489278511872; DSPS: 52134895; Offset: 1452516898247780671
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518509279819598; DSPS: 52790298; Offset: 1452516898247776141
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518520033, nextTick: 59982, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518520043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518529281125865; DSPS: 53445701; Offset: 1452516898247770153
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518549282051634; DSPS: 54101091; Offset: 1452516898247780394
,D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 4131): nl80211: Disconnect event
D/wpa_supplicant( 4131): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 4131): wlan0: Deauthentication notification
D/wpa_supplicant( 4131): wlan0:  * reason 0
D/wpa_supplicant( 4131): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 4131): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 4131): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 4131): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 4131): wlan0: Blacklist count 1 --> request scan in 100 ms
,D/wpa_supplicant( 4131): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): TDLS: Remove peers on disassociation
D/wpa_supplicant( 4131): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  960): handleMessage: E msg.what=147460,
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState,
,D/WifiStateMachine(  960): processMsg: ConnectModeState,
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP
,D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 1,
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7183d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4131):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4131): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/DhcpStateMachine(  960): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  960): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiHS20(  960): hidePasspointNotification off =false
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
D/QCNEA   (  612): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  612): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  612): |CAC| updateNetCfgInfo
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC|                   Netconfig               
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  612): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  612): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  612): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  612): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  612): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  612): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| Received bssid= 
D/QCNEA   (  612): |CAC| net type = 3
V/QCNEA   (  612): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  612): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  612): |CAC| 	ssid           =NG700
V/QCNEA   (  612): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  612): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  612): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  612): |CAC| dispatchNetCfg: updating:0xb8e9f8dc
D/QCNEA   (  612): |CAC| readCallback: read len:0, ret:-1, errno:11
D/wpa_supplicant( 4131): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4131): wlan0: nl80211: scan request
D/wpa_supplicant( 4131): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/wpa_supplicant( 4131): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4131): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6473 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 6473): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6473): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6473): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PCSuite ( 6473): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/PCSuite ( 6473): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6473): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
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
D/NetUtils(  960): android_net_utils_resetConnections in env=0x628b4978 clazz=0x97200001 iface=wlan0 mask=0x3
I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6512 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  960): Killing 4541:com.lge.drmservice/u0a66 (adj 15): empty #17
D/QcConnectivityService(  960): resetConnections(wlan0, 3)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,V/NativeCrypto( 1546): Read error: ssl=0x60be1b30: I/O error during system call, Connection timed out
D/DhcpStateMachine(  960): StoppedState
,V/NativeCrypto( 1546): SSL shutdown failed: ssl=0x60be1b30: I/O error during system call, Broken pipe
,D/HyLog   ( 6512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6512): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QRemote ( 6512): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 6512): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 6512): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6512): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6512): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6512): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6512): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6512): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6512): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  960): Killing 4705:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518569284211719; DSPS: 54756522; Offset: 1452516898247773731
,D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4131): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4131): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4131): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 4131): nl80211: Survey data missing
D/wpa_supplicant( 4131): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 10 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 11 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 12 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 13 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4131): wlan0: BSS: Add new id 14 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 15 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4131): wlan0: BSS: Add new id 16 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB',
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Add new id 17 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4131): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 4131): wlan0: New scan results available
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): WPS: AP c0:ff:d4:d3:aa:4a type 0 added,
,D/wpa_supplicant( 4131): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4131): WPS: AP 44:e9:dd:10:c0:ab type 0 added
,D/wpa_supplicant( 4131): WPS: AP 64:7c:34:12:7f:81 type 0 added,
,D/wpa_supplicant( 4131): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4131): WPS: AP 44:e9:dd:10:c0:ac type 0 added,
D/wpa_supplicant( 4131): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
,D/wpa_supplicant( 4131): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 4131): WPS: AP[2] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4131): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
,D/wpa_supplicant( 4131): WPS: AP[4] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 4131): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4131): wlan0: Selecting BSS from priority group 1,
D/wpa_supplicant( 4131): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps,
,D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 4131): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 4131): wlan0:    skip - blacklisted (count=1 limit=0),
,D/wpa_supplicant( 4131): wlan0: 2: 44:e9:dd:10:c0:ab ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-71 wps,
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 4131): wlan0: 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4131): wlan0: 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80 wps
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4131): wlan0: 5: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-87 wps
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 4131): wlan0: 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86,
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 4131): wlan0: 7: 44:e9:dd:10:c0:ac ssid='FunBox2-C0AB' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-93 wps
,D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4131): wlan0: 8: 44:e9:dd:10:c0:ad ssid='Darmowe_Orange_WiFi' wpa_ie_len=0 rsn_ie_len=0 caps=0x101 level=-83,
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 4131): wlan0: No APs found - clear blacklist and try again,
D/wpa_supplicant( 4131): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 4131): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4131): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 4131): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4131): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 4131): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4131): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
,D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4131): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4131): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb71855a8  current_ssid=0x0
D/wpa_supplicant( 4131): scard is not null..
D/wpa_supplicant( 4131): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4131): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4131): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
,D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4131): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4131): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4131): wlan0: Cancelling scan request
D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 4131): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 4131): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4131): RSN: PMKSA cache search - network_ctx=0xb71855a8 try_opportunistic=0
D/wpa_supplicant( 4131): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4131): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4131): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 44:e9:dd:10:c0:ab]
,D/wpa_supplicant( 4131): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4131): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4131): wlan0: WPA: using PTK CCMP,
D/wpa_supplicant( 4131): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4131): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 4131): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4131): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4131): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4131): wlan0: State: SCANNING -> ASSOCIATING
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 38:f8:89:11:e9:11]
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4131): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4131): nl80211: Unsubscribe mgmt frames handle 0xb7184590 (mode change),
D/wpa_supplicant( 4131): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0d
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590,
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4131): nl80211: Register frame type=0xd0 nl_handle=0xb7184590
D/wpa_supplicant( 4131): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4131): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4131):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131):   * freq=2412
D/wpa_supplicant( 4131):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4131):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131):   * Auth Type 0,
D/wpa_supplicant( 4131):   * WPA Versions 0x2
D/wpa_supplicant( 4131): nl80211: Connect request send successfully
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=0,
,D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4131): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 64:7c:34:12:7f:81]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 a0:c5:62:7a:49:97]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 06:7c:34:12:7f:81]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 44:e9:dd:10:c0:ac]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  960): handleMessage: E msg.what=147461,
,D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4131): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 4131): nl80211: Event message available
D/wpa_supplicant( 4131): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4131): nl80211: Connect event
D/wpa_supplicant( 4131): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4131): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4131): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4131): wlan0: Association info event
D/wpa_supplicant( 4131): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4131): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4131): wlan0: freq=2412 MHz
D/wpa_supplicant( 4131): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4131): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4131): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4131): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): scard is not null..
D/wpa_supplicant( 4131): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4131): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4131): TDLS: Remove peers on association
D/wpa_supplicant( 4131): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4131): EAPOL: enable timer tick
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4131): wlan0: Cancelling scan request
,D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4131): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc ...
D/wpa_supplicant( 4131): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4131): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4131): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4131): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4131): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4131):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4131):   key_nonce - hexdump(len=32): 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc f8 bc b8 d4 46 38 f6 60 e2 6d ad ee 3a 10 50 b4 82
D/wpa_supplicant( 4131):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc ...
D/wpa_supplicant( 4131): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4131): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4131): Get randomness: len=32 entropy=10
,D/wpa_supplicant( 4131): WPA: Renewed SNonce - hexdump(len=32): ef 53 92 39 a8 9a 69 14 70 58 41 ad fd 74 d3 04 60 29 36 43 eb 91 49 ad 2e 9e 3d c9 15 52 5d 72
D/wpa_supplicant( 4131): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): WPA: Nonce1 - hexdump(len=32): ef 53 92 39 a8 9a 69 14 70 58 41 ad fd 74 d3 04 60 29 36 43 eb 91 49 ad 2e 9e 3d c9 15 52 5d 72
D/wpa_supplicant( 4131): WPA: Nonce2 - hexdump(len=32): 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc f8 bc b8 d4 46 38 f6 60 e2 6d ad ee 3a 10 50 b4 82
D/wpa_supplicant( 4131): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4131): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4131): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4131): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4131): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4131): WPA: Derived Key MIC - hexdump(len=16): 18 32 50 1c c9 a3 23 3b f2 4e 63 38 de eb 7f a9
,D/wpa_supplicant( 4131): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 ef 53 92 39 a8 9a 69 14 70 58 41 ad fd 74 d3 ...
,W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 4131): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc ...
D/wpa_supplicant( 4131): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4131): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4131): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4131): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4131):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4131):   key_nonce - hexdump(len=32): 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc f8 bc b8 d4 46 38 f6 60 e2 6d ad ee 3a 10 50 b4 82
D/wpa_supplicant( 4131):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_rsc - hexdump(len=8): ef 0e 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4131):   key_mic - hexdump(len=16): 2e 6b e1 bc a1 25 27 a9 b1 48 0f 0a 11 70 62 83
D/wpa_supplicant( 4131): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 84 95 8e d6 b9 54 f8 20 46 55 2c b6 5f 92 cc ...
D/wpa_supplicant( 4131): RSN: encrypted key data - hexdump(len=56): 67 eb fc 18 1a 4d 84 3e 40 99 4c 85 54 19 39 41 4f 3b b9 af 13 5d 23 f7 0e f8 90 74 8e 5e 8d 93 ...
D/wpa_supplicant( 4131): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4131): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4131): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4131): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 4131): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4131): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4131): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4131): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4131): WPA: Derived Key MIC - hexdump(len=16): bf f6 69 d8 8f 63 69 07 19 a2 56 a5 07 86 41 84
D/wpa_supplicant( 4131): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4131): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7184c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4131):    addr=c0:ff:d4:d3:aa:48
,D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4131): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4131): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4131): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 4131): WPA: RSC - hexdump(len=6): ef 0e 00 00 00 00
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f6903a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4131):    broadcast key
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 4131): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4131): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4131): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4131): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4131): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4131): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4131): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4131): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4131): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4131): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4131): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4131): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4131): EAPOL authentication completed successfully
D/wpa_supplicant( 4131): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4131): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4131): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  960): handleMessage: X
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): Network connection established
,D/WifiNative-wlan0(  960): doString: STATUS
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4131): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  960): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@45180550 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  960): handleMessage: E msg.what=147462
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  960): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@43c694a0 target=com.android.internal.util.StateMachine$SmHandler }
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
,D/WifiStateMachine(  960): ObtainingIpState{ when=-36ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-23ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 4913): start selecting data
,D/SIMObserver( 4913): simInfo1
I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3589): begin check event
,I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=6557 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6557): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  960): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  960): handleMessage: X
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4511a8c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4511a8c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-7ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/DownloadManager( 6557): DownloadService onCreate
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
I/DownloadManager( 6557): in removeSpuriousFiles
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4131): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4131): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4131): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4131): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4131): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4131): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): DHCP successful
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
,D/WifiStateMachine(  960): handleMessage: X
,I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6584 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
E/Parcel  (  612): Reading a NULL string not supported here.
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
,D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@431338e0 on behalf of 6557
,D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState enter
,D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
V/DownloadManager( 6557): DownloadService onStartCommand
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  960): handleMessage: X
,I/DownloadManager( 6557): in trimDatabase
,V/DownloadManager( 6557): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43136c88 on behalf of 6557
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43137498 on behalf of 6557
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
,D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/HyLog   ( 6584): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6584): I : /data/font/config/dfactpre.dat, No such file or directory (2)
E/Parcel  (  612): Reading a NULL string not supported here.
,D/HyLog   ( 6584): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
,E/Parcel  (  612): Reading a NULL string not supported here.
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/DownloadManager( 6557): DownloadService onDestroy
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
I/ActivityManager(  960): Killing 4209:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,V/        (  264): RouteController
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 6584): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGEmail ( 6584): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/QCNEA   (  612): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  612): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  612): |CAC| updateNetCfgInfo
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC|                   Netconfig               
V/QCNEA   (  612): |CAC| *********************************************
V/QCNEA   (  612): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  612): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  612): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  612): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  612): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  612): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  612): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  612): |CAC| net type = 1
,V/QCNEA   (  612): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  612): |CAC| Received ssid= NG700
V/QCNEA   (  612): |CAC| 	ssid           =NG700
V/QCNEA   (  612): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  612): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  612): |CAC| *********************************************
D/QCNEA   (  612): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  612): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  612): |CAC| dispatchNetCfg: updating:0xb8e9f8dc
D/QCNEA   (  612): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/DhcpStateMachine(  960): DHCP request on wlan0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,W/BaseRuntimeLoader( 6584): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6584): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6584): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6584): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6584): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/linker  ( 6584): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 6584): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6584): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6584): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6584): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,I/ActivityManager(  960): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=6625 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/HtmlEditor( 6584): register_HtmlEditor, Success
D/HtmlEditor( 6584): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6584): register_HtmlEditorTimer, Success
D/HtmlEditor( 6584): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6584): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6584): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6584): register_HtmlEditorFont, Success
D/HtmlEditor( 6584): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6584): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6584): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6584): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6584): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6584): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 6584): JNI_OnLoad Success
I/HubEmail( 6584): JNI_OnLoad()
I/HubEmail( 6584): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6584): registerNatives()
I/HubEmail( 6584): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6584): registerNativeMethods()
I/HubEmail( 6584): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6584): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 6625): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6625): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6625): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Killing 4556:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,I/ConversationSkinProvider( 6625): skin provider oncreate
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,E/[MMS]   ( 6625): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 6625): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6625): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6625): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6625): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
,D/[MMS]   ( 6625): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 6625): MmsSettings: Matching Xml Data file name = 2131034168
,D/[MMS]   ( 6625): MmsSettings: [LGE]parseDTMF() file doesn't exist
,D/[MMS]   ( 6625): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 6625): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_concat = [5]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   auto_retr = [1]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 6625): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 6625): MmsSettings: [LGE]   recv_adv = [1]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 6625): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_slide_num = [10]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 6625): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_recipient_length = [64]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 6625): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_dr_invisible = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   custom_extract_ui = [1]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   hide_sync_header_update = [1]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 6625): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   kr_kt_feature_set = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_led_button_blink = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   wificalling_feature_set = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 6625): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   latin_america_fdn_check = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 6625): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 6625): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 6625): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 6625): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 6625): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 6625): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  275): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  275): qmi_init:  Created client handle b72c2b28
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
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
E/Diag_Lib(  275): qmi_init:  Created client handle b72c2a08
,E/Diag_Lib(  275): qmi_client [275] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  275): qmi_client [275] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  275): Setting the api flag to : 1
,E/Diag_Lib(  275): qmi_client [275] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  275): qmi_client [275] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  275):  API Flag .............. 1 
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
E/Diag_Lib(  275): Sending signal ...... to read cmd data 
E/Diag_Lib(  275): qmi error code.........:0
E/Diag_Lib(  275): qmi sys error code.........:0
D/DRM_Adap(  275): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  275): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 6625): isDrmV1 =true
,V/DrmWrapper( 6625): isDrmV2 =false
,V/MmsConfig( 6625): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 6625): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 6625): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 6625): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 6625): Contact init()_Create new insatnce
,I/MessagingNotification( 6625): registerLEDObserver
,I/MessagingNotification( 6625): registerLEDObserver REGISTER
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/MmsConfig( 6625): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/CountryDetector(  960): The first listener is added
,D/LocationManagerService(  960): getProviders()=[passive, gps]
,D/LocationManagerService(  960): request 451e98a0 passive Request[POWER_NONE passive fastest=0] from android(1000)
I/LOG_TAG ( 6625): registerContactDBChangeObserver
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
I/LgeMiscReceiver( 6625): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 6625): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 6625): networkInfo.isConnected() = false
E/ActivityThread( 6625): Failed to find provider info for com.lge.ims.provider.uc
,V/LGRssiData( 6625): [loadRssi] File not exist 
,V/LGRssiData( 6625): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6625): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6656 uid=10052 gids={50052, 3003}
I/ActivityManager(  960): Killing 4664:com.lge.task/u0a43 (adj 15): empty #17
,V/TelephonyAutoProfiling( 6625): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6625): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6625): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/HyLog   ( 6656): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6656): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6656): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 6656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/LGRssiData( 6656): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 6656): onReceive CONNECTIVITY_CHANGE networkType=1
,V/LGRssiData( 6656): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6656): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 6656): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6656): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6656): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6656): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6656): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6656): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6656): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6671 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  960): Killing 4631:com.android.calendar/u0a15 (adj 15): empty #17
,E/PhoneMonitor( 6656): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6656): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,I/CheckinService( 1943): Checking schedule, now: 1452518571396 next: 1452517057144
,I/CheckinService( 1943): active receiver: enabled
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6671): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6671): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/CheckinService( 1943): Preparing to send checkin request
,I/EventLogService( 1943): Accumulating logs since 1452518458875
,D/HyLog   ( 6671): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 4131): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4131): EAPOL: disable timer tick
,D/dalvikvm(  960): GC_EXPLICIT freed 2886K, 46% free 30655K/55956K, paused 6ms+13ms, total 189ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6689 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 6689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6689): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  960): Killing 4601:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6701 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/HyLog   ( 6701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6701): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/LGDMSGCM( 6701): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6727 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  960): Killing 4961:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6727): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6727): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6727): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6727): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,I/Wireless_Storage( 6727): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6727): intf.getDisplayName() = lo
I/Wireless_Storage( 6727): intf.getDisplayName() = sit0
I/Wireless_Storage( 6727): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6727): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6727): intf.getDisplayName() = wlan0
D/NFS     ( 6727): interface name:wlan0 name:wlan0
D/NFS     ( 6727): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6727): interface name:wlan0 name:wlan0
,D/NFS     ( 6727): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 6727): CONNECT : WIFI_CONNECT
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6740 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4928:com.android.contacts/u0a21 (adj 15): empty #17
V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6740): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 30ms
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x43978e60: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 25ms
,W/GAV2    ( 6740): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 24ms
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6757 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6757): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6757): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6757): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6757): install
,I/MultiDex( 6757): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6757): loading existing secondary dex files
,I/MultiDex( 6757): load found 3 secondary dex files
,I/MultiDex( 6757): install done
,D/dalvikvm( 6757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6757): VFY: unable to resolve instance field 61
,D/dalvikvm( 6757): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6757): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f3d08
D/dalvikvm( 6757): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f3d08
,D/dalvikvm( 6757): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f3d08, skipping init
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f3d08
D/dalvikvm( 6757): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f3d08
,V/JNIHelp ( 6757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430f3d08
D/dalvikvm( 6757): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430f3d08
D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430f3d08
,D/dalvikvm( 6757): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430f3d08
,V/WebViewChromium( 6740): Binding Chromium to the main looper Looper (main, tid 1) {430f84a0}
,I/chromium( 6740): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6740): Initializing chromium process, renderers=0
,W/chromium( 6740): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6740): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6740): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6740): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6740): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6740): Remote Branch: 
I/Adreno-EGL( 6740): Local Patches: 
I/Adreno-EGL( 6740): Reconstruct Branch: 
,I/ProviderInstaller( 6757): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 6757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6757): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6757): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6757): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6757): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6757): VFY: replacing opcode 0x6e at 0x0201
,I/NSApplication( 6740): Starting up...
,I/ActivityManager(  960): Killing 4943:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  960): handleMessage: X
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/WVCdm   (  271): Instantiating CDM.
I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2f000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2f000
D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
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
,D/QRemote ( 6512): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6512): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=3519947826
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/QRemote ( 6512): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6512): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/QRemote ( 6512): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6512): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6473): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6473): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6512): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6512): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6512): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6512): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/AuthorizationBluetoothService( 1546): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4737): callingUid 10006, callindPid: 4737
,E/MDM     ( 1422): [74] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1943): Restart initialization of location
,D/dalvikvm( 6757): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x432b3038
,D/dalvikvm( 6757): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x432b3038
,D/dalvikvm( 6757): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x432b3038, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 6757): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/GCM     ( 1546): Connected
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1546): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6757): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
,D/dalvikvm( 6822): DexOpt: load 5ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 6757): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6757): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 119ms
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=150355059
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 4913): start selecting data
,D/SIMObserver( 4913): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3589): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3589): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3589): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3589): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3589): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6557): DownloadService onCreate
,D/eas_req ( 6584): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 6625): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 6625): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 6625): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/Settings( 6584): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 6557): in removeSpuriousFiles
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@4313d3d8 on behalf of 6557
,D/MobileConnectivityChangeReceiver( 6656): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 6557): in trimDatabase
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@4313ed90 on behalf of 6557
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 6557): DownloadService onStartCommand
V/DownloadManager( 6557): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMSGCM( 6701): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43140f80 on behalf of 6557
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 6727): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6727): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/CheckinRequestBuilder( 1943): Classify the device as Phone.
V/DownloadManager( 6557): DownloadService onDestroy
,E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1943): SSL shutdown failed: ssl=0x633c7418: I/O error during system call, Connection timed out
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  960): MasterInitialState.processMessage what=3
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/LicenseContentProvider( 4913): start selecting data
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/SIMObserver( 4913): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
,I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6557): DownloadService onCreate
I/DownloadManager( 6557): in removeSpuriousFiles
D/EAS     ( 6584): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43145108 on behalf of 6557
,I/DownloadManager( 6557): in trimDatabase
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6557): DownloadService onStartCommand
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43146f78 on behalf of 6557
,V/DownloadManager( 6557): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 6625): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 6625): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 6625): networkInfo.isConnected() = true
,D/PhoneState( 6625): setPdpRejectCasuse : false
W/Settings( 6584): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@43148cb0 on behalf of 6557
,D/MobileConnectivityChangeReceiver( 6656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6656): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6557): DownloadService onDestroy
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6701): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 6727): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6727): CONNECT : WIFI_CONNECT
,W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinTask( 1943): Sending checkin request (11587 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3589): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
,D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
,D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3589): isOpenOperator : true
,D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 4913): start selecting data
,D/SIMObserver( 4913): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3589): begin check event
,I/AppUp4:CustModeStarterReceiver( 3589): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6557): DownloadService onCreate
,D/EAS     ( 6584): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 6625): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 6625): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 6625): networkInfo.isConnected() = true
,D/PhoneState( 6625): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6656): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2791): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6701): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6727): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6727): CONNECT : WIFI_CONNECT
,W/Settings( 6584): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/DownloadManager( 6557): in removeSpuriousFiles
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@4314ce38 on behalf of 6557
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6557): in trimDatabase
,V/DownloadManager( 6557): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@4314df08 on behalf of 6557
,I/LGDMClient( 2791): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6557): DownloadService onStartCommand
V/DownloadManager( 6557): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6557): created cursor android.database.sqlite.SQLiteCursor@431509e0 on behalf of 6557
E/LGDMClient( 2791): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2791): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2791): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2791): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 6557): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/dalvikvm(  960): GC_EXPLICIT freed 1683K, 46% free 30615K/55956K, paused 4ms+10ms, total 153ms
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x43c97ed0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1943): awaiting user notification for token
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,I/CheckinTask( 1943): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1943): Checking schedule, now: 1452518576306 next: 1453095972302
,I/CheckinService( 1943): active receiver: disabled
,I/CheckinService( 1943): Checking schedule, now: 1452518576353 next: 1453095972302
,I/CheckinService( 1943): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1943): GC_CONCURRENT freed 2010K, 22% free 19466K/24832K, paused 3ms+5ms, total 75ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 6740): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  960): Killing 6473:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  960): Killing 4725:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518580055, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518580056, nextTick: 59975, mDrawingTime: 1
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6946 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  960): Handling package changes for user 0
,E/SlideAside( 3505): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3505): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6946): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
W/ActivityManager(  960): getAssistContextExtras failed: no resumed activity
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel   ( 6946): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6946): MmsConfig.loadMmsSettings
,I/Babel   ( 6946): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6946): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6946): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6946): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6946): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6946): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6946): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6946): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6946): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6946): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6946): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6946): MmsConfig.loadFromResources
,E/Babel   ( 6946): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6946): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 6946): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6946): [loadRssi] File not exist 
V/LGRssiData( 6946): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6946): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 6946): [getMatchedProfile] selected file : /cust/config/featureset.xml
,D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.gms
V/TelephonyAutoProfiling( 6946): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6946): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4  ( 3589): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3589): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3589): onReceive
D/AppUp4:CustFacade( 3589): Context : android.app.ReceiverRestrictedContext@4310c270
D/AppUp4:CustFacade( 3589): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3589): isOpenOperator : true
D/AppUp4:CustFacade( 3589): isPhone : true
,I/LicenseContentProvider( 4913): start selecting data
,D/SIMObserver( 4913): simInfo1
,I/AppUp4:EulaManager( 3589): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3589): begin check event
D/AppUp4:Utils( 3589): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3589): Event For Nothing, skip.
,D/LocationProviderProxy(  960): applying state to connected service
,D/LocationProviderProxy(  960): applying state to connected service
I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6996 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6996): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6996): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6996): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6996): BUILD Country: EU
,I/SystemConfig( 6996): BUILD Operator: OPEN
I/ActivityManager(  960): Killing 6512:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7010 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/SystemConfig( 6996): systemFeature RCS result false
,D/SystemConfig( 6996): refreshRcsSupport() :false
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  960): Killing 6557:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 7010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7010): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  960): Killing 6584:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2600): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7028 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7028): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 7028): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7028): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7028): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7028): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7028): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7028): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7028): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7028): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7028): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7028): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2600): UpdateCorporaTask done [took 311 ms] updated apps [took 311 ms] 
,W/Settings( 7028): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7028): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7028): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7028): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 7028): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7028): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7028): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7028): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 7028): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 7028): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x001a
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7065 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 7028): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 7028): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/HyLog   ( 7065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7065): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7065): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 7028): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 7028): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7028): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  960): Killing 6625:com.android.mms/u0a35 (adj 15): empty #17
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,I/LocationManagerService(  960): remove 451e98a0
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  960): No listener is left
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7065): DownloadService onCreate
,I/DownloadManager( 7065): in removeSpuriousFiles
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@43137910 on behalf of 7028
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@43139888 on behalf of 7065
,V/DownloadManager( 7065): DownloadService onStartCommand
,V/DownloadManager( 7065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 7065): in trimDatabase
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@4313c0c8 on behalf of 7065
,V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@4313d248 on behalf of 7065
,D/Finsky  ( 7028): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 7065): DownloadService onDestroy
,D/Finsky  ( 7028): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7028): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7028): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7028): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7028): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7028): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1546): GC_EXPLICIT freed 1309K, 28% free 17984K/24832K, paused 3ms+10ms, total 50ms
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-13ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  960): Checking http://216.58.209.46/generate_204
,D/dalvikvm(  960): GC_EXPLICIT freed 1881K, 46% free 30770K/55956K, paused 8ms+20ms, total 199ms
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,W/Finsky  ( 7028): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 7028): Total arena pages for JIT: 11
,I/dalvikvm( 7028): Total arena pages for JIT: 12
,I/dalvikvm( 7028): Total arena pages for JIT: 13
,I/dalvikvm( 7028): Total arena pages for JIT: 14
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7028): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7028): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7028): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7028): [1] DailyHygiene.reschedule: Scheduling new run in 84 minutes (failures=3)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6946): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  960): Killing 6656:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{434c0a00 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518589285640263; DSPS: 55411929; Offset: 1452516898247767949
,D/Finsky  ( 7028): [471] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518609287330771; DSPS: 56067344; Offset: 1452516898247779990
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518629288701307; DSPS: 56722750; Offset: 1452516898247746718
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518640048, nextTick: 59979, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518640054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518649289584235; DSPS: 57378138; Offset: 1452516898247775153
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518669290032465; DSPS: 58033513; Offset: 1452516898247765620
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518689290517433; DSPS: 58688889; Offset: 1452516898247762307
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518700035, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518700051, nextTick: 59981, mDrawingTime: 0
,W/ProcessCpuTracker(  960): Skipping unknown process pid 7245
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518709291450087; DSPS: 59344280; Offset: 1452516898247748916
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,I/ProcessStatsService(  960): Prepared write state in 19ms
,I/ProcessStatsService(  960): Prepared write state in 26ms
,D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  960): Pruning old procstats: /data/system/procstats/state-2016-01-10-15-45-00.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@43144d98 on behalf of 1943
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@43148c20 on behalf of 1943
,V/DownloadManager( 7065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 7065): created cursor android.database.sqlite.SQLiteCursor@4314c3c0 on behalf of 1943
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518729292982526; DSPS: 59999690; Offset: 1452516898247755476
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518749293410757; DSPS: 60655064; Offset: 1452516898247756461
,D/wpa_supplicant( 4131): wlan0: BSS: Remove id 10 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 11 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 12 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 13 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 14 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 15 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 16 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4131): wlan0: BSS: Remove id 17 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4131): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 44:e9:dd:10:c0:ab]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 38:f8:89:11:e9:11]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 64:7c:34:12:7f:81]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 a0:c5:62:7a:49:97],
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 06:7c:34:12:7f:81]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 44:e9:dd:10:c0:ad]
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518760031, nextTick: 59998, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518760039, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518769293885131; DSPS: 61310439; Offset: 1452516898247773071
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518789294788893; DSPS: 61965829; Offset: 1452516898247761306
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1452518809295211329; DSPS: 62621203; Offset: 1452516898247756496
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518820058, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452518820059, nextTick: 59972, mDrawingTime: 1
,TIME-OUT KILL (timeout was 1800000ms)
```
