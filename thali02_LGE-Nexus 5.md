#### Test 60124347d4f5b03_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkUtils( 1343): OkHttp exception
W/EventLoggerService( 1343): Unable to send logs Error code: 262146
E/Auth    ( 1293): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1343): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1293): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1343): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/Finsky  ( 2523): [240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2523): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 3021): 
D/AndroidRuntime( 3021): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3021): CheckJNI is OFF
D/AndroidRuntime( 3021): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3043 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3021): Shutting down VM
V/ActivityManager(  755): Display changed displayId=0
I/WebViewFactory( 3043): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3043): Time to load native libraries: 2 ms (timestamps 2193-2195)
I/LibraryLoader( 3043): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3043): Binding Chromium to main looper Looper (main, tid 1) {3e5fdd6e}
I/LibraryLoader( 3043): Expected native library version number "",actual native library version number ""
I/chromium( 3043): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3043): Initializing chromium process, singleProcess=true
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3043): ApplicationContext is null in ApplicationStatus
W/chromium( 3043): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3043): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3043): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  755): Message: 20
,D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@114893cc:true
,D/BluetoothAdapter( 3043): 485968427: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3043): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3043): CordovaWebView is running on device made by: LGE
,W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3043): Render dirty regions requested: true
,D/Atlas   ( 3043): Validating map...
,W/chromium( 3043): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3043): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3043): Enabling debug mode 0
,W/IInputConnectionWrapper( 3043): showStatusIcon on inactive InputConnection
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +470ms (total +1m10s791ms)
,W/BindingManager( 3043): Cannot call determinedVisibility() - never saw a connection for the pid: 3043
,D/JsMessageQueue( 3043): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3043): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@322aa5da added. We now have 1 listener(s)
D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3043): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229d45a6 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3043): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  755): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3043): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 3043): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3043): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3043): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3043): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3043): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3043): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3043): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3043): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3043): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3043): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3043): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3043): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3043): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3043): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c936be7 added. We now have 2 listener(s)
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3043): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f8394 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3043): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3043): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3043): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3043): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3043): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3043): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3043): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3043): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
,W/System.err( 3043): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3043): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3043): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3043): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3043): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3043): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3043): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ProcessCpuTracker(  755): Skipping unknown process pid 3001
W/ProcessCpuTracker(  755): Skipping unknown process pid 3004
,I/chromium( 3043): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3043): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/VacuumService( 1293): Vacuum at: now=1457399641880 tag=VacuumService
,I/art     (  755): Explicit concurrent mark sweep GC freed 18332(792KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 869us total 55.967ms
,I/ClearcutLoggerApiImpl( 1293): disconnect managed GoogleApiClient
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  755): Killing 1816:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_1816/cgroup.procs: No such file or directory
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium(  948): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  948): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  948): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  755): User[0] Flushing usage stats to disk
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3131): 
D/AndroidRuntime( 3131): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3131): CheckJNI is OFF
D/AndroidRuntime( 3131): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 3043:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  755): WIN DEATH: Window{ffe87fc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  755): Client connection lost with reason: 4
W/PackageSettings(  755): Skipping PackageSetting{2fbeaed com.example.hello/10278} due to missing metadata
I/ActivityManager(  755):   Force finishing activity ActivityRecord{6363b21 u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  755): Spurious death for ProcessRecord{21317dbf 3043:com.test.thalitest/u0a270}, curProc for 3043: null
I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  755):   Force finishing activity ActivityRecord{6363b21 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  755): Duplicate finish request for ActivityRecord{6363b21 u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1300): Explicit concurrent mark sweep GC freed 7329(552KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 225us total 16.132ms
I/art     ( 1603): Explicit concurrent mark sweep GC freed 1022(40KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 382us total 46.553ms
I/art     ( 1343): Explicit concurrent mark sweep GC freed 5567(370KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 690us total 42.596ms
I/Keyboard.Facilitator( 1085): resetDictionaries() : en_US
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1293): Ignoring removeGeofence because network location is disabled.
I/LibraryLoader( 1434): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/Keyboard.Facilitator.DecoderInitializer( 1085): run()
I/Decoder ( 1085): createOrResetDecoder
D/VoicemailCleanupService( 2713): Cleaning up data for package: com.test.thalitest
I/UpdateIcingCorporaServi( 1343): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1300): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e5fdd6e new=com.google.android.velvet.VelvetApplication@3e5fdd6e
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
D/OpenGLRenderer(  948): Enabling debug mode 0
I/art     (  755): Explicit concurrent mark sweep GC freed 10895(794KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.494ms total 114.946ms
I/art     (  755): WaitForGcToComplete blocked for 96.093ms for cause Explicit
I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3170 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/LibraryLoader( 1434): Time to load native libraries: 88 ms (timestamps 3309-3397)
I/LibraryLoader( 1434): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1434): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1434): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1434): Attempt to remove local handle scope entry from IRT, ignoring
I/ConfigService( 1293): onCreate
W/art     (  948): Attempt to remove local handle scope entry from IRT, ignoring
W/InputMethodManagerService(  755): Got RemoteException sending setActive(false) notification to pid 3043 uid 10270
I/Keyboard.Facilitator( 1085): onFinishInput()
D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  755): removeObsoleteFile: deleting file=220_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): run()
W/ContextImpl( 3170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1085): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1085): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1085): run()
I/StatsUtilsManager( 1085): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1085): shouldRecordStats() = Too Soon
D/PackageBroadcastService( 1603): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1603): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1603): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1603): Clearing selected account for com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1293): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1293): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1603): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1603): Module APK com.google.android.play.games already loaded
I/art     (  755): Explicit concurrent mark sweep GC freed 6741(334KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 5.430ms total 214.337ms
I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3207 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1343): UpdateCorporaTask done [took 314 ms] updated apps [took 314 ms] 
I/LocationSettingsChecker( 1603): Removing dialog suppression flag for package com.test.thalitest
I/Launcher( 1300): Deferring update until onResume
D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1603): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/AndroidRuntime( 3131): Shutting down VM
D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1603): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1603): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1603): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1603): Using Auth Proxy for data requests.
W/ResourcesManager( 1300): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1603): Using Auth Proxy for data requests.
I/GMPM-SVC( 1603): App measurement is starting up, version: 8489
I/GMPM-SVC( 1603): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1300): Deferring update until onResume
I/Icing   ( 1603): doRemovePackageData com.test.thalitest
I/ActivityManager(  755): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3237 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 288us total 8.083ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.318ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 7.613ms
I/ActivityManager(  755): Killing 2598:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2598/cgroup.procs: No such file or directory
I/ActivityManager(  755): Killing 2449:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3237): After updating volumes, found 1 active roots
W/libprocessgroup(  755): failed to open /acct/uid_10070/pid_2449/cgroup.procs: No such file or directory
D/ConnectivityService(  755): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 2768): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2768): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1603): Awaiting to be initialized
W/DriveInitializer( 1603): Background init thread started
E/SQLiteLog( 1603): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 1603): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1603): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1603): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1603): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1603): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1603): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1603): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1603): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1603): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1603): Process: com.google.android.gms, PID: 1603
E/AndroidRuntime( 1603): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1603): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1603): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1603): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 1603): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1603): disk I/O error (code 3850)
E/DriveAsyncService( 1603): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1603): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1603): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1603): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1603): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1603): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1603): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1603): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1603): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1603): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1603): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1603): Sending signal. PID: 1603 SIG: 9
E/DropBoxManagerService(  755): Can't write: system_app_crash
E/DropBoxManagerService(  755): java.io.FileNotFoundException: /data/system/dropbox/drop83.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  755): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  755): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  755): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  755): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  755): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  755): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  755): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  755): 	... 5 more

```
