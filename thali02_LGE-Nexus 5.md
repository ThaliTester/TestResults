#### Test 6012434713fea37_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1380): OkHttp exception
W/EventLoggerService( 1380): Unable to send logs Error code: 262146
V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1341): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1380): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2447): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2447): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/Auth    ( 1341): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1380): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/AndroidRuntime( 2983): 
D/AndroidRuntime( 2983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2983): CheckJNI is OFF
D/AndroidRuntime( 2983): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3008 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2983): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 3008): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3008): Time to load native libraries: 2 ms (timestamps 2183-2185)
I/LibraryLoader( 3008): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3008): Binding Chromium to main looper Looper (main, tid 1) {1ad0c0a9}
,I/LibraryLoader( 3008): Expected native library version number "",actual native library version number ""
,I/chromium( 3008): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3008): Initializing chromium process, singleProcess=true
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3008): ApplicationContext is null in ApplicationStatus
,W/chromium( 3008): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3008): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3008): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39897883:true
,D/BluetoothAdapter( 3008): 691335496: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3008): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3008): CordovaWebView is running on device made by: LGE
,W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3008): Render dirty regions requested: true
,D/Atlas   ( 3008): Validating map...
,W/chromium( 3008): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  756): Explicit concurrent mark sweep GC freed 19214(883KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.466ms total 60.318ms
,I/OpenGLRenderer( 3008): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3008): Enabling debug mode 0
,W/BindingManager( 3008): Cannot call determinedVisibility() - never saw a connection for the pid: 3008
,W/IInputConnectionWrapper( 3008): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +540ms (total +1m10s931ms)
,D/JsMessageQueue( 3008): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3008): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258380416
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11dc5345 added. We now have 1 listener(s)
D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): setBluetoothMacAddress: 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3008): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3008): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf3dec1 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3008): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  756): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3008): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3008): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3008): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3008): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3008): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3008): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3008): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3008): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3008): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3008): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3008): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3008): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 3008): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3008): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3008): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfad666 added. We now have 2 listener(s)
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3008): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3008): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30048da7 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3008): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3008): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3008): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3008): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 3008): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3008): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3008): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3008): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3008): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3008): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3008): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3008): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
,W/System.err( 3008): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3008): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3008): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3008): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3008): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/ClearcutLoggerApiImpl( 1341): disconnect managed GoogleApiClient
,I/VacuumService( 1341): Vacuum at: now=1457574348616 tag=VacuumService
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Killing 1762:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_1762/cgroup.procs: No such file or directory
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3110): 
D/AndroidRuntime( 3110): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3110): CheckJNI is OFF
D/AndroidRuntime( 3110): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 3008:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  756): Client connection lost with reason: 4
I/WindowState(  756): WIN DEATH: Window{8898873 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  756): Skipping PackageSetting{208033c4 com.example.hello/10278} due to missing metadata
I/ActivityManager(  756):   Force finishing activity ActivityRecord{269545fc u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  756): Spurious death for ProcessRecord{2d74a1f2 3008:com.test.thalitest/u0a270}, curProc for 3008: null
I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  756):   Force finishing activity ActivityRecord{269545fc u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  756): Duplicate finish request for ActivityRecord{269545fc u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1560): Explicit concurrent mark sweep GC freed 912(37KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 21MB/29MB, paused 373us total 25.523ms
I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1086): resetDictionaries() : en_US
W/GeofencerStateMachine( 1341): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1086): run()
I/Decoder ( 1086): createOrResetDecoder
I/art     ( 1305): Explicit concurrent mark sweep GC freed 7312(552KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 500us total 53.004ms
I/art     ( 1380): Explicit concurrent mark sweep GC freed 5746(372KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 337us total 95.942ms
D/VoicemailCleanupService( 2666): Cleaning up data for package: com.test.thalitest
I/art     (  756): Explicit concurrent mark sweep GC freed 12889(878KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.617ms total 74.895ms
I/art     (  756): WaitForGcToComplete blocked for 9.595ms for cause Explicit
I/Adreno-EGL(  940): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  940): Initialized EGL, version 1.4
I/UpdateIcingCorporaServi( 1380): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1305): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ad0c0a9 new=com.google.android.velvet.VelvetApplication@1ad0c0a9
D/OpenGLRenderer(  940): Enabling debug mode 0
W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 3008 uid 10270
I/Keyboard.Facilitator( 1086): onFinishInput()
I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3150 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
I/ConfigService( 1341): onCreate
D/TaskPersister(  756): removeObsoleteFile: deleting file=220_task.xml
I/UpdateIcingCorporaServi( 1380): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1086): run()
W/ContextImpl( 3150): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1560): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1560): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1086): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1086): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1086): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1086): run()
I/StatsUtilsManager( 1086): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1086): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 1341): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1341): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1560): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1560): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/art     (  756): Explicit concurrent mark sweep GC freed 7450(361KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.743ms total 221.280ms
D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1560): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3184 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1305): Deferring update until onResume
I/GMPM-SVC( 1560): App measurement is starting up, version: 8489
I/GMPM-SVC( 1560): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1560): Using Auth Proxy for data requests.
W/BaseAppContext( 1560): Using Auth Proxy for data requests.
D/AndroidRuntime( 3110): Shutting down VM
W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 1560): doRemovePackageData com.test.thalitest
I/Launcher( 1305): Deferring update until onResume
I/ActivityManager(  756): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3210 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  756): Killing 2515:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2515/cgroup.procs: No such file or directory
I/ActivityManager(  756): Killing 2380:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3210): After updating volumes, found 1 active roots
W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2380/cgroup.procs: No such file or directory
D/ConnectivityService(  756): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 2721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1560): Awaiting to be initialized
W/DriveInitializer( 1560): Background init thread started
E/SQLiteLog( 1560): (778) statement aborts at 2: [DELETE FROM ContentFileDeletionLock163] 
E/DocListDatabase( 1560): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1560): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1560): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1560): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1560): Process: com.google.android.gms, PID: 1560
E/AndroidRuntime( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1560): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1560): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 1560): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1560): disk I/O error (code 3850)
E/DriveAsyncService( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1560): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1560): Sending signal. PID: 1560 SIG: 9
E/DropBoxManagerService(  756): Can't write: system_app_crash
E/DropBoxManagerService(  756): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  756): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  756): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  756): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  756): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  756): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  756): 	... 5 more
D/Documents( 3184): Update found 7 roots in 311ms
D/ConnectivityService(  756): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@fa53f72)
D/ConnectivityService(  756): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  756): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Documents( 3184): Update found 7 roots in 205ms
I/ActivityManager(  756): Process com.google.android.gms (pid 1560) has died
W/ActivityManager(  756): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  756): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  756): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  756): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  756): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms

```
