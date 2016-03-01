#### Test 6122644500803c8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2375): [236] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2375): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/NetworkUtils( 1366): OkHttp exception
W/EventLoggerService( 1366): Unable to send logs Error code: 262146
D/AndroidRuntime( 2865): 
D/AndroidRuntime( 2865): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2865): CheckJNI is OFF
D/AndroidRuntime( 2865): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2892 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2865): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 2892): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2892): Time to load native libraries: 2 ms (timestamps 2572-2574)
I/LibraryLoader( 2892): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2892): Binding Chromium to main looper Looper (main, tid 1) {12edba87}
I/LibraryLoader( 2892): Expected native library version number "",actual native library version number ""
I/chromium( 2892): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2892): Initializing chromium process, singleProcess=true
W/art     ( 2892): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2892): ApplicationContext is null in ApplicationStatus
,W/chromium( 2892): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2892): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2892): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     (  761): Explicit concurrent mark sweep GC freed 21220(975KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 1.044ms total 54.291ms
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26f53c90:true
,D/BluetoothAdapter( 2892): 113339097: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2892): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2892): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2892): CordovaWebView is running on device made by: LGE
,W/art     ( 2892): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2892): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2892): Render dirty regions requested: true
,D/Atlas   ( 2892): Validating map...
,W/chromium( 2892): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2892): Initialized EGL, version 1.4
D/OpenGLRenderer( 2892): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +493ms (total +1m10s765ms)
,W/IInputConnectionWrapper( 2892): showStatusIcon on inactive InputConnection
,W/BindingManager( 2892): Cannot call determinedVisibility() - never saw a connection for the pid: 2892
,D/JsMessageQueue( 2892): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2892): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3275c403 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2892): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Discovery mode: WIFI
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e869d5f added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2892): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  761): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2892): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2892): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): setDiscoveryMode: WIFI -> BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2892): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2892): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2892): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2892): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2892): Initializing JXcore engine
W/jxcore-log( 2892): JXcore engine is ready
,W/Thread-279( 2943): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9429]" dev="sockfs" ino=9429 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-279( 2943): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-279( 2943): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9547]" dev="sockfs" ino=9547 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-279( 2943): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17255]" dev="sockfs" ino=17255 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2892): Starting JXcore engine
,W/jxcore-log( 2892): Platform android
W/jxcore-log( 2892): 
W/jxcore-log( 2892): Process ARCH arm
W/jxcore-log( 2892): 
,I/jxcore-log( 2892): JXcore Cordova bridge is ready!
I/jxcore-log( 2892): 
W/jxcore-log( 2892): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2892): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2892): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 2892): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 2892): BLE multiple advertisement supported
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): My device name is: LGE-Nexus 5
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2892): 
I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 2892): 
I/jxcore-log( 2892): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 2892): 
,I/io.jxcore.node.ConnectivityInfo( 2892): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 2892):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 2892):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 2892):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 2892):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 2892):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 2892):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 2892):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 2892):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 2892): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 2892): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 2892): 
I/jxcore-log( 2892): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 2892): 
I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): Unit Test app is loaded
I/jxcore-log( 2892): 
,I/jxcore-log( 2892): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 2892): 
,I/chromium( 2892): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/ClearcutLoggerApiImpl( 1320): disconnect managed GoogleApiClient
,I/VacuumService( 1320): Vacuum at: now=1456845400748 tag=VacuumService
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1768:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1768/cgroup.procs: No such file or directory
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 2993): 
D/AndroidRuntime( 2993): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2993): CheckJNI is OFF
D/AndroidRuntime( 2993): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2892:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{3358e9c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{2f5194fa com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{1547bcd5 u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  761): Spurious death for ProcessRecord{25eb7313 2892:com.test.thalitest/u0a270}, curProc for 2892: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{1547bcd5 u0 com.test.thalitest/.MainActivity t218 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{1547bcd5 u0 com.test.thalitest/.MainActivity t218 f}
I/art     ( 1557): Explicit concurrent mark sweep GC freed 972(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 367us total 56.380ms
I/art     ( 1366): Explicit concurrent mark sweep GC freed 3864(254KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 18MB/25MB, paused 598us total 60.915ms
I/art     ( 1251): Explicit concurrent mark sweep GC freed 7299(551KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 224us total 45.116ms
I/Keyboard.Facilitator( 1074): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1074): run()
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/art     (  761): Explicit concurrent mark sweep GC freed 13072(881KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/40MB, paused 2.060ms total 61.321ms
I/art     (  761): WaitForGcToComplete blocked for 13.303ms for cause Explicit
W/GeofencerStateMachine( 1320): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1074): createOrResetDecoder
I/UpdateIcingCorporaServi( 1366): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1251): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@12edba87 new=com.google.android.velvet.VelvetApplication@12edba87
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3033 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/OpenGLRenderer(  944): Enabling debug mode 0
D/VoicemailCleanupService( 2548): Cleaning up data for package: com.test.thalitest
I/ConfigService( 1320): onCreate
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=218_task.xml
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2892 uid 10270
I/Keyboard.Facilitator( 1074): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): run()
I/art     (  761): Explicit concurrent mark sweep GC freed 4882(275KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.889ms total 131.897ms
W/ContextImpl( 3033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1366): UpdateCorporaTask done [took 115 ms] updated apps [took 114 ms] 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1074): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1074): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1074): run()
I/StatsUtilsManager( 1074): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1074): shouldRecordStats() = Too Soon
D/PackageBroadcastService( 1557): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1557): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1320): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1320): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1557): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1557): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3067 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1557): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Launcher( 1251): Deferring update until onResume
D/AndroidRuntime( 2993): Shutting down VM
W/BaseAppContext( 1557): Using Auth Proxy for data requests.
W/BaseAppContext( 1557): Using Auth Proxy for data requests.
W/ResourcesManager( 1251): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1251): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/GMPM-SVC( 1557): App measurement is starting up, version: 8489
I/GMPM-SVC( 1557): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Launcher( 1251): Deferring update until onResume
I/Icing   ( 1557): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3092 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2458:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Killing 1448:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2458/cgroup.procs: No such file or directory
W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1448/cgroup.procs: No such file or directory
D/ExternalStorage( 3092): After updating volumes, found 1 active roots
W/DriveInitializer( 1557): Awaiting to be initialized
W/DriveInitializer( 1557): Background init thread started
E/SQLiteLog( 1557): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 1557): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1557): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1557): Background init thread ended
E/SQLiteLog( 1557): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1557): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1557): Process: com.google.android.gms, PID: 1557
E/AndroidRuntime( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1557): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1557): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 1557): disk I/O error (code 3850)
E/DriveAsyncService( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1557): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1557): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1557): 	at java.lang.Thread.run(Thread.java:818)
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
W/ResourcesManager( 2608): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2608): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Process ( 1557): Sending signal. PID: 1557 SIG: 9
D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@21139df7)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Documents( 3067): Update found 7 roots in 320ms
I/ActivityManager(  761): Process com.google.android.gms (pid 1557) has died
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms

```
