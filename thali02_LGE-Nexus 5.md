#### Test 617161634bd7322_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkUtils( 1404): OkHttp exception
W/EventLoggerService( 1404): Unable to send logs Error code: 262146
D/AndroidRuntime( 2905): 
D/AndroidRuntime( 2905): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2905): CheckJNI is OFF
D/AndroidRuntime( 2905): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2925 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2905): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/WebViewFactory( 2925): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2925): Time to load native libraries: 1 ms (timestamps 9268-9269)
I/LibraryLoader( 2925): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2925): Binding Chromium to main looper Looper (main, tid 1) {96e6cc0}
I/LibraryLoader( 2925): Expected native library version number "",actual native library version number ""
I/chromium( 2925): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2925): Initializing chromium process, singleProcess=true
W/art     ( 2925): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2925): ApplicationContext is null in ApplicationStatus
W/chromium( 2925): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2925): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2925): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2925): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2925): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39cb3aad:true
D/BluetoothAdapter( 2925): 1054327483: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2925): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2925): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2925): CordovaWebView is running on device made by: LGE
,W/art     ( 2925): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2925): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2925): Render dirty regions requested: true
,D/Atlas   ( 2925): Validating map...
,W/chromium( 2925): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2925): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2925): Enabling debug mode 0
,W/BindingManager( 2925): Cannot call determinedVisibility() - never saw a connection for the pid: 2925
,W/IInputConnectionWrapper( 2925): showStatusIcon on inactive InputConnection
,I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +414ms (total +1m6s635ms)
,D/JsMessageQueue( 2925): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2925): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c2df94c added. We now have 1 listener(s)
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2925): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2925): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23e75e38 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2925): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  758): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2925): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 2925): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2925): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2925): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2925): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2925): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2925): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2925): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2925): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2925): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2925): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
,W/System.err( 2925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2925): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2925): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2925): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f885e11 added. We now have 2 listener(s)
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2925): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2925): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdf6b76 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2925): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2925): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2925): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2925): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2925): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2925): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2925): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2925): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2925): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2925): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2925): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2925): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2925): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
,W/System.err( 2925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2925): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Finsky  ( 2436): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2436): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/chromium( 2925): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2925): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/art     (  758): Explicit concurrent mark sweep GC freed 19317(904KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.012ms total 91.058ms
,I/ClearcutLoggerApiImpl( 1319): disconnect managed GoogleApiClient
,I/VacuumService( 1319): Vacuum at: now=1457102716393 tag=VacuumService
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  758): Killing 1757:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_1757/cgroup.procs: No such file or directory
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3031): 
D/AndroidRuntime( 3031): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3031): CheckJNI is OFF
D/AndroidRuntime( 3031): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 2925:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  758): WIN DEATH: Window{edd291d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  758): Client connection lost with reason: 4
I/ActivityManager(  758):   Force finishing activity ActivityRecord{30f2757e u0 com.test.thalitest/.MainActivity t220}
W/PackageSettings(  758): Skipping PackageSetting{2f19aa7 com.example.hello/10278} due to missing metadata
W/ActivityManager(  758): Spurious death for ProcessRecord{2c11dc6d 2925:com.test.thalitest/u0a270}, curProc for 2925: null
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1554): Explicit concurrent mark sweep GC freed 889(37KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 21MB/29MB, paused 379us total 24.691ms
I/art     ( 1251): Explicit concurrent mark sweep GC freed 7325(552KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 765us total 16.684ms
I/art     ( 1404): Explicit concurrent mark sweep GC freed 3286(200KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 646us total 50.223ms
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1319): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1078): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1078): run()
I/Decoder ( 1078): createOrResetDecoder
I/UpdateIcingCorporaServi( 1404): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/VoicemailCleanupService( 2607): Cleaning up data for package: com.test.thalitest
W/Launcher( 1251): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@96e6cc0 new=com.google.android.velvet.VelvetApplication@96e6cc0
I/art     (  758): Explicit concurrent mark sweep GC freed 13336(885KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.279ms total 85.106ms
I/art     (  758): WaitForGcToComplete blocked for 63.234ms for cause Explicit
I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  949): Initialized EGL, version 1.4
I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3069 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/OpenGLRenderer(  949): Enabling debug mode 0
I/ConfigService( 1319): onCreate
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ContextImpl( 3069): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): run()
D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
D/PackageBroadcastService( 1554): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1554): Clearing selected account for com.test.thalitest
D/TaskPersister(  758): removeObsoleteFile: deleting file=220_task.xml
D/ChimeraCfgMgr( 1554): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1554): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/UpdateIcingCorporaServi( 1404): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
D/ChimeraCfgMgr( 1554): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1554): Module APK com.google.android.play.games already loaded
W/InputMethodManagerService(  758): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@329830dc (uid=10034 pid=949)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = contacts
I/LocationSettingsChecker( 1554): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1319): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1319): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1078): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1078): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1078): run()
I/StatsUtilsManager( 1078): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1078): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1554): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1554): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1554): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1554): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1554): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1554): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1554): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  758): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3104 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1554): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1554): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1554): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1554): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1554): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1554): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/art     (  758): Explicit concurrent mark sweep GC freed 7991(386KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.699ms total 196.489ms
W/BaseAppContext( 1554): Using Auth Proxy for data requests.
W/BaseAppContext( 1554): Using Auth Proxy for data requests.
I/GMPM-SVC( 1554): App measurement is starting up, version: 8489
I/GMPM-SVC( 1554): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Launcher( 1251): Deferring update until onResume
D/ConnectivityService(  758): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 1251): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Icing   ( 1554): doRemovePackageData com.test.thalitest
W/ResourcesManager( 1251): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1251): Deferring update until onResume
D/AndroidRuntime( 3031): Shutting down VM
I/ActivityManager(  758): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3131 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  758): Killing 2499:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2499/cgroup.procs: No such file or directory
I/ActivityManager(  758): Killing 2362:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3131): After updating volumes, found 1 active roots
W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2362/cgroup.procs: No such file or directory
W/DriveInitializer( 1554): Awaiting to be initialized
W/DriveInitializer( 1554): Background init thread started
W/DriveInitializer( 1554): Background init thread ended
W/ResourcesManager( 2665): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2665): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3104): Update found 7 roots in 224ms
D/Documents( 3104): Update found 7 roots in 168ms

```
