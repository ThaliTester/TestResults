#### Test 613623665d5a4d6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2437): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2437): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2965): 
D/AndroidRuntime( 2965): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2965): CheckJNI is OFF
D/AndroidRuntime( 2965): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2986 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2965): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 2986): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2986): Time to load native libraries: 2 ms (timestamps 6881-6883)
I/LibraryLoader( 2986): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2986): Binding Chromium to main looper Looper (main, tid 1) {b74313c}
,I/LibraryLoader( 2986): Expected native library version number "",actual native library version number ""
I/chromium( 2986): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2986): Initializing chromium process, singleProcess=true
,W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2986): ApplicationContext is null in ApplicationStatus
,W/chromium( 2986): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2986): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2986): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2986): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2986): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c65240c:true
D/BluetoothAdapter( 2986): 15675969: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2986): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2986): CordovaWebView is running on device made by: LGE
,W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2986): Render dirty regions requested: true
,D/Atlas   ( 2986): Validating map...
,W/chromium( 2986): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2986): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2986): Enabling debug mode 0
,I/Keyboard.Facilitator( 1073): onFinishInput()
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +478ms (total +1m14s651ms)
,W/BindingManager( 2986): Cannot call determinedVisibility() - never saw a connection for the pid: 2986
,W/IInputConnectionWrapper( 2986): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 2986): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2986): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c65788 added. We now have 1 listener(s)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2986): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2d6434 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2986): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  759): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2986): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 2986): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2986): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2986): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2986): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2986): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2986): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2986): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2986): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
,W/System.err( 2986): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
,W/System.err( 2986): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2986): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2986): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2986): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2986): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2986): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b13b25d added. We now have 2 listener(s)
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2986): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a977d2 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2986): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2986): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2986): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2986): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2986): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2986): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2986): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2986): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2986): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2986): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2986): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2986): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2986): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2986): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2986): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2986): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 2986): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2986): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1073): run()
I/Keyboard.Facilitator( 1073): flushDynamicLanguageModels()
,I/ConfigService( 1305): onCreate
,I/ConfigService( 1305): onDestroy
,I/ClearcutLoggerApiImpl( 1305): disconnect managed GoogleApiClient
,I/VacuumService( 1305): Vacuum at: now=1457344347457 tag=VacuumService
,W/ProcessCpuTracker(  759): Skipping unknown process pid 3072
W/ProcessCpuTracker(  759): Skipping unknown process pid 3075
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 2405:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2405/cgroup.procs: No such file or directory
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk,
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1305): disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 3102): 
D/AndroidRuntime( 3102): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3102): CheckJNI is OFF
D/AndroidRuntime( 3102): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2986:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  759): Client connection lost with reason: 4
I/WindowState(  759): WIN DEATH: Window{107fa83c u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  759):   Force finishing activity ActivityRecord{38944a61 u0 com.test.thalitest/.MainActivity t220}
W/PackageSettings(  759): Skipping PackageSetting{34f3bcd3 com.example.hello/10278} due to missing metadata
W/ActivityManager(  759): Spurious death for ProcessRecord{17d3f391 2986:com.test.thalitest/u0a270}, curProc for 2986: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1398): Explicit concurrent mark sweep GC freed 4492(299KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 300us total 20.945ms
I/art     ( 1549): Explicit concurrent mark sweep GC freed 912(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 466us total 34.762ms
I/art     ( 1240): Explicit concurrent mark sweep GC freed 7402(556KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 502us total 23.897ms
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1305): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1073): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1073): run()
I/Decoder ( 1073): createOrResetDecoder
I/art     (  759): Explicit concurrent mark sweep GC freed 17593(1085KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.743ms total 73.263ms
D/VoicemailCleanupService( 1325): Cleaning up data for package: com.test.thalitest
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
I/ConfigService( 1305): onCreate
D/OpenGLRenderer(  944): Enabling debug mode 0
I/UpdateIcingCorporaServi( 1398): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1240): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b74313c new=com.google.android.velvet.VelvetApplication@b74313c
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2986 uid 10270
I/Keyboard.Facilitator( 1073): onFinishInput()
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3145 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  759): removeObsoleteFile: deleting file=220_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1073): run()
W/ContextImpl( 3145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/art     (  759): Explicit concurrent mark sweep GC freed 6472(345KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.337ms total 157.301ms
I/UpdateIcingCorporaServi( 1398): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
D/PackageBroadcastService( 1549): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1549): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1549): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1549): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1073): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = history
D/ChimeraCfgMgr( 1549): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1549): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1073): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1073): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1073): run()
I/StatsUtilsManager( 1073): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1073): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 1305): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1305): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator( 1073): onFinishInput()
I/LocationSettingsChecker( 1549): Removing dialog suppression flag for package com.test.thalitest
W/IInputConnectionWrapper( 1240): showStatusIcon on inactive InputConnection
D/gH_CompatibleDatabase( 1549): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1549): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1549): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1549): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1549): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1549): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1549): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1549): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1549): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1549): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1549): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1549): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1549): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3176 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1240): Deferring update until onResume
D/AndroidRuntime( 3102): Shutting down VM
W/ResourcesManager( 1240): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1549): Using Auth Proxy for data requests.
W/BaseAppContext( 1549): Using Auth Proxy for data requests.
I/GMPM-SVC( 1549): App measurement is starting up, version: 8489
I/GMPM-SVC( 1549): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1240): Deferring update until onResume
I/Icing   ( 1549): doRemovePackageData com.test.thalitest
I/ActivityManager(  759): Killing 1770:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
E/SQLiteLog( 1549): (539) recovered 3 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3204 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1770/cgroup.procs: No such file or directory
D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  759): Killing 2536:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2536/cgroup.procs: No such file or directory
D/ExternalStorage( 3204): After updating volumes, found 1 active roots
W/ResourcesManager( 2678): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2678): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1549): Awaiting to be initialized
W/DriveInitializer( 1549): Background init thread started
D/Documents( 3176): Update found 7 roots in 221ms
D/Documents( 3176): Update found 7 roots in 121ms
E/SQLiteLog( 1549): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1549): Failed to delete from FileContent163 table
E/DocListDatabase( 1549): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1549): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1549): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1549): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1549): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1549): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1549): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1549): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 1549): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 1549): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 1549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1549): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1549): FATAL EXCEPTION: pool-12-thread-1
E/AndroidRuntime( 1549): Process: com.google.android.gms, PID: 1549
E/AndroidRuntime( 1549): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1549): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1549): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1549): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1549): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1549): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1549): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1549): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 1549): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 1549): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 1549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1549): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1549): Sending signal. PID: 1549 SIG: 9
E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
D/ConnectivityService(  759): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1c7dcbaa)
D/ConnectivityService(  759): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  759): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  759): Process com.google.android.gms (pid 1549) has died
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms

```
