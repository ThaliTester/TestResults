#### Test 6216742584ac8ae_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2445): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2445): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2909): 
D/AndroidRuntime( 2909): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2909): CheckJNI is OFF
D/AndroidRuntime( 2909): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2930 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2909): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 2930): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2930): Time to load native libraries: 2 ms (timestamps 7770-7772)
I/LibraryLoader( 2930): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2930): Binding Chromium to main looper Looper (main, tid 1) {32daa034}
I/LibraryLoader( 2930): Expected native library version number "",actual native library version number ""
I/chromium( 2930): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2930): Initializing chromium process, singleProcess=true
W/art     ( 2930): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2930): ApplicationContext is null in ApplicationStatus
W/chromium( 2930): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2930): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2930): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2930): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2930): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1282f0f8:true
,D/BluetoothAdapter( 2930): 233216798: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2930): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2930): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2930): CordovaWebView is running on device made by: LGE
,W/art     ( 2930): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2930): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2930): Render dirty regions requested: true
,D/Atlas   ( 2930): Validating map...
,W/chromium( 2930): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2930): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2930): Enabling debug mode 0
,I/Keyboard.Facilitator( 1075): onFinishInput()
,W/IInputConnectionWrapper( 2930): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +426ms (total +1m15s775ms)
,W/BindingManager( 2930): Cannot call determinedVisibility() - never saw a connection for the pid: 2930
,D/JsMessageQueue( 2930): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2930): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15355a00 added. We now have 1 listener(s)
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2930): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2930): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1296162c added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2930): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  756): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 2930): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2930): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2930): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2930): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2930): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2930): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2930): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2930): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2930): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2930): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2930): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2930): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2930): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2930): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2930): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b108f5 added. We now have 2 listener(s)
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2930): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2930): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c99a68a added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2930): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2930): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2930): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2930): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2930): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2930): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2930): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2930): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2930): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2930): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2930): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2930): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2930): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2930): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2930): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 2930): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2930): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1075): run()
I/Keyboard.Facilitator( 1075): flushDynamicLanguageModels()
,I/ConfigService( 1275): onCreate
,I/ConfigService( 1275): onDestroy
,I/ClearcutLoggerApiImpl( 1275): disconnect managed GoogleApiClient
,I/VacuumService( 1275): Vacuum at: now=1457489175678 tag=VacuumService
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1275): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3026): 
D/AndroidRuntime( 3026): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3026): CheckJNI is OFF
D/AndroidRuntime( 3026): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 2930:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  756): WIN DEATH: Window{f108828 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  756): Client connection lost with reason: 4
W/PackageSettings(  756): Skipping PackageSetting{3446df2b com.example.hello/10278} due to missing metadata
I/ActivityManager(  756):   Force finishing activity ActivityRecord{17f8b79d u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  756): Spurious death for ProcessRecord{c3deef6 2930:com.test.thalitest/u0a270}, curProc for 2930: null
I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1310): Explicit concurrent mark sweep GC freed 7357(554KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.838ms total 19.306ms
I/art     ( 1553): Explicit concurrent mark sweep GC freed 958(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 446us total 56.099ms
I/art     ( 1338): Explicit concurrent mark sweep GC freed 6080(412KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 289us total 36.860ms
I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1275): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1365): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1075): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1075): run()
I/UpdateIcingCorporaServi( 1338): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Decoder ( 1075): createOrResetDecoder
I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  945): Initialized EGL, version 1.4
I/art     (  756): Explicit concurrent mark sweep GC freed 17516(1082KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 2.482ms total 87.695ms
I/art     (  756): WaitForGcToComplete blocked for 71.520ms for cause Explicit
W/Launcher( 1310): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32daa034 new=com.google.android.velvet.VelvetApplication@32daa034
D/OpenGLRenderer(  945): Enabling debug mode 0
I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3068 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ConfigService( 1275): onCreate
D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  756): removeObsoleteFile: deleting file=220_task.xml
W/InputMethodManagerService(  756): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@6bedeb7 (uid=10034 pid=945)
I/art     (  756): Explicit concurrent mark sweep GC freed 3820(179KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.385ms total 114.927ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): run()
W/ContextImpl( 3068): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1338): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
D/PackageBroadcastService( 1553): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1553): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1553): Module APK com.google.android.play.games already loaded
W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 2930 uid 10270
D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1553): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator( 1075): onFinishInput()
I/LocationSettingsChecker( 1553): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1275): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1275): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1075): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1075): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1075): run()
I/StatsUtilsManager( 1075): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1075): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1553): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3100 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/AndroidRuntime( 3026): Shutting down VM
I/Launcher( 1310): Deferring update until onResume
W/BaseAppContext( 1553): Using Auth Proxy for data requests.
W/BaseAppContext( 1553): Using Auth Proxy for data requests.
W/ResourcesManager( 1310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GMPM-SVC( 1553): App measurement is starting up, version: 8489
I/GMPM-SVC( 1553): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 1553): doRemovePackageData com.test.thalitest
I/Launcher( 1310): Deferring update until onResume
I/ActivityManager(  756): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3125 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  756): Killing 1803:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_1803/cgroup.procs: No such file or directory
I/ActivityManager(  756): Killing 2512:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
D/ExternalStorage( 3125): After updating volumes, found 1 active roots
W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2512/cgroup.procs: No such file or directory
D/ConnectivityService(  756): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
