#### Test 61362366121daa0_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/CAR.SERVICE( 3018): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 3018): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3312bb2 that was originally bound here
E/ActivityThread( 3018): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3312bb2 that was originally bound here
E/ActivityThread( 3018): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3018): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3018): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3018): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3018): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3018): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3018): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3018): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3018): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3018): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3018): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3018): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3018): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3018): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3018): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3018): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3018): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3018): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3018): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3018): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3018): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11a7f375 that was originally bound here
E/ActivityThread( 3018): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11a7f375 that was originally bound here
E/ActivityThread( 3018): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3018): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3018): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3018): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3018): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3018): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3018): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3018): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3018): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3018): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3018): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3018): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3018): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3018): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3018): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3018): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3018): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3018): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3018): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@3ed007a6
,D/AndroidRuntime( 3099): 
D/AndroidRuntime( 3099): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3099): CheckJNI is OFF
D/AndroidRuntime( 3099): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3120 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3099): Shutting down VM
,V/ActivityManager(  758): Display changed displayId=0
,I/WebViewFactory( 3120): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3120): Time to load native libraries: 1 ms (timestamps 8977-8978)
,I/LibraryLoader( 3120): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3120): Binding Chromium to main looper Looper (main, tid 1) {19a2784a}
I/LibraryLoader( 3120): Expected native library version number "",actual native library version number ""
I/chromium( 3120): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3120): Initializing chromium process, singleProcess=true
W/art     ( 3120): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3120): ApplicationContext is null in ApplicationStatus
,W/chromium( 3120): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3120): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3120): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3120): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26ff5b8a:true
,W/art     ( 3120): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3120): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3120): CordovaWebView is running on device made by: LGE
,W/art     ( 3120): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3120): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3120): Render dirty regions requested: true
,D/Atlas   ( 3120): Validating map...
,W/chromium( 3120): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3120): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3120): Enabling debug mode 0
,I/Keyboard.Facilitator( 1081): onFinishInput()
,W/BindingManager( 3120): Cannot call determinedVisibility() - never saw a connection for the pid: 3120
W/IInputConnectionWrapper( 3120): showStatusIcon on inactive InputConnection
,I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +391ms (total +1m7s114ms)
,D/JsMessageQueue( 3120): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3120): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@180ef711 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5652e4 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3120): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  758): New client listening to asynchronous messages
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3120): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3120): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 3120): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3120): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3120): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3120): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3120): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3120): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3120): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3120): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3120): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3120): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3120): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 3120): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3120): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345af34d added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b693e02 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3120): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3120): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3120): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3120): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 3120): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3120): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3120): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3120): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3120): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3120): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3120): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3120): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3120): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3120): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3120): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3120): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3120): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/Finsky  ( 2650): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,E/ActivityThread( 1614): Failed to find provider info for com.android.contacts.metadata
,D/Finsky  ( 2650): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SyncManager(  758): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 73200, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  758): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 163070, reason: UserStart
,I/art     (  758): Explicit concurrent mark sweep GC freed 26613(1193KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.049ms total 77.494ms
,V/GLSActivity( 1630): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1630): Vacuum at: now=1456925814186 tag=VacuumService
,I/PhenotypeConfigurator( 1630): Scheduling Phenotype for one-off execution 6636 seconds from now (1456925814869)
,I/PhenotypeFlagCommitter( 1630): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1630): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1081): run()
I/Keyboard.Facilitator( 1081): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1630): disconnect managed GoogleApiClient
,I/ActivityManager(  758): Killing 1836:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_1836/cgroup.procs: No such file or directory
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3249 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 15.634ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 10.355ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 164us total 12.276ms
,I/GAv4    ( 3249): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3249):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3249):   adb logcat -s GAv4
,W/GAv4    ( 3249): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3249): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3249): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2113:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2113/cgroup.procs: No such file or directory
,W/bt-smp  ( 2156): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2156): Plain text(LSB ~ MSB) = b4 72 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2156): Encrypted text(LSB ~ MSB) = ac 04 bd 29 fc 26 56 06 0f de 72 ae 5d e6 62 53 
W/bt-btm  ( 2156): Stopping oneshot timer
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 3300): 
D/AndroidRuntime( 3300): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3300): CheckJNI is OFF
D/AndroidRuntime( 3300): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 3120:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  758): Client connection lost with reason: 4
I/WindowState(  758): WIN DEATH: Window{28edbb3a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  758): Skipping PackageSetting{142142f9 com.example.hello/10278} due to missing metadata
I/ActivityManager(  758):   Force finishing activity ActivityRecord{314c05e7 u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  758): Spurious death for ProcessRecord{2c108b89 3120:com.test.thalitest/u0a270}, curProc for 3120: null
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1374): Explicit concurrent mark sweep GC freed 6363(507KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 294us total 39.350ms
I/art     ( 1286): Explicit concurrent mark sweep GC freed 7362(554KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.143ms total 32.840ms
I/art     ( 1614): Explicit concurrent mark sweep GC freed 2704(158KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/29MB, paused 451us total 48.018ms
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1081): resetDictionaries() : en_US
W/GeofencerStateMachine( 1630): Ignoring removeGeofence because network location is disabled.
I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/VoicemailCleanupService( 1353): Cleaning up data for package: com.test.thalitest
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
I/Keyboard.Facilitator.DecoderInitializer( 1081): run()
D/OpenGLRenderer(  947): Enabling debug mode 0
I/UpdateIcingCorporaServi( 1374): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Decoder ( 1081): createOrResetDecoder
W/Launcher( 1286): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@19a2784a new=com.google.android.velvet.VelvetApplication@19a2784a
I/art     (  758): Explicit concurrent mark sweep GC freed 18352(1107KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.690ms total 112.418ms
I/art     (  758): WaitForGcToComplete blocked for 22.393ms for cause Explicit
I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3339 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 3120 uid 10270
I/Keyboard.Facilitator( 1081): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): run()
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
I/UpdateIcingCorporaServi( 1374): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
W/ContextImpl( 3339): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/TaskPersister(  758): removeObsoleteFile: deleting file=218_task.xml
D/PackageBroadcastService( 1614): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1614): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = contacts
I/Keyboard.Facilitator( 1081): onFinishInput()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = user
E/NetworkScheduler.SchedulerReceiver( 1630): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1630): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1081): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1081): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1081): run()
I/StatsUtilsManager( 1081): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1081): shouldRecordStats() = Too Soon
W/IInputConnectionWrapper( 1286): showStatusIcon on inactive InputConnection
I/art     (  758): Explicit concurrent mark sweep GC freed 5322(276KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.282ms total 151.616ms
I/LocationSettingsChecker( 1614): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1614): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  758): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3372 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/AndroidRuntime( 3300): Shutting down VM
W/BaseAppContext( 1614): Using Auth Proxy for data requests.
I/GMPM-SVC( 1614): App measurement is starting up, version: 8489
I/GMPM-SVC( 1614): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1614): Using Auth Proxy for data requests.
I/Icing   ( 1614): doRemovePackageData com.test.thalitest
I/ActivityManager(  758): Killing 2764:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2764/cgroup.procs: No such file or directory
I/ActivityManager(  758): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3400 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  758): Killing 2708:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  758): Client connection lost with reason: 4
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2708/cgroup.procs: No such file or directory
D/ExternalStorage( 3400): After updating volumes, found 1 active roots
W/ResourcesManager( 2860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Launcher( 1286): Deferring update until onResume
E/SQLiteLog( 1286): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
