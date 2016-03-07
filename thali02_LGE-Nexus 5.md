#### Test 61362366345141a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1337): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/NetworkUtils( 1383): OkHttp exception
W/EventLoggerService( 1383): Unable to send logs Error code: 262146
W/Search.LoginHelper( 1383): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1337): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1383): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/Finsky  ( 2439): [236] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2439): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2953): 
D/AndroidRuntime( 2953): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2953): CheckJNI is OFF
D/AndroidRuntime( 2953): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2978 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2953): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
,I/WebViewFactory( 2978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2978): Time to load native libraries: 2 ms (timestamps 7104-7106)
,I/LibraryLoader( 2978): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2978): Binding Chromium to main looper Looper (main, tid 1) {1310f1b4}
,I/LibraryLoader( 2978): Expected native library version number "",actual native library version number ""
I/chromium( 2978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2978): Initializing chromium process, singleProcess=true
,W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2978): ApplicationContext is null in ApplicationStatus
,W/chromium( 2978): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2978): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38790a78:true
,D/BluetoothAdapter( 2978): 577659038: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2978): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2978): CordovaWebView is running on device made by: LGE
,W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2978): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2978): Render dirty regions requested: true
,D/Atlas   ( 2978): Validating map...
,I/art     (  761): Explicit concurrent mark sweep GC freed 20189(925KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 916us total 53.877ms
,W/chromium( 2978): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2978): Initialized EGL, version 1.4
D/OpenGLRenderer( 2978): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +557ms (total +1m5s199ms)
,W/IInputConnectionWrapper( 2978): showStatusIcon on inactive InputConnection
,W/BindingManager( 2978): Cannot call determinedVisibility() - never saw a connection for the pid: 2978
,D/JsMessageQueue( 2978): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2978): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14720380 added. We now have 1 listener(s)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3d7ac added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2978): addListener: New listener added - the number of listeners is now 1
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
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31516c75 added. We now have 2 listener(s)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2978): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2978): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2978): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2635040a added. We now have 2 listener(s)
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
,I/ClearcutLoggerApiImpl( 1337): disconnect managed GoogleApiClient
,I/VacuumService( 1337): Vacuum at: now=1457361553527 tag=VacuumService
,I/ActivityManager(  761): Killing 1764:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1764/cgroup.procs: No such file or directory
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 3076): 
D/AndroidRuntime( 3076): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3076): CheckJNI is OFF
D/AndroidRuntime( 3076): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2978:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{398001a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
I/ActivityManager(  761):   Force finishing activity ActivityRecord{3514eb1d u0 com.test.thalitest/.MainActivity t220}
W/PackageSettings(  761): Skipping PackageSetting{255a0eab com.example.hello/10278} due to missing metadata
W/ActivityManager(  761): Spurious death for ProcessRecord{1b236f9b 2978:com.test.thalitest/u0a270}, curProc for 2978: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1556): Explicit concurrent mark sweep GC freed 936(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 366us total 25.311ms
I/art     ( 1383): Explicit concurrent mark sweep GC freed 6004(411KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 706us total 23.927ms
I/art     ( 1302): Explicit concurrent mark sweep GC freed 7330(552KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 622us total 17.258ms
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1083): resetDictionaries() : en_US
W/GeofencerStateMachine( 1337): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 2637): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1083): run()
I/Decoder ( 1083): createOrResetDecoder
I/art     (  761): Explicit concurrent mark sweep GC freed 14693(971KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.096ms total 68.987ms
I/art     (  761): WaitForGcToComplete blocked for 20.938ms for cause Explicit
I/UpdateIcingCorporaServi( 1383): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
W/Launcher( 1302): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1310f1b4 new=com.google.android.velvet.VelvetApplication@1310f1b4
D/OpenGLRenderer(  944): Enabling debug mode 0
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2978 uid 10270
I/Keyboard.Facilitator( 1083): onFinishInput()
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3118 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=220_task.xml
I/ConfigService( 1337): onCreate
I/CheckinRequestBuilder( 1337): Classify the device as Phone.
W/ContextImpl( 3118): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/art     (  761): Explicit concurrent mark sweep GC freed 4254(226KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.389ms total 156.614ms
I/UpdateIcingCorporaServi( 1383): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
D/ChimeraCfgMgr( 1556): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1556): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1556): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1556): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1556): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1556): Clearing selected account for com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1337): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1337): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/FetchTask( 1337): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/LocationSettingsChecker( 1556): Removing dialog suppression flag for package com.test.thalitest
I/CheckinRequestBuilder( 1337): Classify the device as Phone.
W/FetchTask( 1337): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/CheckinRequestBuilder( 1337): Classify the device as Phone.
D/gH_MetricsDatabase( 1556): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1556): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1556): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1556): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1556): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3158 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1302): Deferring update until onResume
W/FetchTask( 1337): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/AndroidRuntime( 3076): Shutting down VM
W/BaseAppContext( 1556): Using Auth Proxy for data requests.
W/BaseAppContext( 1556): Using Auth Proxy for data requests.
W/ResourcesManager( 1302): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1302): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1337): Classify the device as Phone.
W/FetchTask( 1337): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/GMPM-SVC( 1556): App measurement is starting up, version: 8489
I/GMPM-SVC( 1556): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Launcher( 1302): Deferring update until onResume
I/Icing   ( 1556): doRemovePackageData com.test.thalitest
I/CheckinRequestBuilder( 1337): Classify the device as Phone.
W/FetchTask( 1337): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): run()
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3185 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = user
I/ActivityManager(  761): Killing 2522:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1083): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1083): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1083): run()
I/StatsUtilsManager( 1083): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1083): shouldRecordStats() = Too Soon
W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2522/cgroup.procs: No such file or directory
I/ActivityManager(  761): Killing 2385:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3185): After updating volumes, found 1 active roots
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2385/cgroup.procs: No such file or directory
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 2691): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2691): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1556): Awaiting to be initialized
W/DriveInitializer( 1556): Background init thread started
E/SQLiteLog( 1556): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
D/Documents( 3158): Update found 7 roots in 258ms
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
I/Process ( 1556): Sending signal. PID: 1556 SIG: 9
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
D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3a2852a)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Documents( 3158): Update found 7 roots in 141ms

```
