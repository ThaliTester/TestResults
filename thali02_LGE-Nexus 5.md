#### Test 613623666a5dbc7_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1278): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/NetworkUtils( 1361): OkHttp exception
W/EventLoggerService( 1361): Unable to send logs Error code: 262146
W/Search.LoginHelper( 1361): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1278): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1361): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/AndroidRuntime( 2970): 
D/AndroidRuntime( 2970): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2970): CheckJNI is OFF
D/AndroidRuntime( 2970): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3009 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2970): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3009): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3009): Time to load native libraries: 4 ms (timestamps 6286-6290)
I/LibraryLoader( 3009): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3009): Binding Chromium to main looper Looper (main, tid 1) {175b2fbb}
I/LibraryLoader( 3009): Expected native library version number "",actual native library version number ""
I/chromium( 3009): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3009): Initializing chromium process, singleProcess=true
W/art     ( 3009): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3009): ApplicationContext is null in ApplicationStatus
,W/chromium( 3009): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3009): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3009): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3009): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3009): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@360e61a2:true
D/BluetoothAdapter( 3009): 829197956: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3009): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3009): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3009): CordovaWebView is running on device made by: LGE
,W/art     ( 3009): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3009): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3009): Render dirty regions requested: true
,D/Atlas   ( 3009): Validating map...
,W/chromium( 3009): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3009): Initialized EGL, version 1.4
D/OpenGLRenderer( 3009): Enabling debug mode 0
,I/art     (  761): Explicit concurrent mark sweep GC freed 18307(851KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 742us total 56.522ms
,W/IInputConnectionWrapper( 3009): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1072): onFinishInput()
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +500ms (total +1m3s567ms)
,W/BindingManager( 3009): Cannot call determinedVisibility() - never saw a connection for the pid: 3009
,D/JsMessageQueue( 3009): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3009): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3009): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b52a277 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bdb6a02 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3009): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  761): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3009): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3009): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3009): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3009): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3009): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 3009): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3009): Initializing JXcore engine
W/jxcore-log( 3009): JXcore engine is ready
,W/Thread-284( 3061): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7991]" dev="sockfs" ino=7991 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-284( 3061): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-284( 3061): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6753]" dev="sockfs" ino=6753 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-284( 3061): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18894]" dev="sockfs" ino=18894 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3009): Starting JXcore engine
,W/jxcore-log( 3009): Platform android
W/jxcore-log( 3009): 
W/jxcore-log( 3009): Process ARCH arm
W/jxcore-log( 3009): 
,I/jxcore-log( 3009): JXcore Cordova bridge is ready!
I/jxcore-log( 3009): 
,W/jxcore-log( 3009): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3009): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/Finsky  ( 2488): [241] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2488): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3009): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 3009): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 3009): BLE multiple advertisement supported
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): My device name is: LGE-Nexus 5
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3009): 
I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3009): 
,I/io.jxcore.node.ConnectivityInfo( 3009): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3009):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3009):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3009):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 3009):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 3009):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3009):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3009):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3009):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3009): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3009): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3009): 
I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): Unit Test app is loaded
I/jxcore-log( 3009): 
,I/jxcore-log( 3009): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 3009): 
I/chromium( 3009): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1072): run()
I/Keyboard.Facilitator( 1072): flushDynamicLanguageModels()
,I/ConfigService( 1278): onCreate
,I/ConfigService( 1278): onDestroy
,I/ClearcutLoggerApiImpl( 1278): disconnect managed GoogleApiClient
,I/VacuumService( 1278): Vacuum at: now=1456906158063 tag=VacuumService
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium(  950): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  950): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  950): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1825:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1825/cgroup.procs: No such file or directory
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium(  950): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  950): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  950): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1278): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3112): 
D/AndroidRuntime( 3112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3112): CheckJNI is OFF
D/AndroidRuntime( 3112): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3009:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{7b67752 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{7977e3e com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{e325b9f u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  761): Spurious death for ProcessRecord{65be529 3009:com.test.thalitest/u0a270}, curProc for 3009: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{e325b9f u0 com.test.thalitest/.MainActivity t218 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{e325b9f u0 com.test.thalitest/.MainActivity t218 f}
I/art     ( 1361): Explicit concurrent mark sweep GC freed 3165(215KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 517us total 30.041ms
I/art     ( 1611): Explicit concurrent mark sweep GC freed 802(33KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 21MB/29MB, paused 485us total 35.080ms
I/art     ( 1234): Explicit concurrent mark sweep GC freed 7378(555KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 223us total 21.995ms
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1278): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1072): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1072): run()
I/Decoder ( 1072): createOrResetDecoder
D/VoicemailCleanupService( 2668): Cleaning up data for package: com.test.thalitest
I/art     (  761): Explicit concurrent mark sweep GC freed 14608(955KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 904us total 87.518ms
I/art     (  761): WaitForGcToComplete blocked for 28.967ms for cause Explicit
I/LibraryLoader( 1473): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/UpdateIcingCorporaServi( 1361): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1234): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@175b2fbb new=com.google.android.velvet.VelvetApplication@175b2fbb
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3150 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/LibraryLoader( 1473): Time to load native libraries: 77 ms (timestamps 6978-7055)
I/LibraryLoader( 1473): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1473): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1473): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1473): Attempt to remove local handle scope entry from IRT, ignoring
I/ConfigService( 1278): onCreate
I/art     (  761): Explicit concurrent mark sweep GC freed 3281(158KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.251ms total 88.305ms
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
I/OpenGLRenderer(  950): Initialized EGL, version 1.4
D/OpenGLRenderer(  950): Enabling debug mode 0
D/TaskPersister(  761): removeObsoleteFile: deleting file=218_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): run()
I/UpdateIcingCorporaServi( 1361): UpdateCorporaTask done [took 142 ms] updated apps [took 141 ms] 
W/ContextImpl( 3150): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1611): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1611): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1611): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1611): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@5326c1e (uid=10034 pid=950)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1072): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1072): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1072): run()
I/StatsUtilsManager( 1072): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1072): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1611): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1611): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1278): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1278): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1611): Removing dialog suppression flag for package com.test.thalitest
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3009 uid 10270
I/Keyboard.Facilitator( 1072): onFinishInput()
D/gH_CompatibleDatabase( 1611): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1611): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1611): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1611): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/AndroidRuntime( 3112): Shutting down VM
D/gH_CompatibleDatabase( 1611): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1611): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1611): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1611): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1611): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1611): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1611): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1611): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1611): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3190 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1234): Deferring update until onResume
W/BaseAppContext( 1611): Using Auth Proxy for data requests.
W/ResourcesManager( 1234): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1611): Using Auth Proxy for data requests.
I/GMPM-SVC( 1611): App measurement is starting up, version: 8489
I/GMPM-SVC( 1611): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/ResourcesManager( 1234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1234): Deferring update until onResume
I/Icing   ( 1611): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Killing 2563:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3223 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2563/cgroup.procs: No such file or directory
I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 196us total 8.457ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 172us total 7.488ms
I/art     (  195): Explicit concurrent mark sweep GC freed 2(64B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 177us total 8.217ms
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  761): Killing 2421:com.google.android.gm/u0a70 (adj 15): empty #17
D/ExternalStorage( 3223): After updating volumes, found 1 active roots
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2421/cgroup.procs: No such file or directory
W/DriveInitializer( 1611): Awaiting to be initialized
W/DriveInitializer( 1611): Background init thread started
E/SQLiteLog( 1611): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 1611): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1611): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1611): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1611): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1611): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1611): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1611): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1611): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1611): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1611): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1611): Background init thread ended
E/SQLiteLog( 1611): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1611): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1611): Process: com.google.android.gms, PID: 1611
E/AndroidRuntime( 1611): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1611): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1611): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1611): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1611): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1611): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1611): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1611): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1611): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 1611): disk I/O error (code 3850)
E/DriveAsyncService( 1611): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1611): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1611): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1611): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1611): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1611): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1611): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1611): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1611): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1611): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1611): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1611): Sending signal. PID: 1611 SIG: 9
E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
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
D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1dc7673a)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 2721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
