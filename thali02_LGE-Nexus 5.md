#### Test 6012434797f7ca7_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1310): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/NetworkUtils( 1352): OkHttp exception
W/EventLoggerService( 1352): Unable to send logs Error code: 262146
W/Search.LoginHelper( 1352): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1310): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1352): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/AndroidRuntime( 2951): 
D/AndroidRuntime( 2951): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2951): CheckJNI is OFF
D/AndroidRuntime( 2951): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2973 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2951): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 2973): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2973): Time to load native libraries: 1 ms (timestamps 884-885)
I/LibraryLoader( 2973): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2973): Binding Chromium to main looper Looper (main, tid 1) {219136fa}
I/LibraryLoader( 2973): Expected native library version number "",actual native library version number ""
I/chromium( 2973): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2973): Initializing chromium process, singleProcess=true
W/art     ( 2973): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2973): ApplicationContext is null in ApplicationStatus
,W/chromium( 2973): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2973): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2973): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2973): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2973): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2b3faf:true
D/BluetoothAdapter( 2973): 288082118: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2973): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2973): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2973): CordovaWebView is running on device made by: LGE
,W/art     ( 2973): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2973): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2973): Render dirty regions requested: true
,D/Atlas   ( 2973): Validating map...
,W/chromium( 2973): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2973): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2973): Enabling debug mode 0
,I/Keyboard.Facilitator( 1067): onFinishInput()
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +438ms (total +1m8s173ms)
,W/IInputConnectionWrapper( 2973): showStatusIcon on inactive InputConnection
,W/BindingManager( 2973): Cannot call determinedVisibility() - never saw a connection for the pid: 2973
,D/JsMessageQueue( 2973): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2973): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258380416
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f2226 added. We now have 1 listener(s)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2973): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2973): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dab3ab2 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2973): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  759): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2973): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2973): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2973): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2973): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2973): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2973): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2973): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2973): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2973): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2973): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2973): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2973): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2973): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2973): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25766a03 added. We now have 2 listener(s)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2973): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2973): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90a3d80 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2973): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2973): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2973): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2973): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2973): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2973): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2973): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2973): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2973): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2973): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2973): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2973): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2973): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2973): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Finsky  ( 2486): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2486): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/chromium( 2973): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2973): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/art     (  759): Explicit concurrent mark sweep GC freed 20780(973KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.042ms total 104.175ms
,I/Keyboard.Facilitator.LanguageModelFlusher( 1067): run()
I/Keyboard.Facilitator( 1067): flushDynamicLanguageModels()
,I/ConfigService( 1310): onCreate
,I/ConfigService( 1310): onDestroy
,I/ClearcutLoggerApiImpl( 1310): disconnect managed GoogleApiClient
,I/VacuumService( 1310): Vacuum at: now=1457379014860 tag=VacuumService
,I/EventLogService( 1559): Aggregate from 1457377312164 (log), 1457377312164 (data)
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 1773:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1773/cgroup.procs: No such file or directory
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3088): 
D/AndroidRuntime( 3088): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3088): CheckJNI is OFF
D/AndroidRuntime( 3088): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2973:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  759): Client connection lost with reason: 4
I/WindowState(  759): WIN DEATH: Window{10b1729f u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  759): Skipping PackageSetting{15263769 com.example.hello/10278} due to missing metadata
I/ActivityManager(  759):   Force finishing activity ActivityRecord{1f578478 u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  759): Spurious death for ProcessRecord{1953e126 2973:com.test.thalitest/u0a270}, curProc for 2973: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  759):   Force finishing activity ActivityRecord{1f578478 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  759): Duplicate finish request for ActivityRecord{1f578478 u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1352): Explicit concurrent mark sweep GC freed 5577(367KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 302us total 18.752ms
I/art     ( 1242): Explicit concurrent mark sweep GC freed 7376(555KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 231us total 28.546ms
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1310): Ignoring removeGeofence because network location is disabled.
I/art     ( 1559): Explicit concurrent mark sweep GC freed 2512(168KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 21MB/29MB, paused 368us total 46.339ms
I/Keyboard.Facilitator( 1067): resetDictionaries() : en_US
D/VoicemailCleanupService( 2659): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1067): run()
I/Decoder ( 1067): createOrResetDecoder
I/UpdateIcingCorporaServi( 1352): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1242): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@219136fa new=com.google.android.velvet.VelvetApplication@219136fa
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
I/art     (  759): Explicit concurrent mark sweep GC freed 14112(949KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 9.481ms total 88.008ms
I/art     (  759): WaitForGcToComplete blocked for 63.505ms for cause Explicit
D/OpenGLRenderer(  946): Enabling debug mode 0
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3127 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ConfigService( 1310): onCreate
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): run()
D/TaskPersister(  759): removeObsoleteFile: deleting file=220_task.xml
W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1de223e6 (uid=10034 pid=946)
W/ContextImpl( 3127): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1067): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1067): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1067): run()
I/StatsUtilsManager( 1067): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1067): shouldRecordStats() = Too Soon
D/PackageBroadcastService( 1559): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1559): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1559): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1559): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1352): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
D/ChimeraCfgMgr( 1559): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1559): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1310): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1310): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1559): Removing dialog suppression flag for package com.test.thalitest
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2973 uid 10270
I/Keyboard.Facilitator( 1067): onFinishInput()
I/art     (  759): Explicit concurrent mark sweep GC freed 6152(309KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.971ms total 165.767ms
D/gH_CompatibleDatabase( 1559): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1559): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1559): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1559): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1559): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1559): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1559): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1559): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1559): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1559): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1559): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1559): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1559): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3162 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1242): Deferring update until onResume
D/AndroidRuntime( 3088): Shutting down VM
W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1559): Using Auth Proxy for data requests.
W/BaseAppContext( 1559): Using Auth Proxy for data requests.
I/GMPM-SVC( 1559): App measurement is starting up, version: 8489
I/GMPM-SVC( 1559): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1242): Deferring update until onResume
I/Icing   ( 1559): doRemovePackageData com.test.thalitest
I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3186 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  759): Killing 2548:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2548/cgroup.procs: No such file or directory
I/ActivityManager(  759): Killing 2410:com.google.android.gm/u0a70 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2410/cgroup.procs: No such file or directory
D/ExternalStorage( 3186): After updating volumes, found 1 active roots
D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 2713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1559): Awaiting to be initialized
W/DriveInitializer( 1559): Background init thread started
E/SQLiteLog( 1559): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1559): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 1559): Background init thread ended
E/DriveAsyncService( 1559): disk I/O error (code 3850)
E/DriveAsyncService( 1559): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1559): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1559): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1559): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1559): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1559): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1559): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1559): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1559): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1559): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1559): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1559): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1559): Process: com.google.android.gms, PID: 1559
E/AndroidRuntime( 1559): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1559): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.database.f.e(SourceFile:858)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.events.av.b(SourceFile:192)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.events.av.a(SourceFile:158)
E/AndroidRuntime( 1559): 	at com.google.android.gms.drive.t.run(SourceFile:65)
I/Process ( 1559): Sending signal. PID: 1559 SIG: 9
E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  759): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  759): 	... 5 more
D/Documents( 3162): Update found 7 roots in 296ms
D/ConnectivityService(  759): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@104f370b)
D/ConnectivityService(  759): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  759): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  759): Process com.google.android.gms (pid 1559) has died
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
D/Documents( 3162): Update found 7 roots in 219ms

```
