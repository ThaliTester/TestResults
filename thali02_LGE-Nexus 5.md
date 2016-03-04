#### Test 61699762a45f11c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2643): [261] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2643): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 3172): 
D/AndroidRuntime( 3172): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3172): CheckJNI is OFF
D/AndroidRuntime( 3172): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3189 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3172): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
I/WebViewFactory( 3189): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3189): Time to load native libraries: 1 ms (timestamps 1764-1765)
I/LibraryLoader( 3189): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3189): Binding Chromium to main looper Looper (main, tid 1) {2e1411af}
I/LibraryLoader( 3189): Expected native library version number "",actual native library version number ""
I/chromium( 3189): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3189): Initializing chromium process, singleProcess=true
W/art     ( 3189): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3189): ApplicationContext is null in ApplicationStatus
,W/chromium( 3189): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3189): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3189): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3189): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13cb60ed:true
,W/art     ( 3189): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3189): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3189): CordovaWebView is running on device made by: LGE
,W/art     ( 3189): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3189): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3189): Render dirty regions requested: true
,D/Atlas   ( 3189): Validating map...
,W/chromium( 3189): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3189): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3189): Enabling debug mode 0
,I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +425ms (total +1m10s115ms)
,I/art     (  736): Explicit concurrent mark sweep GC freed 30617(1439KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 798us total 86.093ms
,W/IInputConnectionWrapper( 3189): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1058): onFinishInput()
,W/BindingManager( 3189): Cannot call determinedVisibility() - never saw a connection for the pid: 3189
,D/JsMessageQueue( 3189): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3189): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1404477056
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60dfffa added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f7bba1 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3189): addListener: New listener added - the number of listeners is now 1
D/WifiService(  736): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3189): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3189): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3189): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3189): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 3189): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
,W/System.err( 3189): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3189): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3189): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3189): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3189): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3189): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3189): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3189): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3189): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2c21c6 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2938e587 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3189): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3189): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3189): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3189): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3189): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3189): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3189): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3189): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3189): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3189): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3189): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3189): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3189): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3189): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3189): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3189): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1553): Vacuum at: now=1457092482856 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1058): run()
I/Keyboard.Facilitator( 1058): flushDynamicLanguageModels()
,I/ConfigService( 1553): onCreate
,I/ConfigService( 1553): onDestroy
,I/ClearcutLoggerApiImpl( 1553): disconnect managed GoogleApiClient
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3278 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3278): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3278):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3278):   adb logcat -s GAv4
,W/GAv4    ( 3278): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/EventLogService( 1600): Aggregate from 1457090973083 (log), 1457090973083 (data)
,W/GAv4    ( 3278): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3278): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Killing 2732:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2732/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 2712:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  736): Client connection lost with reason: 4
,W/libprocessgroup(  736): failed to open /acct/uid_1000/pid_2712/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1553): Scheduling Phenotype for one-off execution 4892 seconds from now (1457093314659)
,I/PhenotypeFlagCommitter( 1553): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1553): Using platform SSLCertificateSocketFactory
,W/bt-smp  ( 2112): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2112): Plain text(LSB ~ MSB) = 73 e7 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2112): Encrypted text(LSB ~ MSB) = 1e 28 c4 f4 d6 e3 ec ee 39 3d 7f 59 6b b3 97 f0 
,W/bt-btm  ( 2112): Stopping oneshot timer
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3353): 
D/AndroidRuntime( 3353): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3353): CheckJNI is OFF
D/AndroidRuntime( 3353): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 3189:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  736): WIN DEATH: Window{11535f5d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  736): Client connection lost with reason: 4
I/ActivityManager(  736):   Force finishing activity ActivityRecord{3a6fc2be u0 com.test.thalitest/.MainActivity t218}
W/PackageSettings(  736): Skipping PackageSetting{989342 com.example.hello/10278} due to missing metadata
W/ActivityManager(  736): Spurious death for ProcessRecord{27047032 3189:com.test.thalitest/u0a270}, curProc for 3189: null
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1394): Explicit concurrent mark sweep GC freed 6368(507KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 301us total 18.441ms
I/art     ( 1600): Explicit concurrent mark sweep GC freed 4438(293KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 469us total 29.040ms
W/GeofencerStateMachine( 1553): Ignoring removeGeofence because network location is disabled.
I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1273): Explicit concurrent mark sweep GC freed 7342(553KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 526us total 52.779ms
I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
I/Keyboard.Facilitator( 1058): resetDictionaries() : en_US
D/OpenGLRenderer(  947): Enabling debug mode 0
I/art     (  736): Explicit concurrent mark sweep GC freed 22492(1350KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 991us total 75.298ms
I/art     (  736): WaitForGcToComplete blocked for 16.072ms for cause Explicit
I/Keyboard.Facilitator.DecoderInitializer( 1058): run()
I/Decoder ( 1058): createOrResetDecoder
D/VoicemailCleanupService( 2862): Cleaning up data for package: com.test.thalitest
W/InputMethodManagerService(  736): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@281f8173 (uid=10034 pid=947)
I/ConfigService( 1553): onCreate
I/UpdateIcingCorporaServi( 1394): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Keyboard.Facilitator.MainLanguageModelLoader( 1058): run()
D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
W/Launcher( 1273): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2e1411af new=com.google.android.velvet.VelvetApplication@2e1411af
W/InputMethodManagerService(  736): Got RemoteException sending setActive(false) notification to pid 3189 uid 10270
I/Keyboard.Facilitator( 1058): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1058): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1058): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1058): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1058): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1058): run()
I/StatsUtilsManager( 1058): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1058): shouldRecordStats() = Too Soon
I/ActivityManager(  736): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3399 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  736): removeObsoleteFile: deleting file=218_task.xml
I/art     (  736): Explicit concurrent mark sweep GC freed 4881(271KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.104ms total 148.353ms
I/UpdateIcingCorporaServi( 1394): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
W/ContextImpl( 3399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1600): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1600): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1553): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1553): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1600): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1600): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/AndroidRuntime( 3353): Shutting down VM
D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  736): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3427 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/BaseAppContext( 1600): Using Auth Proxy for data requests.
I/GMPM-SVC( 1600): App measurement is starting up, version: 8489
I/GMPM-SVC( 1600): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1600): Using Auth Proxy for data requests.
I/Icing   ( 1600): doRemovePackageData com.test.thalitest
I/ActivityManager(  736): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3452 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  736): Killing 1461:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_1461/cgroup.procs: No such file or directory
I/Launcher( 1273): Deferring update until onResume
I/ActivityManager(  736): Killing 1922:com.android.defcontainer/u0a5 (adj 15): empty #17
W/ResourcesManager( 1273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1273): Deferring update until onResume
W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_1922/cgroup.procs: No such file or directory
D/ExternalStorage( 3452): After updating volumes, found 1 active roots
W/ResourcesManager( 2916): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2916): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
