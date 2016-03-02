#### Test 61432979123161a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/CAR.SERVICE( 3086): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 3086): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ea6d59b that was originally bound here
E/ActivityThread( 3086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ea6d59b that was originally bound here
E/ActivityThread( 3086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3086): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3086): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3086): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3086): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3086): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3086): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3086): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3086): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3086): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2147d002 that was originally bound here
E/ActivityThread( 3086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2147d002 that was originally bound here
E/ActivityThread( 3086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3086): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3086): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3086): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3086): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3086): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  755): Unbind failed: could not find connection for android.os.BinderProxy@988a07d
,D/AndroidRuntime( 3167): 
D/AndroidRuntime( 3167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3167): CheckJNI is OFF
D/AndroidRuntime( 3167): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3187 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3167): Shutting down VM
V/ActivityManager(  755): Display changed displayId=0
I/WebViewFactory( 3187): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3187): Time to load native libraries: 3 ms (timestamps 8804-8807)
I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3187): Binding Chromium to main looper Looper (main, tid 1) {1e7ba553}
I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
I/chromium( 3187): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3187): Initializing chromium process, singleProcess=true
W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3187): ApplicationContext is null in ApplicationStatus
W/chromium( 3187): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3187): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd1ecb1:true
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3187): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3187): CordovaWebView is running on device made by: LGE
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3187): Render dirty regions requested: true
,D/Atlas   ( 3187): Validating map...
,W/chromium( 3187): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3187): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3187): Enabling debug mode 0
,W/IInputConnectionWrapper( 3187): showStatusIcon on inactive InputConnection
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +459ms (total +1m6s898ms)
,W/BindingManager( 3187): Cannot call determinedVisibility() - never saw a connection for the pid: 3187
,D/JsMessageQueue( 3187): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3187): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15065cee added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f8a425 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3187): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  755): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3187): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3187): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 3187): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3187): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3187): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3187): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3187): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3187): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3187): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3187): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3187): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3187): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3187): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3187): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@157f59fa added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ffabab added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3187): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 3187): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 3187): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
,W/System.err( 3187): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3187): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3187): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3187): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3187): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3187): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3187): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3187): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3187): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3187): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3187): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3187): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/Finsky  ( 2656): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2656): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1607): Vacuum at: now=1456940243911 tag=VacuumService
,I/PhenotypeConfigurator( 1607): Scheduling Phenotype for one-off execution 2642 seconds from now (1456940244266)
,I/PhenotypeFlagCommitter( 1607): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1607): Using platform SSLCertificateSocketFactory
,W/ProcessCpuTracker(  755): Skipping unknown process pid 3276
W/ProcessCpuTracker(  755): Skipping unknown process pid 3279
,I/ClearcutLoggerApiImpl( 1607): disconnect managed GoogleApiClient
,I/ActivityManager(  755): Killing 2619:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10069/pid_2619/cgroup.procs: No such file or directory
,I/ActivityManager(  755): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3285 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3285): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3285):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3285):   adb logcat -s GAv4
,W/GAv4    ( 3285): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3285): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3285): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  755): Killing 2551:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_2551/cgroup.procs: No such file or directory
,W/bt-smp  ( 2122): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2122): Plain text(LSB ~ MSB) = 9e be 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2122): Encrypted text(LSB ~ MSB) = de 40 cf bd 98 5a 48 64 60 54 4b 8b dc ed a9 13 
W/bt-btm  ( 2122): Stopping oneshot timer
,I/UsageStatsService(  755): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3336): 
D/AndroidRuntime( 3336): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3336): CheckJNI is OFF
D/AndroidRuntime( 3336): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 3187:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  755): WIN DEATH: Window{1ec66421 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  755): Client connection lost with reason: 4
W/PackageSettings(  755): Skipping PackageSetting{74a8bb6 com.example.hello/10278} due to missing metadata
I/ActivityManager(  755):   Force finishing activity ActivityRecord{dc09b72 u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  755): Spurious death for ProcessRecord{2384a7c9 3187:com.test.thalitest/u0a270}, curProc for 3187: null
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1315): Explicit concurrent mark sweep GC freed 7339(553KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 906us total 18.397ms
I/art     ( 1396): Explicit concurrent mark sweep GC freed 7866(561KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 633us total 35.782ms
I/art     ( 1640): Explicit concurrent mark sweep GC freed 2821(161KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/29MB, paused 448us total 68.470ms
W/GeofencerStateMachine( 1607): Ignoring removeGeofence because network location is disabled.
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1114): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1114): run()
I/Decoder ( 1114): createOrResetDecoder
D/VoicemailCleanupService( 1369): Cleaning up data for package: com.test.thalitest
I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
I/UpdateIcingCorporaServi( 1396): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1315): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e7ba553 new=com.google.android.velvet.VelvetApplication@1e7ba553
D/OpenGLRenderer(  943): Enabling debug mode 0
I/art     (  755): Explicit concurrent mark sweep GC freed 30307(1666KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.305ms total 128.185ms
I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3378 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  755): WaitForGcToComplete blocked for 83.157ms for cause Explicit
W/InputMethodManagerService(  755): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@35d514df (uid=10034 pid=943)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): run()
W/ContextImpl( 3378): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  755): removeObsoleteFile: deleting file=218_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1114): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1114): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1114): run()
I/StatsUtilsManager( 1114): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1114): shouldRecordStats() = Too Soon
D/PackageBroadcastService( 1640): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1640): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1640): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1640): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1396): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
D/ChimeraCfgMgr( 1640): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1640): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1607): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1607): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1640): Removing dialog suppression flag for package com.test.thalitest
I/art     (  755): Explicit concurrent mark sweep GC freed 6221(343KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.419ms total 157.294ms
D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1640): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3415 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/AndroidRuntime( 3336): Shutting down VM
W/BaseAppContext( 1640): Using Auth Proxy for data requests.
I/GMPM-SVC( 1640): App measurement is starting up, version: 8489
I/GMPM-SVC( 1640): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1640): Using Auth Proxy for data requests.
I/Icing   ( 1640): doRemovePackageData com.test.thalitest
I/ActivityManager(  755): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3438 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  755): Killing 2773:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2773/cgroup.procs: No such file or directory
I/ActivityManager(  755): Killing 2714:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  755): Client connection lost with reason: 4
W/libprocessgroup(  755): failed to open /acct/uid_1000/pid_2714/cgroup.procs: No such file or directory
I/Launcher( 1315): Deferring update until onResume
D/ExternalStorage( 3438): After updating volumes, found 1 active roots
W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1315): Deferring update until onResume
W/ResourcesManager( 2869): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2869): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3415): Update found 7 roots in 300ms
D/Documents( 3415): Update found 7 roots in 133ms

```
