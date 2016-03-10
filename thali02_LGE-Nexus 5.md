#### Test 61362366b6c9a6f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkUtils( 1334): OkHttp exception
W/EventLoggerService( 1334): Unable to send logs Error code: 262146
E/Auth    ( 1276): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1334): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1276): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1334): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/Finsky  ( 2461): [236] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2461): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2956): 
D/AndroidRuntime( 2956): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2956): CheckJNI is OFF
D/AndroidRuntime( 2956): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2978 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2956): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 2978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2978): Time to load native libraries: 2 ms (timestamps 2183-2185)
I/LibraryLoader( 2978): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2978): Binding Chromium to main looper Looper (main, tid 1) {3d11b369}
I/LibraryLoader( 2978): Expected native library version number "",actual native library version number ""
I/chromium( 2978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2978): Initializing chromium process, singleProcess=true
W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2978): ApplicationContext is null in ApplicationStatus
,W/chromium( 2978): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2978): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32a33884:true
,D/BluetoothAdapter( 2978): 224452346: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2978): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2978): CordovaWebView is running on device made by: LGE
,W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2978): Render dirty regions requested: true
,D/Atlas   ( 2978): Validating map...
,W/chromium( 2978): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2978): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2978): Enabling debug mode 0
,W/IInputConnectionWrapper( 2978): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1066): onFinishInput()
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +455ms (total +1m9s515ms)
,W/BindingManager( 2978): Cannot call determinedVisibility() - never saw a connection for the pid: 2978
,D/JsMessageQueue( 2978): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2978): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31b01205 added. We now have 1 listener(s)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2978): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2978): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e24c981 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2978): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  761): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2978): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2978): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2978): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2978): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2978): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2978): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2978): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2978): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2978): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2978): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2978): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2978): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2978): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2978): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2978): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d54a26 added. We now have 2 listener(s)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2978): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2978): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc5667 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2978): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2978): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2978): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2978): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2978): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2978): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2978): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2978): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2978): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2978): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2978): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2978): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2978): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2978): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2978): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 2978): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2978): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1066): run()
I/Keyboard.Facilitator( 1066): flushDynamicLanguageModels()
,I/ConfigService( 1276): onCreate
,I/ConfigService( 1276): onDestroy
,I/VacuumService( 1276): Vacuum at: now=1457599116217 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1276): disconnect managed GoogleApiClient
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1770:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1770/cgroup.procs: No such file or directory
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1276): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 3092): 
D/AndroidRuntime( 3092): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3092): CheckJNI is OFF
D/AndroidRuntime( 3092): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2978:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{3b07cab4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{e995d84 com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{32a514f9 u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  761): Spurious death for ProcessRecord{3d59cb62 2978:com.test.thalitest/u0a270}, curProc for 2978: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{32a514f9 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{32a514f9 u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1556): Explicit concurrent mark sweep GC freed 901(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 370us total 25.321ms
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1276): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1066): resetDictionaries() : en_US
I/art     ( 1247): Explicit concurrent mark sweep GC freed 7354(554KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 705us total 44.176ms
I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  950): Initialized EGL, version 1.4
D/VoicemailCleanupService( 2626): Cleaning up data for package: com.test.thalitest
I/art     ( 1334): Explicit concurrent mark sweep GC freed 6083(415KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 289us total 37.879ms
I/Keyboard.Facilitator.DecoderInitializer( 1066): run()
I/Decoder ( 1066): createOrResetDecoder
W/Launcher( 1247): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d11b369 new=com.google.android.velvet.VelvetApplication@3d11b369
I/UpdateIcingCorporaServi( 1334): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/OpenGLRenderer(  950): Enabling debug mode 0
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3133 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  761): Explicit concurrent mark sweep GC freed 23360(1342KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.326ms total 130.363ms
I/art     (  761): WaitForGcToComplete blocked for 95.451ms for cause Explicit
I/ConfigService( 1276): onCreate
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2978 uid 10270
I/CheckinRequestBuilder( 1276): Classify the device as Phone.
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=220_task.xml
W/FetchTask( 1276): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/UpdateIcingCorporaServi( 1334): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
W/ContextImpl( 3133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator( 1066): onFinishInput()
D/PackageBroadcastService( 1556): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1556): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1556): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1556): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator( 1066): onFinishInput()
I/CheckinRequestBuilder( 1276): Classify the device as Phone.
W/FetchTask( 1276): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/LocationSettingsChecker( 1556): Removing dialog suppression flag for package com.test.thalitest
W/IInputConnectionWrapper( 1247): showStatusIcon on inactive InputConnection
D/ChimeraCfgMgr( 1556): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1556): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1276): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1276): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/CheckinRequestBuilder( 1276): Classify the device as Phone.
W/FetchTask( 1276): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/art     (  761): Explicit concurrent mark sweep GC freed 8328(404KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.950ms total 172.059ms
D/gH_MetricsDatabase( 1556): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/CheckinRequestBuilder( 1276): Classify the device as Phone.
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3178 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/FetchTask( 1276): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Launcher( 1247): Deferring update until onResume
I/GMPM-SVC( 1556): App measurement is starting up, version: 8489
I/GMPM-SVC( 1556): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1556): Using Auth Proxy for data requests.
W/ResourcesManager( 1247): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1556): Using Auth Proxy for data requests.
D/AndroidRuntime( 3092): Shutting down VM
I/CheckinRequestBuilder( 1276): Classify the device as Phone.
W/FetchTask( 1276): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 1247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 1556): doRemovePackageData com.test.thalitest
I/Launcher( 1247): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1066): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1066): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1066): run()
I/StatsUtilsManager( 1066): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1066): shouldRecordStats() = Too Soon
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3207 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2525:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
I/ActivityManager(  761): Killing 1450:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2525/cgroup.procs: No such file or directory
W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1450/cgroup.procs: No such file or directory
W/DriveInitializer( 1556): Awaiting to be initialized
D/ExternalStorage( 3207): After updating volumes, found 1 active roots
W/DriveInitializer( 1556): Background init thread started
E/SQLiteLog( 1556): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 1556): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1556): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1556): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1556): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1556): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1556): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1556): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1556): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1556): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1556): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 1556): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1556): disk I/O error (code 3850)
E/DriveAsyncService( 1556): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1556): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1556): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1556): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1556): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1556): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1556): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1556): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1556): 	at java.lang.Thread.run(Thread.java:818)
W/DriveInitializer( 1556): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1556): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1556): Process: com.google.android.gms, PID: 1556
E/AndroidRuntime( 1556): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1556): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1556): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1556): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1556): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1556): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1556): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1556): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1556): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 1556): Sending signal. PID: 1556 SIG: 9
D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b6aeac4)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Process com.google.android.gms (pid 1556) has died
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ResourcesManager( 2692): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
