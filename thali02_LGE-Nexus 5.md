#### Test 6012434764ab483_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkUtils( 1350): OkHttp exception
,W/EventLoggerService( 1350): Unable to send logs Error code: 262146
V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1315): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1350): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1315): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1350): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/Finsky  ( 2468): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2468): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2981): 
D/AndroidRuntime( 2981): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2981): CheckJNI is OFF
D/AndroidRuntime( 2981): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2995 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2981): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 2995): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2995): Time to load native libraries: 5 ms (timestamps 2299-2304)
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2995): Binding Chromium to main looper Looper (main, tid 1) {c7d0419}
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
I/chromium( 2995): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2995): Initializing chromium process, singleProcess=true
W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2995): ApplicationContext is null in ApplicationStatus
,W/chromium( 2995): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2995): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2995): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37b32765:true
,D/BluetoothAdapter( 2995): 27234936: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2995): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2995): CordovaWebView is running on device made by: LGE
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2995): Render dirty regions requested: true
,D/Atlas   ( 2995): Validating map...
,W/chromium( 2995): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2995): Initialized EGL, version 1.4
D/OpenGLRenderer( 2995): Enabling debug mode 0
,I/Keyboard.Facilitator( 1061): onFinishInput()
,W/IInputConnectionWrapper( 2995): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +484ms (total +1m10s277ms)
,W/BindingManager( 2995): Cannot call determinedVisibility() - never saw a connection for the pid: 2995
,D/JsMessageQueue( 2995): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2995): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd755b5 added. We now have 1 listener(s)
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2995): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2995): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f749831 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2995): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 2995): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 2995): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2995): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2995): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2995): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2995): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2995): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2995): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 2995): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2995): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2995): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2995): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2995): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2995): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2995): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e9eb16 added. We now have 2 listener(s)
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2995): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2995): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f3dfc97 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2995): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2995): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2995): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2995): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2995): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2995): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2995): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2995): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2995): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2995): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2995): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2995): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2995): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2995): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2995): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     (  760): Explicit concurrent mark sweep GC freed 19696(903KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 916us total 69.265ms
D/WifiService(  760): New client listening to asynchronous messages
,I/chromium( 2995): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2995): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1061): run(),
I/Keyboard.Facilitator( 1061): flushDynamicLanguageModels()
,I/ConfigService( 1315): onCreate
,I/ConfigService( 1315): onDestroy
,I/ClearcutLoggerApiImpl( 1315): disconnect managed GoogleApiClient
,I/VacuumService( 1315): Vacuum at: now=1457487549149 tag=VacuumService
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 1773:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1773/cgroup.procs: No such file or directory
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3090): 
D/AndroidRuntime( 3090): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3090): CheckJNI is OFF
D/AndroidRuntime( 3090): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2995:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  760): WIN DEATH: Window{1855b3d5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  760): Client connection lost with reason: 4
W/PackageSettings(  760): Skipping PackageSetting{b844bf4 com.example.hello/10278} due to missing metadata
I/ActivityManager(  760):   Force finishing activity ActivityRecord{36f17756 u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  760): Spurious death for ProcessRecord{298a10ab 2995:com.test.thalitest/u0a270}, curProc for 2995: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{36f17756 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{36f17756 u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1350): Explicit concurrent mark sweep GC freed 5216(352KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 320us total 19.416ms
W/GeofencerStateMachine( 1315): Ignoring removeGeofence because network location is disabled.
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1253): Explicit concurrent mark sweep GC freed 7339(553KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 223us total 41.753ms
I/Keyboard.Facilitator( 1061): resetDictionaries() : en_US
I/art     (  760): Explicit concurrent mark sweep GC freed 13337(906KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.387ms total 62.930ms
I/Keyboard.Facilitator.DecoderInitializer( 1061): run()
I/Decoder ( 1061): createOrResetDecoder
I/art     ( 1550): Explicit concurrent mark sweep GC freed 972(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 21MB/29MB, paused 359us total 43.901ms
I/ConfigService( 1315): onCreate
I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
D/OpenGLRenderer(  943): Enabling debug mode 0
D/VoicemailCleanupService( 2655): Cleaning up data for package: com.test.thalitest
I/UpdateIcingCorporaServi( 1350): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
W/Launcher( 1253): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@c7d0419 new=com.google.android.velvet.VelvetApplication@c7d0419
W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2995 uid 10270
I/Keyboard.Facilitator( 1061): onFinishInput()
I/CheckinRequestBuilder( 1315): Classify the device as Phone.
I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3133 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  760): removeObsoleteFile: deleting file=220_task.xml
I/art     (  760): Explicit concurrent mark sweep GC freed 5221(275KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.690ms total 115.800ms
W/FetchTask( 1315): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1315): Classify the device as Phone.
W/FetchTask( 1315): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ContextImpl( 3133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1350): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
D/PackageBroadcastService( 1550): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1550): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1550): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1550): Module APK com.google.android.play.games already loaded
I/CheckinRequestBuilder( 1315): Classify the device as Phone.
W/FetchTask( 1315): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ChimeraCfgMgr( 1550): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1550): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1550): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator( 1061): onFinishInput()
E/NetworkScheduler.SchedulerReceiver( 1315): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1315): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/IInputConnectionWrapper( 1253): showStatusIcon on inactive InputConnection
I/CheckinRequestBuilder( 1315): Classify the device as Phone.
W/FetchTask( 1315): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1550): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1550): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1550): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1550): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1550): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1550): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1550): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1061): run()
D/gH_CompatibleDatabase( 1550): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1550): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1550): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1550): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1550): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1550): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 3090): Shutting down VM
I/Keyboard.Facilitator.MainLanguageModelLoader( 1061): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1061): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1061): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1061): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1061): run()
I/StatsUtilsManager( 1061): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1061): shouldRecordStats() = Too Soon
I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3173 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1253): Deferring update until onResume
W/BaseAppContext( 1550): Using Auth Proxy for data requests.
W/BaseAppContext( 1550): Using Auth Proxy for data requests.
W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1253): Deferring update until onResume
D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/GMPM-SVC( 1550): App measurement is starting up, version: 8489
I/GMPM-SVC( 1550): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3194 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/Icing   ( 1550): doRemovePackageData com.test.thalitest
I/ActivityManager(  760): Killing 2536:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2536/cgroup.procs: No such file or directory
D/ExternalStorage( 3194): After updating volumes, found 1 active roots
W/DriveInitializer( 1550): Awaiting to be initialized
W/DriveInitializer( 1550): Background init thread started
I/ActivityManager(  760): Killing 2407:com.google.android.gm/u0a70 (adj 15): empty #17
W/ResourcesManager( 2709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2407/cgroup.procs: No such file or directory
D/Documents( 3173): Update found 7 roots in 237ms
D/Documents( 3173): Update found 7 roots in 111ms
E/SQLiteLog( 1550): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 1550): Background init thread ended
E/DriveAsyncService( 1550): disk I/O error (code 3850)
E/DriveAsyncService( 1550): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1550): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1550): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1550): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1550): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1550): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1550): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1550): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1550): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1550): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1550): 	at java.lang.Thread.run(Thread.java:818)

```
