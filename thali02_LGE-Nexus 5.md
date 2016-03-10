#### Test 623288225dc9f88_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2449): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2449): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 2978): 
D/AndroidRuntime( 2978): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2978): CheckJNI is OFF
D/AndroidRuntime( 2978): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2999 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2978): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 2999): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2999): Time to load native libraries: 2 ms (timestamps 4566-4568)
I/LibraryLoader( 2999): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2999): Binding Chromium to main looper Looper (main, tid 1) {1cd90f3c}
I/LibraryLoader( 2999): Expected native library version number "",actual native library version number ""
I/chromium( 2999): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2999): Initializing chromium process, singleProcess=true
W/art     ( 2999): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2999): ApplicationContext is null in ApplicationStatus
W/chromium( 2999): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2999): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2999): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2999): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2999): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17cf2062:true
,D/BluetoothAdapter( 2999): 314958632: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2999): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2999): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2999): CordovaWebView is running on device made by: LGE
,W/art     ( 2999): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2999): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2999): Render dirty regions requested: true
,D/Atlas   ( 2999): Validating map...
,W/chromium( 2999): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2999): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2999): Enabling debug mode 0
,I/Keyboard.Facilitator( 1070): onFinishInput()
,W/BindingManager( 2999): Cannot call determinedVisibility() - never saw a connection for the pid: 2999
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +430ms (total +1m14s700ms)
,W/IInputConnectionWrapper( 2999): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 2999): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2999): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1549081728
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18d21588 added. We now have 1 listener(s)
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): setBluetoothMacAddress: 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2999): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2999): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26370234 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2999): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  733): New client listening to asynchronous messages
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2999): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2999): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2999): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2999): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2999): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2999): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2999): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2999): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2999): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2999): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2999): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2999): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2999): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 2999): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2999): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@304ff85d added. We now have 2 listener(s)
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2999): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2999): setIdentityString: {"name":"<no peer name>","address":"34:FC:EF:11:AE:67"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a745d2 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2999): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2999): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 2999): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 2999): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 2999): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 2999): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 2999): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 2999): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 2999): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 2999): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 2999): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 2999): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 2999): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 2999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2999): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2999): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 2999): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 2999): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1070): run()
I/Keyboard.Facilitator( 1070): flushDynamicLanguageModels()
,I/ConfigService( 1270): onCreate
,I/ConfigService( 1270): onDestroy
,I/ClearcutLoggerApiImpl( 1270): disconnect managed GoogleApiClient
,I/art     (  733): Explicit concurrent mark sweep GC freed 17291(754KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.299ms total 72.439ms
,I/VacuumService( 1270): Vacuum at: now=1457577307732 tag=VacuumService
,W/ProcessCpuTracker(  733): Skipping unknown process pid 3065
W/ProcessCpuTracker(  733): Skipping unknown process pid 3068
,I/ActivityManager(  733): Killing 2418:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2418/cgroup.procs: No such file or directory
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1270): disconnect managed GoogleApiClient
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  733): User[0] Flushing usage stats to disk
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3097): 
D/AndroidRuntime( 3097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3097): CheckJNI is OFF
D/AndroidRuntime( 3097): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 2999:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  733): Client connection lost with reason: 4
I/WindowState(  733): WIN DEATH: Window{29846612 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  733): Skipping PackageSetting{81bf2d3 com.example.hello/10278} due to missing metadata
I/ActivityManager(  733):   Force finishing activity ActivityRecord{fdd5f5f u0 com.test.thalitest/.MainActivity t220}
W/ActivityManager(  733): Spurious death for ProcessRecord{3f26f20f 2999:com.test.thalitest/u0a270}, curProc for 2999: null
I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1545): Explicit concurrent mark sweep GC freed 980(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 21MB/29MB, paused 362us total 24.729ms
I/art     ( 1332): Explicit concurrent mark sweep GC freed 6155(419KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 284us total 18.969ms
I/art     ( 1288): Explicit concurrent mark sweep GC freed 7382(555KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 658us total 16.783ms
I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1270): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1070): resetDictionaries() : en_US
D/VoicemailCleanupService( 1354): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1070): run()
I/Decoder ( 1070): createOrResetDecoder
W/Launcher( 1288): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1cd90f3c new=com.google.android.velvet.VelvetApplication@1cd90f3c
I/UpdateIcingCorporaServi( 1332): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ConfigService( 1270): onCreate
I/art     (  733): Explicit concurrent mark sweep GC freed 11956(819KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.891ms total 78.428ms
I/art     (  733): WaitForGcToComplete blocked for 31.117ms for cause Explicit
I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
D/OpenGLRenderer(  943): Enabling debug mode 0
I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3139 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/CheckinRequestBuilder( 1270): Classify the device as Phone.
D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  733): removeObsoleteFile: deleting file=220_task.xml
W/ContextImpl( 3139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@26877b5c (uid=10034 pid=943)
D/PackageBroadcastService( 1545): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1545): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1545): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1545): Module APK com.google.android.play.games already loaded
W/FetchTask( 1270): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ChimeraCfgMgr( 1545): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1545): Module APK com.google.android.play.games already loaded
I/art     (  733): Explicit concurrent mark sweep GC freed 5430(276KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 8.015ms total 148.759ms
I/UpdateIcingCorporaServi( 1332): UpdateCorporaTask done [took 168 ms] updated apps [took 168 ms] 
W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 2999 uid 10270
I/LocationSettingsChecker( 1545): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator( 1070): onFinishInput()
E/NetworkScheduler.SchedulerReceiver( 1270): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1270): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/CheckinRequestBuilder( 1270): Classify the device as Phone.
W/FetchTask( 1270): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1270): Classify the device as Phone.
D/gH_CompatibleDatabase( 1545): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1545): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1545): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1545): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1545): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1545): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1545): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1545): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1545): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1545): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3178 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1545): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1545): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1545): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/FetchTask( 1270): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Launcher( 1288): Deferring update until onResume
W/BaseAppContext( 1545): Using Auth Proxy for data requests.
D/AndroidRuntime( 3097): Shutting down VM
W/ResourcesManager( 1288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1545): Using Auth Proxy for data requests.
I/CheckinRequestBuilder( 1270): Classify the device as Phone.
W/FetchTask( 1270): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/GMPM-SVC( 1545): App measurement is starting up, version: 8489
I/GMPM-SVC( 1545): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1288): Deferring update until onResume
I/CheckinRequestBuilder( 1270): Classify the device as Phone.
I/Icing   ( 1545): doRemovePackageData com.test.thalitest
W/FetchTask( 1270): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1070): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1070): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1070): run()
I/StatsUtilsManager( 1070): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1070): shouldRecordStats() = Too Soon
I/ActivityManager(  733): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3207 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  733): Killing 1799:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_1799/cgroup.procs: No such file or directory
I/ActivityManager(  733): Killing 2529:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2529/cgroup.procs: No such file or directory
D/ConnectivityService(  733): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ExternalStorage( 3207): After updating volumes, found 1 active roots

```
