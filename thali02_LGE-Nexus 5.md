#### Test 6177688874f8189_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/NetworkUtils( 1350): OkHttp exception
,W/EventLoggerService( 1350): Unable to send logs Error code: 262146
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1264): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1350): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1264): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1350): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/Finsky  ( 2459): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2459): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2952): 
D/AndroidRuntime( 2952): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2952): CheckJNI is OFF
D/AndroidRuntime( 2952): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2972 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2952): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 2972): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2972): Time to load native libraries: 2 ms (timestamps 2188-2190)
I/LibraryLoader( 2972): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2972): Binding Chromium to main looper Looper (main, tid 1) {130bec40}
I/LibraryLoader( 2972): Expected native library version number "",actual native library version number ""
I/chromium( 2972): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2972): Initializing chromium process, singleProcess=true
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2972): ApplicationContext is null in ApplicationStatus
W/chromium( 2972): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2972): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2972): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 2972): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2972): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d0e72e3:true
,D/BluetoothAdapter( 2972): 616677435: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2972): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2972): CordovaWebView is running on device made by: LGE
,W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2972): Render dirty regions requested: true
,D/Atlas   ( 2972): Validating map...
,W/chromium( 2972): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2972): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2972): Enabling debug mode 0
,I/Keyboard.Facilitator( 1068): onFinishInput()
,W/BindingManager( 2972): Cannot call determinedVisibility() - never saw a connection for the pid: 2972
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +448ms (total +1m9s475ms)
,W/IInputConnectionWrapper( 2972): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 2972): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2972): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35b0cc added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206bf81b added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2972): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  761): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2972): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2972): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2972): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2972): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2972): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2972): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2972): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2972): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2972): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2972): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2972): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2972): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2972): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2972): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33730db8 added. We now have 2 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7b1791 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2972): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2972): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2972): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2972): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2972): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2972): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2972): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2972): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2972): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2972): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2972): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2972): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2972): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2972): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 2972): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2972): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1068): run()
I/Keyboard.Facilitator( 1068): flushDynamicLanguageModels()
,I/ConfigService( 1264): onCreate
,I/ConfigService( 1264): onDestroy
,I/ClearcutLoggerApiImpl( 1264): disconnect managed GoogleApiClient
,I/art     (  761): Explicit concurrent mark sweep GC freed 18583(818KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.109ms total 52.041ms
,I/VacuumService( 1264): Vacuum at: now=1457130236173 tag=VacuumService
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1764:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1764/cgroup.procs: No such file or directory
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3075): 
D/AndroidRuntime( 3075): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3075): CheckJNI is OFF
D/AndroidRuntime( 3075): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2972:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{17f1dad3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{2f0d9027 com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{3391f6dc u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  761): Spurious death for ProcessRecord{bfb3159 2972:com.test.thalitest/u0a270}, curProc for 2972: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{3391f6dc u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{3391f6dc u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1350): Explicit concurrent mark sweep GC freed 3062(204KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 683us total 51.792ms
W/GeofencerStateMachine( 1264): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1068): resetDictionaries() : en_US
I/art     ( 1244): Explicit concurrent mark sweep GC freed 7355(554KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 673us total 71.199ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 844(34KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 362us total 82.530ms
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1068): run()
I/Decoder ( 1068): createOrResetDecoder
I/UpdateIcingCorporaServi( 1350): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/VoicemailCleanupService( 2647): Cleaning up data for package: com.test.thalitest
I/art     (  761): Explicit concurrent mark sweep GC freed 10283(732KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 966us total 83.616ms
I/art     (  761): WaitForGcToComplete blocked for 39.923ms for cause Explicit
W/Launcher( 1244): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@130bec40 new=com.google.android.velvet.VelvetApplication@130bec40
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
D/OpenGLRenderer(  946): Enabling debug mode 0
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3114 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ConfigService( 1264): onCreate
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=220_task.xml
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2972 uid 10270
I/Keyboard.Facilitator( 1068): onFinishInput()
I/art     (  761): Explicit concurrent mark sweep GC freed 3860(212KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.713ms total 113.727ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1068): run()
I/UpdateIcingCorporaServi( 1350): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
W/ContextImpl( 3114): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1557): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1557): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1068): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = contacts
D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1068): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1068): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1068): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1068): run()
I/StatsUtilsManager( 1068): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1068): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 1264): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1264): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator( 1068): onFinishInput()
W/IInputConnectionWrapper( 1244): showStatusIcon on inactive InputConnection
I/LocationSettingsChecker( 1557): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1557): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3148 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1244): Deferring update until onResume
D/AndroidRuntime( 3075): Shutting down VM
W/BaseAppContext( 1557): Using Auth Proxy for data requests.
W/BaseAppContext( 1557): Using Auth Proxy for data requests.
W/ResourcesManager( 1244): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GMPM-SVC( 1557): App measurement is starting up, version: 8489
I/GMPM-SVC( 1557): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1244): Deferring update until onResume
I/Icing   ( 1557): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3174 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2518:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2518/cgroup.procs: No such file or directory
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Killing 2384:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3174): After updating volumes, found 1 active roots
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2384/cgroup.procs: No such file or directory
W/DriveInitializer( 1557): Awaiting to be initialized
W/DriveInitializer( 1557): Background init thread started
E/SQLiteLog( 1557): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1557): Failed to delete from FileContent163 table
E/DocListDatabase( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 1557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1557): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 2701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of crash
E/AndroidRuntime( 1557): FATAL EXCEPTION: pool-12-thread-1
E/AndroidRuntime( 1557): Process: com.google.android.gms, PID: 1557
E/AndroidRuntime( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 1557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1557): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1557): Sending signal. PID: 1557 SIG: 9
E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop84.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  761): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  761): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  761): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  761): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  761): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  761): 	... 5 more
D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3742c752)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Process com.google.android.gms (pid 1557) has died
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
D/Documents( 3148): Update found 7 roots in 326ms

```
