#### Test 614329799926788_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/CAR.SERVICE( 3039): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 3039): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1653e8d that was originally bound here
E/ActivityThread( 3039): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1653e8d that was originally bound here
E/ActivityThread( 3039): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3039): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3039): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3039): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3039): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3039): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3039): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3039): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3039): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3039): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3039): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3039): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3039): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3039): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3039): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3039): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3039): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3039): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3039): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3039): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3039): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3039): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3039): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2b2052bc that was originally bound here
E/ActivityThread( 3039): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2b2052bc that was originally bound here
E/ActivityThread( 3039): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3039): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3039): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3039): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3039): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3039): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3039): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3039): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3039): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3039): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3039): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3039): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3039): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3039): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3039): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3039): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3039): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3039): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3039): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3039): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3039): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@1852e629
,D/AndroidRuntime( 3133): 
D/AndroidRuntime( 3133): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3133): CheckJNI is OFF
D/AndroidRuntime( 3133): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3153 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3133): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 530us total 8.535ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.378ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.762ms
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3153): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3153): Time to load native libraries: 2 ms (timestamps 2399-2401)
I/LibraryLoader( 3153): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3153): Binding Chromium to main looper Looper (main, tid 1) {3abc7885}
I/LibraryLoader( 3153): Expected native library version number "",actual native library version number ""
I/chromium( 3153): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3153): Initializing chromium process, singleProcess=true
W/art     ( 3153): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3153): ApplicationContext is null in ApplicationStatus
,W/chromium( 3153): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3153): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3153): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3153): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3edd829d:true
,W/art     ( 3153): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3153): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3153): CordovaWebView is running on device made by: LGE
,W/art     ( 3153): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3153): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3153): Render dirty regions requested: true
,D/Atlas   ( 3153): Validating map...
,W/chromium( 3153): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3153): Initialized EGL, version 1.4
D/OpenGLRenderer( 3153): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +532ms (total +60s388ms)
,I/art     (  761): Explicit concurrent mark sweep GC freed 28070(1307KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.042ms total 56.120ms
,I/Keyboard.Facilitator( 1064): onFinishInput()
,W/IInputConnectionWrapper( 3153): showStatusIcon on inactive InputConnection
,W/BindingManager( 3153): Cannot call determinedVisibility() - never saw a connection for the pid: 3153
,D/JsMessageQueue( 3153): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3153): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258380416
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@105e9c48 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d586c7 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3153): addListener: New listener added - the number of listeners is now 1
D/WifiService(  761): New client listening to asynchronous messages
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3153): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3153): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 3153): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3153): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3153): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3153): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3153): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3153): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3153): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3153): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3153): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3153): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3153): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3153): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3153): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e534f4 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3172141d added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3153): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3153): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 3153): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 3153): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 3153): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3153): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3153): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3153): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3153): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3153): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3153): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3153): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3153): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3153): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3153): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3153): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3153): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/Finsky  ( 2636): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2636): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1628): Vacuum at: now=1457077200060 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1064): run()
I/Keyboard.Facilitator( 1064): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1628): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Killing 2070:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2070/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3258 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3258): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3258):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3258):   adb logcat -s GAv4
,W/GAv4    ( 3258): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3258): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3258): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2723:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2723/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1628): Scheduling Phenotype for one-off execution 2083 seconds from now (1457078031870)
,I/PhenotypeFlagCommitter( 1628): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1628): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-smp  ( 2119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2119): Plain text(LSB ~ MSB) = 3a 33 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2119): Encrypted text(LSB ~ MSB) = 0e 44 47 6e 89 e1 06 6f 91 80 33 a4 df ee 29 79 
,W/bt-btm  ( 2119): Stopping oneshot timer
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3340): 
D/AndroidRuntime( 3340): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3340): CheckJNI is OFF
D/AndroidRuntime( 3340): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3153:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{9c94d0d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{3c87ecd0 com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{a22adae u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  761): Spurious death for ProcessRecord{bcd1c04 3153:com.test.thalitest/u0a270}, curProc for 3153: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{a22adae u0 com.test.thalitest/.MainActivity t218 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{a22adae u0 com.test.thalitest/.MainActivity t218 f}
I/art     ( 1281): Explicit concurrent mark sweep GC freed 7363(554KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 223us total 29.691ms
I/art     ( 1360): Explicit concurrent mark sweep GC freed 7499(534KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 302us total 44.689ms
W/GeofencerStateMachine( 1628): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1064): resetDictionaries() : en_US
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Keyboard.Facilitator.DecoderInitializer( 1064): run()
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
I/Decoder ( 1064): createOrResetDecoder
D/OpenGLRenderer(  944): Enabling debug mode 0
I/art     (  761): Explicit concurrent mark sweep GC freed 23117(1337KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 2.492ms total 99.631ms
I/art     (  761): WaitForGcToComplete blocked for 85.484ms for cause Explicit
I/art     ( 1607): Explicit concurrent mark sweep GC freed 2737(158KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 705us total 130.509ms
D/VoicemailCleanupService( 1383): Cleaning up data for package: com.test.thalitest
I/UpdateIcingCorporaServi( 1360): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1281): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3abc7885 new=com.google.android.velvet.VelvetApplication@3abc7885
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3153 uid 10270
I/Keyboard.Facilitator( 1064): onFinishInput()
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3382 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): run()
D/TaskPersister(  761): removeObsoleteFile: deleting file=218_task.xml
I/art     (  761): Explicit concurrent mark sweep GC freed 4328(252KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.910ms total 124.952ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = contacts
W/ContextImpl( 3382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1064): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1064): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1064): run()
I/StatsUtilsManager( 1064): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1064): shouldRecordStats() = Too Soon
I/UpdateIcingCorporaServi( 1360): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
D/PackageBroadcastService( 1607): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1607): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1607): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1607): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1607): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1607): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1628): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1628): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator( 1064): onFinishInput()
W/IInputConnectionWrapper( 1281): showStatusIcon on inactive InputConnection
I/LocationSettingsChecker( 1607): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1607): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 3340): Shutting down VM
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3415 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/BaseAppContext( 1607): Using Auth Proxy for data requests.
W/BaseAppContext( 1607): Using Auth Proxy for data requests.
I/GMPM-SVC( 1607): App measurement is starting up, version: 8489
I/GMPM-SVC( 1607): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 1607): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3439 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2697:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  761): Client connection lost with reason: 4
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2697/cgroup.procs: No such file or directory
I/ActivityManager(  761): Killing 1477:com.google.android.partnersetup/u0a13 (adj 15): empty #17
D/ExternalStorage( 3439): After updating volumes, found 1 active roots
W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1477/cgroup.procs: No such file or directory
I/Launcher( 1281): Deferring update until onResume
W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1281): Deferring update until onResume
W/ResourcesManager( 2853): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2853): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
