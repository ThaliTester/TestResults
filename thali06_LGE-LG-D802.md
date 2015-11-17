#### Test 503880196ac79ce_thali06_LGE-LG-D802 Logs


```--------- beginning of /dev/log/main
11-17 18:30:49.992  1944  1944 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
11-17 18:30:50.002  1944  1944 I ConfigFetchService: launchTask
11-17 18:30:50.002  1944  1944 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:30:50.012  1944  3952 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UbvT5-_R7uQtkUQg-bW-cl25aIb3BCw9MrV4H11HWe0IO2yNa4NcM83_HjECm87fLOJnaetgtu2GrYKrEhojsuCy4OFy-03uigdMgPprWaJHNCxQBTtT8pnmN9YO7AVVmsTQVRqr5wyue1RVlYRNO5c3Q8pg_s8q_UpnuNS6B3kB8Pr1j4Gndze0LVYnY2sm1sH2Yp
11-17 18:30:50.012  1944  1944 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:50.012  1944  1944 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:30:50.012  1944  1944 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
11-17 18:30:50.022  1944  1944 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
11-17 18:30:50.022  1944  3952 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-17 18:30:50.022  1944  1944 D Vision  : Failed to find package metadata for com.example.hello
11-17 18:30:50.022  1944  1944 D Vision  : No vision deps
11-17 18:30:50.042  1944  3954 I PeopleContactsSync: CP2 sync disabled
11-17 18:30:50.042  1944  3954 I dalvikvm: Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
11-17 18:30:50.042  1944  3954 W dalvikvm: VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
11-17 18:30:50.042  1944  3954 D dalvikvm: VFY: replacing opcode 0x6e at 0x000e
11-17 18:30:50.052  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.052  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.082  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.092  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.092  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.102  1944  3957 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:50.112  1944  3952 E DataScheduler: isDataSchedulerEnabled():false
11-17 18:30:50.112   264  3964 D libc    : _dns_getaddrinfo: iptype =0
11-17 18:30:50.112   264  3964 D libc    : _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
11-17 18:30:50.112  1944  3952 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
11-17 18:30:50.112  1944  1944 I ConfigFetchService: fetch service done; releasing wakelock
11-17 18:30:50.112  1944  1944 I ConfigFetchService: stopping self
11-17 18:30:50.152  3918  3918 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
11-17 18:30:50.152   960  1518 I ActivityManager: Killing 3438:com.android.providers.calendar/u0a16 (adj 15): empty #17
11-17 18:30:50.162   960  1516 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 1 tasks}
11-17 18:30:50.162   960  1516 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2}
11-17 18:30:50.262   287   502 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
11-17 18:30:50.282  1944  3957 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:50.282  1944  3957 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:30:50.322  1944  1948 D dalvikvm: GC_CONCURRENT freed 1573K, 26% free 18461K/24832K, paused 3ms+5ms, total 46ms
11-17 18:30:50.542   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:30:50.562  1944  2694 I Icing   : Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
11-17 18:30:50.642  1944  2694 D Icing   : Loaded CLD2 Version V2.0 - 20141016
11-17 18:30:50.692  1944  2694 I Icing   : Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
11-17 18:30:50.782   960   992 I ActivityManager: Waited long enough for: ServiceRecord{432c0940 u0 com.lge.slideaside/.MainService}
11-17 18:30:51.132  1156  1380 E BatteryObserver: usb Uevent not necessary.
11-17 18:30:51.132   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:30:51.152   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:30:51.172   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:51.812  1156  1380 E BatteryObserver: usb Uevent not necessary.
11-17 18:30:51.812   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:30:51.832   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:30:51.842   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:30:51.892  3974  3974 D AndroidRuntime: 
11-17 18:30:51.892  3974  3974 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:51.892  3974  3974 D AndroidRuntime: CheckJNI is OFF
11-17 18:30:51.902  3974  3974 D dalvikvm: Trying to load lib libjavacore.so 0x0
11-17 18:30:51.902  3974  3974 D dalvikvm: Added shared lib libjavacore.so 0x0
11-17 18:30:51.912  3974  3974 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:30:51.912  3974  3974 D dalvikvm: Added shared lib libnativehelper.so 0x0
11-17 18:30:51.912  3974  3974 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
11-17 18:30:51.942  3974  3974 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
11-17 18:30:52.042  3974  3974 E memtrack: Couldn't load memtrack module (No such file or directory)
11-17 18:30:52.042  3974  3974 E android.os.Debug: failed to load memtrack module: -2
11-17 18:30:52.102  3974  3974 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:30:52.112   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:30:52.112   960   971 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3974
11-17 18:30:52.112   960   971 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 2 tasks}
11-17 18:30:52.112   267  1000 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
11-17 18:30:52.112   960   971 V ActivityManager: Moving to PAUSING: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2}
11-17 18:30:52.192   960   971 D dalvikvm: GC_FOR_ALLOC freed 481K, 13% free 27478K/31228K, paused 65ms, total 65ms
11-17 18:30:52.192   960   971 I dalvikvm-heap: Grow heap (frag case) to 29.830MB for 856096-byte allocation
11-17 18:30:52.262   960   971 D dalvikvm: GC_FOR_ALLOC freed 42K, 12% free 28277K/32068K, paused 68ms, total 68ms
11-17 18:30:52.262   960   971 I dalvikvm-heap: Grow heap (frag case) to 30.610MB for 856096-byte allocation
11-17 18:30:52.272   960   971 D ActivityManager: resumeTopActivityLocked: Pausing null
11-17 18:30:52.272   960   971 V ActivityManager: resumeTopActivityLocked: Skip resume: need to start pausing
11-17 18:30:52.272   960   971 D ActivityManager: setFocusedStack: mFocusedStack=ActivityStack{433103f8 stackId=1, 2 tasks}
11-17 18:30:52.272   960   971 D ActivityManager: allPausedActivitiesComplete: r=ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2} state=PAUSING
11-17 18:30:52.282  3974  3974 D AndroidRuntime: Shutting down VM
11-17 18:30:52.282  3974  3979 D dalvikvm: GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
11-17 18:30:52.282  2514  2514 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
11-17 18:30:52.282  2514  2514 D UsbSettings: [AUTORUN] onPause() : mActiveCurrentFunction = boot
11-17 18:30:52.282   960   992 I ActivityManager: startService SlideAside
11-17 18:30:52.282   960   992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
11-17 18:30:52.282   960  1520 V ActivityManager: Moving to PAUSED: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2} (pause complete)
11-17 18:30:52.282   960  1520 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 2 tasks}
11-17 18:30:52.282   960  1520 D ActivityManager: resumeTopActivityLocked: Restarting ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3}
11-17 18:30:52.292   960  1520 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3991 uid=10311 gids={50311, 3003, 3001, 3002}
11-17 18:30:52.302  3512  3512 I SlideAside: [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
11-17 18:30:52.302  3512  3512 I SlideAside: [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
11-17 18:30:52.312  3512  3512 D SlideAside: [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
11-17 18:30:52.312   960  1488 V ActivityManager: Moving to RESUMED: ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3} (starting new instance)
11-17 18:30:52.322  3991  3991 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:30:52.322  3991  3991 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
11-17 18:30:52.322  3991  3991 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:30:52.342  3991  3991 V WebViewChromium: Binding Chromium to the background looper Looper (main, tid 1) {42891ae8}
11-17 18:30:52.342  3991  3991 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:52.342  3991  3991 I BrowserProcessMain: Initializing chromium process, renderers=0
11-17 18:30:52.352  3991  4009 W chromium: [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
11-17 18:30:52.352  3991  3991 I Adreno-EGL: <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
11-17 18:30:52.352  3991  3991 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.00.02
11-17 18:30:52.352  3991  3991 I Adreno-EGL: Build Date: 01/20/14 Mon
11-17 18:30:52.352  3991  3991 I Adreno-EGL: Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
11-17 18:30:52.352  3991  3991 I Adreno-EGL: Remote Branch: 
11-17 18:30:52.352  3991  3991 I Adreno-EGL: Local Patches: 
11-17 18:30:52.352  3991  3991 I Adreno-EGL: Reconstruct Branch: 
11-17 18:30:52.362   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:30:52.392  3991  3991 I dalvikvm: Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
11-17 18:30:52.392  3991  3991 D dalvikvm: VFY: replacing opcode 0x6e at 0x0016
11-17 18:30:52.392  3991  3991 I dalvikvm: Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
11-17 18:30:52.392  3991  3991 D dalvikvm: VFY: replacing opcode 0x6e at 0x0008
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:30:52.392  3991  3991 I dalvikvm: Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
11-17 18:30:52.392  3991  3991 D dalvikvm: VFY: replacing opcode 0x6f at 0x001a
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
11-17 18:30:52.392  3991  3991 I dalvikvm: Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
11-17 18:30:52.392  3991  3991 D dalvikvm: VFY: replacing opcode 0x6e at 0x000d
11-17 18:30:52.392  3991  3991 I dalvikvm: Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
11-17 18:30:52.392  3991  3991 W dalvikvm: VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
11-17 18:30:52.392  3991  3991 D dalvikvm: VFY: replacing opcode 0x6e at 0x0000
11-17 18:30:52.392  3991  3991 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:30:52.412  3991  3991 D dalvikvm: Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,11-17 18:30:52.552  3991  3991 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:30:52.552  3991  4024 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
11-17 18:30:52.552  3991  4024 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
11-17 18:30:52.552  3991  4024 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,11-17 18:30:52.552  3991  4024 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,11-17 18:30:52.552  3991  3991 W AwContents: nativeOnDraw failed; clearing to background color.
,11-17 18:30:52.582   960   991 I ActivityManager: Displayed com.example.hello/.MainActivity: +303ms
,11-17 18:30:52.582  3991  3991 I ActivityManager: Timeline: Activity_idle id: android.os.BinderProxy@428931c0 time:43518
,11-17 18:30:52.712  3991  3991 I chromium: [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:30:52.722  3991  4010 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:30:52.762  3991  3991 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:30:52.812   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:52.832  3991  4027 D dalvikvm: Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428977b0
,11-17 18:30:52.842  3991  4027 D dalvikvm: Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428977b0
,11-17 18:30:52.842  3991  4027 D jxcore_app_log: JniHelper::setJavaVM(0x4175d838), pthread_self() = 1626641408
,11-17 18:30:52.842  3991  4027 D JX-Cordova: jxcore cordova android initializing
,11-17 18:30:52.962  3991  3991 W jxcore-log: Initializing JXcore engine
,11-17 18:30:52.962  3991  3991 W jxcore-log: JXcore engine is ready
,11-17 18:30:52.972  3991  3991 W jxcore-log: Starting JXcore engine
,11-17 18:30:52.972  1944  3063 I CheckinService: Done disabling old GoogleServicesFramework version
,11-17 18:30:53.032   960   991 I ActivityManager: Timeline: Activity_windows_visible id: ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3} time:43968
11-17 18:30:53.032   960   992 D ActivityManager: no-history finish of ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2}
11-17 18:30:53.032   960   992 V ActivityManager: Finishing activity token=Token{432cea60 ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,11-17 18:30:53.042  2514  2514 D UsbSettings: [AUTORUN] onStop()
11-17 18:30:53.042   960   992 V ActivityManager: Moving to FINISHING: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2 f}
11-17 18:30:53.042   960   992 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3}
11-17 18:30:53.042   960   992 V ActivityManager: Moving to STOPPING: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,11-17 18:30:53.062   960  1487 V ActivityManager: Moving to STOPPED: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,11-17 18:30:53.162   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:53.162  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:53.182   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:53.452  3991  3991 W jxcore-log: Platform android
11-17 18:30:53.452  3991  3991 W jxcore-log: 
,11-17 18:30:53.452  3991  3991 W jxcore-log: Process ARCH arm
11-17 18:30:53.452  3991  3991 W jxcore-log: 
,11-17 18:30:53.492  3991  3991 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:30:53.492  3991  3991 I jxcore-log: 
,11-17 18:30:53.492  3991  3991 W jxcore-log: JXcore engine is started
,11-17 18:30:53.512  3991  3991 I chromium: [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,11-17 18:30:53.532  3991  3991 I chromium: [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,11-17 18:30:53.582  3991  3991 E jxcore-log: >> LGE-LG-D802
11-17 18:30:53.582  3991  3991 E jxcore-log: 
11-17 18:30:53.582  3991  3991 I jxcore-log: Total memory 1943035904
11-17 18:30:53.582  3991  3991 I jxcore-log: 
11-17 18:30:53.582  3991  3991 I jxcore-log: Free memory 466677760
11-17 18:30:53.582  3991  3991 I jxcore-log: 
11-17 18:30:53.582  3991  3991 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:53.582  3991  3991 I jxcore-log: 
11-17 18:30:53.582  3991  3991 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:53.582  3991  3991 I jxcore-log: 
11-17 18:30:53.582  3991  3991 I jxcore-log: userPath [ 'www' ]
11-17 18:30:53.582  3991  3991 I jxcore-log: 
,11-17 18:30:53.582  3991  3991 I jxcore-log: Size 1080 1776
11-17 18:30:53.582  3991  3991 I jxcore-log: 
11-17 18:30:53.592  3991  3991 I jxcore-log: Screen Brightness 255
11-17 18:30:53.592  3991  3991 I jxcore-log: 
,11-17 18:30:53.592  3991  3991 E jxcore-log: Dummy Error Log.
11-17 18:30:53.592  3991  3991 E jxcore-log: 
,11-17 18:30:53.822   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:54.122  3991  3991 I jxcore-log: getBuffer is called!!!!
11-17 18:30:54.122  3991  3991 I jxcore-log: 
,11-17 18:30:54.182   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:54.182  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:54.192   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:54.262   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:54.552   960  1518 I ActivityManager: Killing 3404:com.android.calendar/u0a15 (adj 15): empty #17
,11-17 18:30:54.602   960  1505 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 2 tasks}
,11-17 18:30:54.602   960  1505 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3}
,11-17 18:30:54.612   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:54.752  3918  3937 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:54.872   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:54.922   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:55.142  1534  1534 I ConfigService: onDestroy
,11-17 18:30:55.202   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:55.202  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:55.212   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:55.542   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:55.552  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:55.552   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:55.572   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:56.642   960  1506 I ActivityManager: Killing 3349:com.google.android.music:main/u0a107 (adj 15): empty #17
,11-17 18:30:56.662   960  1487 F ActivityManager: Service ServiceRecord{43283830 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{430b9ce8 3349:com.google.android.music:main/u0a107} not same as in map: null
,11-17 18:30:56.672   960  1487 F ActivityManager: Service ServiceRecord{43269318 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{430b9ce8 3349:com.google.android.music:main/u0a107} not same as in map: null
,11-17 18:30:56.682   960  1487 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 2 tasks}
11-17 18:30:56.682   960  1487 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3}
,11-17 18:30:56.772   960  1116 V qcom_sensors_hal: hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,11-17 18:30:56.772   960  1116 D qcom_sensors_hal: hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
11-17 18:30:56.772   960  1116 V qcom_sensors_hal: hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
11-17 18:30:56.772   960  1116 V qcom_sensors_hal: hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,11-17 18:30:56.772   960  1116 V qcom_sensors_hal: hal_process_report_ind: X: -0.561600 Y: -0.369385 Z: 9.707352 
11-17 18:30:56.772   960   990 D qcom_sensors_hal: _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561600 .y:-0.369385 .z:9.707352
11-17 18:30:56.772   960   990 D qcom_sensors_hal: _hal_sensors_data_poll: cnt: 36
,11-17 18:30:56.772   960   990 D qcom_sensors_hal: hal_wait_for_response: timeout=0
,11-17 18:30:56.842   960  1116 V qcom_sensors_hal: hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,11-17 18:30:56.842   960  1116 D qcom_sensors_hal: hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
11-17 18:30:56.842   960  1116 V qcom_sensors_hal: hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
11-17 18:30:56.842   960  1116 V qcom_sensors_hal: hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
11-17 18:30:56.842   960  1116 V qcom_sensors_hal: hal_process_report_ind: X: -0.550629 Y: -0.387802 Z: 9.707260 
,11-17 18:30:56.842   960   990 D qcom_sensors_hal: _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.550629 .y:-0.387802 .z:9.707260
11-17 18:30:56.842   960   990 D qcom_sensors_hal: _hal_sensors_data_poll: cnt: 36
,11-17 18:30:56.842   960   990 D qcom_sensors_hal: hal_wait_for_response: timeout=0
,11-17 18:30:56.902   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:56.902  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:56.912   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:58.602   960   997 D BluetoothManagerService: Message: 20
,11-17 18:30:58.602   960   997 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431adef0:true
,11-17 18:30:58.602   960   970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:30:58.612   960   970 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:30:58.612   960   997 D BluetoothManagerService: Message: 2
,11-17 18:30:58.622   960  1129 D WifiService: New client listening to asynchronous messages
,11-17 18:30:58.632   960  1516 D WifiService: setWifiEnabled: false pid=3991, uid=10311
,11-17 18:30:58.632   960  1516 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:30:58.632  3991  3991 I jxcore-log: ****TEST TOOK:  5062  ms ****
11-17 18:30:58.632  3991  3991 I jxcore-log: 
,11-17 18:30:58.632  3991  3991 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:58.632  3991  3991 I jxcore-log: 
11-17 18:30:58.632   960  1516 I WifiService: setWifiEnabled startWifiDelaySendMsg true
,11-17 18:30:58.932  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:30:58.932   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:58.952   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:58.962   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:30:59.082  4070  4070 D AndroidRuntime: 
11-17 18:30:59.082  4070  4070 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:30:59.092  4070  4070 D AndroidRuntime: CheckJNI is OFF
,11-17 18:30:59.102  4070  4070 D dalvikvm: Trying to load lib libjavacore.so 0x0
,11-17 18:30:59.102  4070  4070 D dalvikvm: Added shared lib libjavacore.so 0x0
,11-17 18:30:59.102  4070  4070 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:30:59.102  4070  4070 D dalvikvm: Added shared lib libnativehelper.so 0x0
,11-17 18:30:59.102  4070  4070 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,11-17 18:30:59.132  4070  4070 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,11-17 18:30:59.252  4070  4070 E memtrack: Couldn't load memtrack module (No such file or directory)
,11-17 18:30:59.252  4070  4070 E android.os.Debug: failed to load memtrack module: -2
,11-17 18:30:59.312   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:59.312  4070  4070 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:30:59.342   960   992 I ActivityManager: Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,11-17 18:30:59.342   960   992 I ActivityManager: Killing 3991:com.example.hello/u0a311 (adj 0): stop com.example.hello
,11-17 18:30:59.342   960   992 W ActivityManager: Force removing ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,11-17 18:30:59.342   960   992 V ActivityManager: Moving to DESTROYED: ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,11-17 18:30:59.342   960   992 V ActivityManager: Moving to DESTROYED: ActivityRecord{430fd368 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,11-17 18:30:59.342   960   992 I MDM     :  removeProcessLocked app.persistent = false callerWillRestart = false
,11-17 18:30:59.352   960   992 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{433103f8 stackId=1, 1 tasks}
11-17 18:30:59.352   960   992 D ActivityManager: resumeTopActivityLocked: No more activities go home
,11-17 18:30:59.352   960   992 V ActivityManager: moveHomeStack:
,11-17 18:30:59.352   960   992 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:30:59.352   960  1138 I WindowState: WIN DEATH: Window{431fa848 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:59.352   960  1129 D WifiService: Client connection lost with reason: 4
,11-17 18:30:59.412   960  1001 W PackageSettings: Skipping PackageSetting{42d3d420 com.test.thalitest/10304} due to missing metadata
,11-17 18:30:59.442   960   992 V ActivityManager: Moving to RESUMED: ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1} (in existing)
,11-17 18:30:59.442   960   992 D ActivityManager: resumeTopActivityLocked: Resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:30:59.442   960   992 I ActivityManager: resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:30:59.442   960   992 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:30:59.442  2514  2514 D UsbSettings: [AUTORUN] onDestroy() : getDefaultFunction =boot
,11-17 18:30:59.442   960   992 V ActivityManager: Moving to DESTROYING: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
11-17 18:30:59.452  2514  2514 V UsbSettings: [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
11-17 18:30:59.452  2514  2514 V UsbSettings: [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,11-17 18:30:59.452  2514  2514 V UsbSettings: [AUTORUN] onDestroy() : sys.usb.state=boot,adb
11-17 18:30:59.452   960  1001 I ActivityManager: Force stopping com.example.hello appid=10311 user=0: pkg removed
11-17 18:30:59.452   960  1001 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
11-17 18:30:59.452   960  1001 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:30:59.452  1489  1489 I [LGHome]EVENT: [Launcher.java:4947:onStart()]onStart
,11-17 18:30:59.472  1142  1142 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,11-17 18:30:59.472  1489  1489 I [LGHome]EVENT: [Launcher.java:717:onResume()]onResume
,11-17 18:30:59.472   960  1115 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:30:59.482  3656  3656 D AppUp4:Utils: [getPackageName] uri : package:com.example.hello
,11-17 18:30:59.482  3512  3512 E SlideAside: [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
11-17 18:30:59.482  3512  3512 I SlideAside: [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
11-17 18:30:59.482  3656  3656 D AppUp4  : [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,11-17 18:30:59.482  3656  3656 I AppUp4  :  isExcludedPackage  packagename = com.example.hello
,11-17 18:30:59.482  2574  2574 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
11-17 18:30:59.482  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
11-17 18:30:59.482  2574  2574 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
11-17 18:30:59.482  2574  2574 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:30:59.482  2574  2574 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
11-17 18:30:59.482  2574  2574 W System.err: 	at android.os.Handler.handleCallback(Handler.java:733)
11-17 18:30:59.482  2574  2574 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:30:59.482  2574  2574 W System.err: 	at android.os.Looper.loop(Looper.java:136)
11-17 18:30:59.482  2574  2574 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5105)
11-17 18:30:59.482  2574  2574 W System.err: 	at java.lang.reflect.Method.invokeNative(Native Method)
11-17 18:30:59.482  2574  2574 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:515)
11-17 18:30:59.482  2574  2574 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
11-17 18:30:59.482  1489  1548 I [LGHome]Launcher.Model: [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
11-17 18:30:59.482  2574  2574 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,11-17 18:30:59.482  2574  2574 W System.err: 	at dalvik.system.NativeStart.main(Native Method)
,11-17 18:30:59.482  1449  1460 D PhoneApp: getIsInUseVoLTE : false
,11-17 18:30:59.492  1424  1716 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:30:59.492  1489  1489 I [LGHome]LGActivityUtil: [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,11-17 18:30:59.492  1489  1489 I [LGHome]EVENT: [Launcher.java:868:onResume()]onResume end
,11-17 18:30:59.492  3656  3656 D AppUp4  :  isExcludedPackage TRUE : com.example.hello
,11-17 18:30:59.502   960  1487 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.502   960  1487 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.502   960  1487 I PackageManager:   Scheme: "sms"
11-17 18:30:59.502   960  1487 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.512  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:30:59.512  1489  1489 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:30:59.512  1489  1489 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,11-17 18:30:59.542   960  1505 V ActivityManager: Moving to DESTROYED: ActivityRecord{430f0838 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,11-17 18:30:59.542   960  1520 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.542   960  1520 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.542   960  1520 I PackageManager:   Scheme: "smsto"
11-17 18:30:59.542   960  1520 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.552   960  1505 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:30:59.552   960  1505 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:30:59.562   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:59.562   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:30:59.572  3392  3392 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.example.hello
11-17 18:30:59.572   960   971 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.572   960   971 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.572   960   971 I PackageManager:   Scheme: "mms"
11-17 18:30:59.572   960   971 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.582  2586  2586 D dalvikvm: GC_EXPLICIT freed 3647K, 29% free 17873K/24832K, paused 37ms+2ms, total 124ms
,11-17 18:30:59.592   960  1518 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.592   960  1518 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.592   960  1518 I PackageManager:   Scheme: "mmsto"
11-17 18:30:59.592   960  1518 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.602   960   960 D dalvikvm: GC_EXPLICIT freed 1071K, 12% free 29171K/32792K, paused 2ms+9ms, total 146ms
,11-17 18:30:59.602   960  1001 D dalvikvm: WAIT_FOR_CONCURRENT_GC blocked 117ms
,11-17 18:30:59.622  1824  4106 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
11-17 18:30:59.622   960  1506 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.622   960  1506 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.622   960  1506 I PackageManager:   Scheme: "sms"
,11-17 18:30:59.622  3901  3901 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
11-17 18:30:59.622   960  1506 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.642   960   960 D administrator: Handling package changes for user 0
,11-17 18:30:59.642   960  1505 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.642   960  1505 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.642   960  1505 I PackageManager:   Scheme: "smsto"
11-17 18:30:59.642   960  1505 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.652  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,11-17 18:30:59.672  1142  1142 D GlobalAccess: optimizeTargetDrawableItems(), newSize: 20
,11-17 18:30:59.672  1142  1142 D GlowPadView: changeTargets() succeeded. size: 20
11-17 18:30:59.672  2514  2514 D PackageIntentReceiver: Not supported Hotkey customization function 
11-17 18:30:59.672   960  1138 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.672   960  1138 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.672   960  1138 I PackageManager:   Scheme: "mms"
,11-17 18:30:59.672  1142  1142 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,11-17 18:30:59.672  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
11-17 18:30:59.672   960  1138 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.682   960  1516 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:30:59.682   960  1516 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:30:59.682   960  1516 I PackageManager:   Scheme: "mmsto"
11-17 18:30:59.682   960  1516 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:30:59.692  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,11-17 18:30:59.692  2514  2514 D HideNavigationAppsReceiver: Receive package name : com.example.hello
,11-17 18:30:59.692   960  1487 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4107 uid=10090 gids={50090}
11-17 18:30:59.702  2514  2514 D HideNavigationAppsReceiver: Delete mPackageMame : com.example.hello
11-17 18:30:59.702  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
11-17 18:30:59.702  4107  4107 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:30:59.702  4107  4107 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:30:59.702  4107  4107 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:30:59.712  2586  4120 I IcingCorporaProvider: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:30:59.712  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,11-17 18:30:59.722  4107  4107 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
11-17 18:30:59.722   960  1516 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4121 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,11-17 18:30:59.732   960   960 I InteractionManagerConfigurator: updateIntentFilterConfig
,11-17 18:30:59.732   960   960 I InteractionManagerConfigurator: com.example.hello isn't inclued in dragdropPackageList
11-17 18:30:59.732   960   960 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:30:59.732   960   960 V BackupManagerService: removePackageParticipantsLocked: uid=10311 #1
11-17 18:30:59.742  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
11-17 18:30:59.742  1142  1168 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,11-17 18:30:59.742  1142  1168 D KeyguardModel: createShortcutInfo...
11-17 18:30:59.742  1142  1168 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,11-17 18:30:59.742  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.752  4121  4121 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:30:59.752  4121  4121 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:30:59.752  4121  4121 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:30:59.762  4121  4121 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,11-17 18:30:59.762  1489  1493 D dalvikvm: GC_CONCURRENT freed 5152K, 9% free 60922K/66276K, paused 1ms+3ms, total 23ms
,11-17 18:30:59.762  1489  1489 D dalvikvm: WAIT_FOR_CONCURRENT_GC blocked 21ms
,11-17 18:30:59.772  1142  1142 D dalvikvm: GC_FOR_ALLOC freed 6658K, 13% free 69280K/78808K, paused 24ms, total 24ms
11-17 18:30:59.772  1142  1168 D KeyguardModel: package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,11-17 18:30:59.772  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.782  1142  1168 D KeyguardModel: package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,11-17 18:30:59.782  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.782  1142  1168 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,11-17 18:30:59.782  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.792  1142  1168 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,11-17 18:30:59.792  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.792  1142  1168 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,11-17 18:30:59.792  1142  1168 D KeyguardModel: createShortcutInfo...
11-17 18:30:59.792  1142  1168 D KeyguardModel: package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,11-17 18:30:59.792  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.792   960  1001 D dalvikvm: GC_EXPLICIT freed 419K, 11% free 29211K/32792K, paused 2ms+14ms, total 187ms
,11-17 18:30:59.792  1142  1168 D KeyguardModel: package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,11-17 18:30:59.792  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.802  1142  1168 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,11-17 18:30:59.802  1142  1168 D KeyguardModel: createShortcutInfo...
,11-17 18:30:59.812  3732  3732 I dalvikvm: Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,11-17 18:30:59.812  3732  3732 W dalvikvm: VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,11-17 18:30:59.812  3732  3732 D dalvikvm: VFY: replacing opcode 0x6e at 0x0013
,11-17 18:30:59.832  1489  4136 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
11-17 18:30:59.832  1534  1534 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-17 18:30:59.832  1534  1534 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 18:30:59.832  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,11-17 18:30:59.842  1489  4136 E [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,11-17 18:30:59.842  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,11-17 18:30:59.842  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,11-17 18:30:59.842  4070  4070 D AndroidRuntime: Shutting down VM
,11-17 18:30:59.842  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
11-17 18:30:59.842  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,11-17 18:30:59.852  4070  4075 D dalvikvm: GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+1ms, total 2ms
,11-17 18:30:59.852  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,11-17 18:30:59.852  1142  1142 D KeyguardModel: handleShortcutListChanged...
,11-17 18:30:59.852  1142  1142 D KeyguardModel: handleShortcutListChanged...
,11-17 18:30:59.852  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,11-17 18:30:59.852   960  1518 I ActivityManager: Killing 3260:com.google.android.talk/u0a77 (adj 15): empty #17
11-17 18:30:59.862  1489  1489 E [LGHome]NumberBadge: [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,11-17 18:30:59.862   960  1488 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:30:59.862   960  1488 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
11-17 18:30:59.872  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,11-17 18:30:59.872  1944  4144 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,11-17 18:30:59.882  1944  4144 D AccountUtils: Clearing selected account for com.example.hello
11-17 18:30:59.882  1944  1944 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:30:59.882  1944  1944 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:59.882  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,11-17 18:30:59.892  2514  2514 D PackageIntentReceiver: Not supported Hotkey customization function 
,11-17 18:30:59.892  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
11-17 18:30:59.892   960  1516 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4146 uid=10065 gids={50065, 1028, 4002}
,11-17 18:30:59.902  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,11-17 18:30:59.912  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
11-17 18:30:59.912  1944  1944 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:30:59.912  1944  1944 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:59.912  1944  4144 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:30:59.912  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,11-17 18:30:59.922  4146  4146 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:30:59.922  4146  4146 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:30:59.922  4146  4146 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:30:59.922  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:30:59.932  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
11-17 18:30:59.932   960   971 I ActivityManager: Delaying start of: ServiceRecord{432d6530 u0 com.google.android.gms/.wearable.service.WearableControlService}
,11-17 18:30:59.942  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,11-17 18:30:59.952  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,11-17 18:30:59.952  2586  4120 I IcingCorporaProvider: UpdateCorporaTask done [took 245 ms] updated apps [took 245 ms] 
,11-17 18:30:59.962  4146  4163 D Documents: Loading roots for com.android.externalstorage.documents
,11-17 18:30:59.962  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,11-17 18:30:59.972  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,11-17 18:30:59.972  1534  1534 I ConfigService: onCreate
11-17 18:30:59.972   960  1506 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4164 uid=10005 gids={50005, 1028, 1015, 1023}
,11-17 18:30:59.982  1944  1944 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-17 18:30:59.992  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,11-17 18:30:59.992  1142  1142 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
11-17 18:30:59.992  1944  4161 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
11-17 18:30:59.992  1944  4161 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
11-17 18:30:59.992  1142  1142 D KeyguardUpdateMonitor: handleTimeUpdate
11-17 18:30:59.992  1142  1142 D KeyguardModel: mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
11-17 18:30:59.992  1944  4161 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:30:59.992  1944  4161 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
11-17 18:30:59.992  1944  4162 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:59.992  1892  1892 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:31:0
11-17 18:30:59.992  1892  1892 D WeatherService: 2 : TimeTick Intent And Screen On
11-17 18:30:59.992  1892  1892 D WeatherService: 2 : SDK version : 19
11-17 18:30:59.992  1892  1892 D WeatherQuickCover: 2 : quick cover state : opened : 0
11-17 18:31:00.002  1892  1892 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
11-17 18:31:00.002  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
11-17 18:31:00.002  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
11-17 18:31:00.002  1892  1892 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
11-17 18:31:00.002  1892  1892 D UpdateThreadPoolManager: 2 : This is isUpdating : false
11-17 18:31:00.002  1892  1892 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
11-17 18:31:00.002  1892  1892 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 1
11-17 18:31:00.002  1892  1892 D WeatherReflect: 2 : Map key string is -2
11-17 18:31:00.002  4164  4164 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:31:00.002  4164  4164 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
11-17 18:31:00.002  4164  4164 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:31:00.002  1892  1892 D lim     : 2 : time = 18:31
11-17 18:31:00.002  1892  1892 I WeatherReflect: Model Name : LG-D802
11-17 18:31:00.002  1892  1892 D WeatherTheme: 2 : Different view - status_min_formatted : 30 != 31
11-17 18:31:00.002  1892  1892 D WeatherTheme: 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
11-17 18:31:00.002  1892  1892 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
11-17 18:31:00.002  1892  1892 D WeatherTheme: 2 : Fixed theme : optimus
11-17 18:31:00.002  1892  1892 D WeatherTheme: 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
11-17 18:31:00.002   960  1516 I ActivityManager: Killing 2999:android.process.media/u0a23 (adj 15): empty #17
11-17 18:31:00.012  1944  4162 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:31:00.012  1892  1892 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:31:0
11-17 18:31:00.012   960  1516 I ActivityManager: Killing 3830:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,11-17 18:31:00.022  1892  1892 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:31:0
,11-17 18:31:00.022  1944  2694 I Icing   : doRemovePackageData com.example.hello
11-17 18:31:00.022  1944  4161 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-17 18:31:00.022  1944  4161 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,11-17 18:31:00.022  1944  4161 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:31:00.022  1142  1142 D Clock   : Clock updated, drawingStartTime : 1447781460037, nextTick: 59995, mDrawingTime: 0
,11-17 18:31:00.022  1142  1142 D Clock   : Clock updated, drawingStartTime : 1447781460038, nextTick: 59995, mDrawingTime: 0
,11-17 18:31:00.022  1892  1892 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,11-17 18:31:00.022  1892  1892 D WeatherQuickCover: 2 : quick cover state : opened : 0
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,11-17 18:31:00.032  1892  1892 D WeatherAncestor: 2 : shouldTimeTickRegistered().........
,11-17 18:31:00.032  1892  1892 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,11-17 18:31:00.032  1892  1892 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:31:0
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,11-17 18:31:00.032  1892  1892 D WeatherQuickCover: 2 : quick cover state : opened : 0
,11-17 18:31:00.032  1892  1892 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,11-17 18:31:00.032  1892  1892 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
11-17 18:31:00.032  1892  1892 D UpdateThreadPoolManager: 2 : This is isUpdating : false
11-17 18:31:00.032  1892  1892 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
,11-17 18:31:00.032  1892  1892 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 1
,11-17 18:31:00.032  1892  1892 D WeatherReflect: 2 : Map key string is -2
,11-17 18:31:00.032  1892  1892 D lim     : 2 : time = 18:31
11-17 18:31:00.032  1892  1892 I WeatherReflect: Model Name : LG-D802
11-17 18:31:00.032  1892  1892 D WeatherTheme: 2 : exactly same view!
,11-17 18:31:00.032  1892  1892 D WeatherTheme: 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
,11-17 18:31:00.032   960   991 I ActivityManager: Timeline: Activity_windows_visible id: ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1} time:50968
11-17 18:31:00.032  1944  4161 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,11-17 18:31:00.042  1944  4161 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:31:00.042  1944  4161 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-17 18:31:00.042  1944  4161 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:31:00.042  1944  4161 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:31:00.042  1944  4161 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
11-17 18:31:00.042  1892  1892 D WeatherQuickCover: 2 : quick cover state : opened : 0
,11-17 18:31:00.042  1944  4178 I PeopleContactsSync: CP2 sync disabled
,11-17 18:31:00.042  1489  1489 D dalvikvm: GC_FOR_ALLOC freed 4875K, 9% free 61905K/67520K, paused 21ms, total 21ms
11-17 18:31:00.042   960  1139 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
11-17 18:31:00.042   960  1139 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
11-17 18:31:00.042   960  1505 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:31:00.042   960  1505 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
11-17 18:31:00.052  1892  1892 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
11-17 18:31:00.052  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
11-17 18:31:00.052  1892  1892 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,11-17 18:31:00.062  4164  4164 D ExternalStorage: After updating volumes, found 1 active roots
,11-17 18:31:00.062  4146  4146 D Documents: Updating roots due to change at content://com.android.externalstorage.documents/root
,11-17 18:31:00.072  4146  4163 D Documents: Loading roots for com.android.providers.downloads.documents
,11-17 18:31:00.072   960   970 I ActivityManager: Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4179 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,11-17 18:31:00.092   960  1506 I ActivityManager: Killing 3872:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,11-17 18:31:00.092   960  1518 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5a028 stackId=0, 1 tasks}
,11-17 18:31:00.092   960  1518 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c28438 u0 com.lge.launcher2/.Launcher t1}
11-17 18:31:00.102  4179  4179 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:31:00.102  4179  4179 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
11-17 18:31:00.102  4179  4179 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:31:00.132  1489  1489 I ActivityManager: Timeline: Activity_idle id: android.os.BinderProxy@42895ff8 time:51063
11-17 18:31:00.132   960  1139 I ActivityManager: Delaying start of: ServiceRecord{4288b5f8 u0 com.android.providers.downloads/.DownloadService}
,11-17 18:31:00.172  4146  4163 D Documents: Loading roots for com.android.providers.media.documents
,11-17 18:31:00.192  4146  4163 D Documents: Loading roots for com.google.android.apps.docs.storage
,11-17 18:31:00.212  1944  4160 W DriveInitializer: Awaiting to be initialized
,11-17 18:31:00.212  1944  4196 W DriveInitializer: Background init thread started
,11-17 18:31:00.212  4146  4163 D Documents: Update found 7 roots in 256ms
,11-17 18:31:00.212  4146  4197 D Documents: Loading roots for com.android.externalstorage.documents
11-17 18:31:00.222  4146  4197 D Documents: Used cached roots for com.android.providers.downloads.documents
,11-17 18:31:00.222  4146  4197 D Documents: Used cached roots for com.android.providers.media.documents
11-17 18:31:00.222  4146  4197 D Documents: Used cached roots for com.google.android.apps.docs.storage
,11-17 18:31:00.222  4146  4197 D Documents: Update found 7 roots in 5ms
,11-17 18:31:00.252  1944  4199 E SQLiteLog: (3850) statement aborts at 184: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,11-17 18:31:00.252  1944  4199 E DocListDatabase: Failed to delete from FileContent112
11-17 18:31:00.252  1944  4199 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:31:00.252  1944  4199 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:841)
,11-17 18:31:00.252  1944  4199 W dalvikvm: threadid=41: thread exiting with uncaught exception (group=0x41858e48)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: FATAL EXCEPTION: pool-12-thread-1
11-17 18:31:00.252  1944  4199 E AndroidRuntime: Process: com.google.android.gms, PID: 1944
11-17 18:31:00.252  1944  4199 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:31:00.252  1944  4199 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:841)
,11-17 18:31:00.262   960  4204 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:31:00.262   960  4204 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:458)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:31:00.262   960  4204 E DropBoxManagerService: 	... 5 more
,11-17 18:31:00.282  1944  4160 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:31:00.282  1944  4160 E DriveAsyncService: disk I/O error (code 3850)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:31:00.282  1944  4160 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:841)
,11-17 18:31:00.282  1944  4196 W DriveInitializer: Background init thread ended
11-17 18:31:00.282   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:31:00.282  1156  1380 E BatteryObserver: usb Uevent not necessary.
,11-17 18:31:00.302   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:31:00.312  1142  1142 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,11-17 18:31:00.312   960  1129 D WifiController: battery changed pluggedType: 2
11-17 18:31:00.322  1142  1142 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
11-17 18:31:00.322  1142  1142 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 298 plugged : true isCharging : false
11-17 18:31:00.322  1142  1142 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:31:00.322  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
11-17 18:31:00.322  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
11-17 18:31:00.322  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:31:00.322  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:31:00.322  2574  2598 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t002(f003,f002,f004) VALUES (?,?,?)] disk I/O error
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: Error inserting f003=11 f002=1447781460333 f004=1320118920953921636
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertBatteryLog(MltMonitorService.java:2146)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$1300(MltMonitorService.java:38)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3119)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:136)
11-17 18:31:00.322  2574  2598 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
,11-17 18:31:00.332   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.332   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
11-17 18:31:00.332   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.332   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.332   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.332   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.332   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.332   267   267 E qdoverlay: data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
11-17 18:31:00.332   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.332   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.332   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.332   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.332   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:31:00.332   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:31:00.362   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.362   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.362   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.362   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.362   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.362   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.362   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.362   267   267 E qdoverlay: data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
11-17 18:31:00.362   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.362   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.362   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.362   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.362   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:31:00.362   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.372   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.372   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.372   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.372   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.372   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.372   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.372   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.372   267   267 E qdoverlay: data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
11-17 18:31:00.372   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.372   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.372   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.372   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.372   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.372   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:31:00.372   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:31:00.382   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.382   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.382   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.382   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.382   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.382   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.382   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.382   267   267 E qdoverlay: data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
11-17 18:31:00.382   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.382   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.382   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.382   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.382   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.382   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.402   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.402   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.402   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.402   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.402   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.402   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.402   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.402   267   267 E qdoverlay: data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
11-17 18:31:00.402   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.402   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.402   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.402   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.402   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.402   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.422   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.422   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.422   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.422   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.422   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.422   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.422   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.422   267   267 E qdoverlay: data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
11-17 18:31:00.422   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.422   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.422   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.422   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.422   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.422   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.432   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:31:00.432   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.432   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.432   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.432   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.432   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.432   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.432   267   267 E qdoverlay: data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
11-17 18:31:00.432   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.432   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.432   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.432   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.432   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.432   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.462   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.462   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.462   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.462   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.462   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.462   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.462   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.462   267   267 E qdoverlay: data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
11-17 18:31:00.462   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.462   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.462   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.462   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.462   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.462   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.472   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.472   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.472   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.472   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.472   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.472   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.472   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.472   267   267 E qdoverlay: data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
11-17 18:31:00.472   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.472   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.472   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,11-17 18:31:00.472   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.472   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.472   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.482   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.482   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.482   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.482   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.482   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.482   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.482   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.482   267   267 E qdoverlay: data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
11-17 18:31:00.482   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.482   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.482   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,11-17 18:31:00.482   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.482   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.482   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.512   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.512   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.512   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.512   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.512   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.512   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.512   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.512   267   267 E qdoverlay: data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
11-17 18:31:00.512   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.512   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.512   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.512   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,11-17 18:31:00.512   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.512   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.522   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.522   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.522   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.522   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.522   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.522   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.522   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.522   267   267 E qdoverlay: data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
11-17 18:31:00.522   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.522   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.522   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,11-17 18:31:00.522   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.522   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.522   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:31:00.522   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:31:00.532   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.532   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.532   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.542   267   267 E qdoverlay: MdpData failed to play
,11-17 18:31:00.542   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.542   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.542   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:31:00.542   267   267 E qdoverlay: data msmfb_data offset=0 memid=34 id=0 flags=0x0 priv=0
,11-17 18:31:00.542   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.542   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.542   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.542   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,11-17 18:31:00.542   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.542   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.552   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:31:00.552   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:31:00.552   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:31:00.552   267   267 E qdoverlay: MdpData failed to play
11-17 18:31:00.552   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:31:00.552   267   267 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
11-17 18:31:00.552   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
,11-17 18:31:00.552   267   267 E qdoverlay: data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
11-17 18:31:00.552   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:31:00.552   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:31:00.552   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:31:00.552   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:31:00.552   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:31:00.552   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:31:00.632   259   308 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
```
