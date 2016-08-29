#### Test 81418577b213184_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 11:26:36.494  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 11:26:36.505  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 11:26:36.510  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 11:26:36.553  1513  2406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 11:26:36.553  1513  2406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 11:26:36.553  1513  2406 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:26:36.554  1513  2406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 11:26:36.595  3669  3669 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 11:26:36.596  3669  3669 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 11:26:36.596  3669  3669 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-29 11:26:38.530  4009  4009 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 11:26:38.535  4009  4009 D AndroidRuntime: CheckJNI is OFF
08-29 11:26:38.577  4009  4009 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 11:26:38.626  4009  4009 I Radio-JNI: register_android_hardware_Radio DONE
08-29 11:26:38.647  4009  4009 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 11:26:38.651   873  1389 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 11:26:38.693   873  1389 I ActivityManager: Start proc 4018:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 11:26:38.705  4009  4009 D AndroidRuntime: Shutting down VM
08-29 11:26:38.784  4018  4018 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 11:26:38.809  4018  4018 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 11:26:38.815  4018  4018 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5025-5027)
08-29 11:26:38.816  4018  4018 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:26:38.833  4018  4018 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ec721f7}
08-29 11:26:38.833  4018  4018 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:26:38.833  4018  4018 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 11:26:38.841  4018  4018 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 11:26:38.843  4018  4018 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 11:26:38.862  4018  4018 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 11:26:38.872  4018  4018 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:26:38.873  4018  4018 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:26:38.873  4018  4018 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 11:26:38.873  4018  4018 I Adreno  : Build Date                       : 10/20/15
08-29 11:26:38.873  4018  4018 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 11:26:38.873  4018  4018 I Adreno  : Local Branch                     : M14
08-29 11:26:38.873  4018  4018 I Adreno  : Remote Branch                    : 
08-29 11:26:38.873  4018  4018 I Adreno  : Remote Branch                    : 
08-29 11:26:38.873  4018  4018 I Adreno  : Reconstruct Branch               : 
08-29 11:26:38.953   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57544d1:true
,08-29 11:26:38.986  4018  4018 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 11:26:39.000  4018  4018 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 11:26:39.086  4018  4055 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 11:26:39.099  4018  4042 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 11:26:39.140  4018  4055 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 11:26:39.186   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +444ms (total +512ms)
,08-29 11:26:39.191  1860  1860 I Keyboard.Facilitator: onFinishInput()
,08-29 11:26:39.264  4018  4018 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4018
,08-29 11:26:39.391  4018  4018 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 11:26:39.587  4018  4057 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1700071120
,08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 11:26:39.594  4018  4057 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@622a39a added. We now have 1 listener(s)
,08-29 11:26:39.597  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 11:26:39.598  4018  4057 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:26:39.598  4018  4057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:26:39.598  4018  4057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 11:26:39.602  4018  4057 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd8ebc1 added. We now have 1 listener(s)
08-29 11:26:39.602  4018  4057 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:26:39.608   873  1304 D WifiService: New client listening to asynchronous messages
,08-29 11:26:39.609  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:26:39.609  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 11:26:39.609  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 11:26:39.609  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 11:26:39.609  4018  4057 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 11:26:39.619  4018  4057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:26:39.619  4018  4057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 11:26:39.634  4018  4057 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:39.635  4018  4057 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:39.635  4018  4057 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 11:26:39.635  4018  4057 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:26:39.636  4018  4057 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:26:39.641  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:39.644  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:39.667  4018  4018 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 11:26:40.436  4018  4065 W jxcore-log: Initializing JXcore engine
,08-29 11:26:40.436  4018  4065 W jxcore-log: JXcore engine is ready
,08-29 11:26:40.472  4065  4065 W Thread-369: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8955 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 11:26:40.472  4065  4065 W Thread-369: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13330]" dev="sockfs" ino=13330 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 11:26:40.472  4065  4065 W Thread-369: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 11:26:40.472  4065  4065 W Thread-369: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[30535]" dev="sockfs" ino=30535 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 11:26:40.488  4018  4065 W jxcore-log: Starting JXcore engine
,08-29 11:26:40.569  4018  4065 W jxcore-log: Platform android
08-29 11:26:40.569  4018  4065 W jxcore-log: 
,08-29 11:26:40.570  4018  4065 W jxcore-log: Process ARCH arm
08-29 11:26:40.570  4018  4065 W jxcore-log: 
,08-29 11:26:40.758  4018  4065 I jxcore-log: JXcore Cordova bridge is ready!
08-29 11:26:40.758  4018  4065 I jxcore-log: 
,08-29 11:26:40.759  4018  4065 W jxcore-log: JXcore engine is started
,08-29 11:26:40.772  4018  4057 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 11:26:40.777  4018  4018 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 11:26:41.914  1513  2213 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 11:26:46.164  3929  4066 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 11:26:46.213  3929  4067 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 11:26:46.242  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:46.247  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:46.287  1513  2097 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 11:26:46.288  1513  2097 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 11:26:46.288  1513  2097 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:26:46.288  1513  2097 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:26:46.321  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:46.326  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:46.366  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 11:26:46.366  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 11:26:46.366  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:26:46.367  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:26:46.394  3929  4067 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 11:26:46.395  3929  4066 E BooksSync: Soft error
08-29 11:26:46.395  3929  4066 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 11:26:46.395  3929  4066 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 11:26:46.395  3929  4066 E BooksSync: Sync error
08-29 11:26:46.395  3929  4066 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 11:26:46.395  3929  4066 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 11:26:46.397  3929  4066 I BooksSync: Finished books sync
,08-29 11:26:46.406   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163959, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 11:26:50.225  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 11:26:50.225  4018  4065 I jxcore-log: 
,08-29 11:26:50.227  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 11:26:50.227  4018  4065 I jxcore-log: 
,08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:50.239  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:50.246  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:26:50.249  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 11:26:50.249  4018  4065 I jxcore-log: 
,08-29 11:26:50.250  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 11:26:50.250  4018  4065 I jxcore-log: 
,08-29 11:26:50.585   873  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 11:26:50.746  4018  4065 D executeNativeTests: Running unit tests
,08-29 11:26:50.804  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:26:50.804  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea added. We now have 2 listener(s)
,08-29 11:26:50.805  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:26:50.806  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:26:50.806  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:26:50.806  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:26:50.806  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db added. We now have 2 listener(s)
08-29 11:26:50.806  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:26:50.806  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:26:50.808  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:50.828  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:50.831  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:26:50.831  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:26:50.832  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:50.839  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:26:50.839  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:50.842  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:26:50.842  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:26:50.848  4018  4065 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 11:26:50.849  4018  4065 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:26:50.849  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 11:26:50.850  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:26:50.850  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 11:26:50.852  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:26:50.855  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:26:50.855  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:26:50.857  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:50.857  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:50.858  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:50.859  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:26:50.859  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea removed from the list
08-29 11:26:50.860  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:26:50.860  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db removed from the list
,08-29 11:26:50.861  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:50.861  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.862  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.862  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:50.863  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:50.864  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:26:50.864  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.864  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.865  4018  4065 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 11:26:50.866  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:26:50.866  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:26:50.866  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:26:50.866  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:50.866  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.866  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:50.866  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
,08-29 11:26:50.866  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:26:50.866  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.866  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:50.867  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.867  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.867  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.867  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.868  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:26:50.868  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:50.868  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.868  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.872  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 11:26:50.872  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 11:26:50.873  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:26:50.874  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:26:50.874  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:50.874  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:50.874  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:50.875  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:50.875  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:50.875  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.875  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:50.875  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.875  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.875  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:50.875  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.875  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.875  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.875  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.876  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:50.876  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:26:50.876  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.876  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.877  4018  4065 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:26:50.878  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:50.881  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:50.883  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.883  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:26:50.884  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:50.884  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:26:50.885  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:26:50.885  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 11:26:50.885  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:50.885  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:26:50.886  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:50.891  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 11:26:50.892  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:26:50.902  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:26:50.905  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 11:26:50.906  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:26:50.910  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 11:26:50.913  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 11:26:50.913  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:26:50.913  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 11:26:50.913  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:26:50.914  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:50.918  2632  2645 D BtGatt.GattService: registerClient() - UUID=7b2150f8-e4f5-4e71-8c75-f946d5d13afc
,08-29 11:26:50.919  2632  2659 D BtGatt.GattService: onClientRegistered() - UUID=7b2150f8-e4f5-4e71-8c75-f946d5d13afc, clientIf=5
,08-29 11:26:50.920  4018  4029 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:26:50.921  2632  2794 D BtGatt.GattService: start scan with filters
,08-29 11:26:50.923  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:26:50.924  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:26:50.924  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:26:50.924  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:26:50.924  2632  2669 D BtGatt.ScanManager: handling starting scan
,08-29 11:26:50.926  2632  2669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:26:50.929  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:26:50.929  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:26:50.930  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:26:50.932  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:26:50.934  2632  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:26:50.934  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:26:50.935  2632  2669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:26:50.936  4018  4065 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:26:50.940  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:26:50.940  4018  4065 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:26:50.940  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:26:50.941  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 11:26:50.941  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:26:50.941  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.941  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:26:50.941  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.941  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 11:26:50.941  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:26:50.941  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:26:50.941  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:26:50.942  2632  2669 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:26:50.942  2632  2669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:26:50.942  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:26:50.942  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:26:50.943  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:50.943  2632  2645 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:26:50.944  2632  2794 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:26:50.945  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:26:50.946  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:26:50.946  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:26:50.946  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:26:50.947  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:26:50.948  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:50.949  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:26:50.949  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:26:50.949  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:26:50.949  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:26:50.951  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:50.951  2632  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 11:26:50.951  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.951  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:50.951  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:50.951  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.951  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:50.951  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
,08-29 11:26:50.951  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.951  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:50.952  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.952  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:50.952  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.952  4018  4065 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 11:26:50.954  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:50.957  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:26:50.957  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:26:50.958  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.958  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:50.958  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:26:50.960  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:50.960  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:26:50.960  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:26:50.960  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 11:26:50.960  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:50.960  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:26:50.962  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:50.965  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:26:50.965  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:26:50.965  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 11:26:50.966  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.966  2632  2669 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:26:50.968  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:26:50.968  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 11:26:50.968  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:26:50.970  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:26:50.970  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:26:50.970  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 11:26:50.971  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:50.972  2632  2645 D BtGatt.GattService: registerClient() - UUID=b6f0374c-81e6-41bc-9185-4870d29af2f4
08-29 11:26:50.972  2632  2659 D BtGatt.GattService: onClientRegistered() - UUID=b6f0374c-81e6-41bc-9185-4870d29af2f4, clientIf=5
08-29 11:26:50.973  4018  4028 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:26:50.973  2632  2643 D BtGatt.GattService: start scan with filters
08-29 11:26:50.974  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:26:50.974  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.974  2632  2669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 11:26:50.976  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 11:26:50.977  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:26:50.977  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:26:50.977  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:26:50.978  2632  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:26:50.978  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:26:50.980  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:26:50.980  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:26:50.980  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:26:50.980  2632  2669 D BtGatt.ScanManager: handling starting scan
,08-29 11:26:50.981  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:26:50.985  4018  4065 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:26:50.985  2632  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:26:50.985  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:26:50.985  2632  2669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:26:50.987  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:50.987  4018  4065 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:26:50.987  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:50.987  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:26:50.988  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:50.988  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:26:50.988  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 11:26:50.988  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:26:50.988  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:26:50.988  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:26:50.989  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:26:50.989  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:26:50.989  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:50.990  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 11:26:50.990  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:50.990  2632  2669 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:26:50.990  2632  2669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:26:50.991  2632  2643 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:26:50.991  2632  2794 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:26:50.992  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:26:50.992  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:26:50.992  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:26:50.992  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:26:50.992  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:26:50.993  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:50.993  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:26:50.993  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:26:50.993  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:26:50.994  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:50.994  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:26:50.994  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.994  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:50.994  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:50.995  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:50.995  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.995  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:50.995  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.995  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:26:50.995  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:50.995  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.995  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:50.995  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:50.996  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:50.996  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:50.996  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:50.996  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:50.996  4018  4065 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:26:50.998  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:26:51.002  2632  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:26:51.002  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:51.002  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:51.005  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:26:51.005  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:26:51.005  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:26:51.005  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:26:51.005  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:26:51.005  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:51.005  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:26:51.007  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.008  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:26:51.008  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.009  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.009  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:26:51.009  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:26:51.011  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:26:51.012  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:26:51.012  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:26:51.015  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 11:26:51.015  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.015  2632  2669 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:26:51.015  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:26:51.015  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:26:51.015  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 11:26:51.016  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:51.018  2632  2794 D BtGatt.GattService: registerClient() - UUID=7bba3110-8ef7-4deb-9394-95a439574df4
08-29 11:26:51.018  2632  2659 D BtGatt.GattService: onClientRegistered() - UUID=7bba3110-8ef7-4deb-9394-95a439574df4, clientIf=5
08-29 11:26:51.018  4018  4029 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:26:51.019  2632  2645 D BtGatt.GattService: start scan with filters
08-29 11:26:51.020  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:26:51.020  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:26:51.021  2632  2669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:26:51.021  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:26:51.021  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:26:51.021  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:26:51.021  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 11:26:51.023  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:26:51.023  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:26:51.023  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:26:51.024  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:26:51.026  2632  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:26:51.026  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.026  4018  4065 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:26:51.026  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.027  4018  4065 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:26:51.027  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.027  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:26:51.028  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:51.028  2632  2669 D BtGatt.ScanManager: handling starting scan
08-29 11:26:51.028  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:26:51.028  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:26:51.028  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:26:51.028  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 11:26:51.028  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:26:51.028  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:26:51.028  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:26:51.028  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:26:51.029  2632  2794 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:26:51.029  2632  2645 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:26:51.030  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:26:51.030  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:26:51.030  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:26:51.030  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:26:51.031  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:51.032  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:51.032  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:51.032  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.032  4018  4065 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:26:51.032  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:51.032  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.032  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.032  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.032  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.032  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:26:51.032  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.032  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.032  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.032  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.033  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:51.033  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.033  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.034  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.034  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.035  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.035  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.035  4018  4065 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 11:26:51.035  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.036  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.036  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.036  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.036  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.036  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.036  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.036  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.036  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
,08-29 11:26:51.036  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.036  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:51.036  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.036  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.036  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.039  2632  2659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:26:51.039  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.039  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:26:51.040  2632  2669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 11:26:51.039  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.042  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:26:51.042  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
,08-29 11:26:51.045  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 11:26:51.045  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.045  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.046  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:26:51.046  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.046  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:51.047  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:26:51.048  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.047  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.048  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.048  2632  2669 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:26:51.048  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:26:51.049  2632  2669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:26:51.049  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.049  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.049  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.049  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.049  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.050  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:51.051  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.051  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:26:51.051  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.051  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.051  4018  4065 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 11:26:51.052  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.052  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.052  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.052  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.052  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.052  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.052  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
,08-29 11:26:51.052  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.052  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.052  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.052  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.052  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.052  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:51.052  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.054  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.054  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:26:51.054  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.054  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.054  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 11:26:51.054  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.055  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.055  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.055  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:26:51.055  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.055  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.055  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.055  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.055  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.055  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.055  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:26:51.055  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.055  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.055  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.056  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:26:51.056  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.056  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.056  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.057  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 11:26:51.058  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:26:51.058  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:26:51.058  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:26:51.059  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:26:51.059  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:26:51.059  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:26:51.059  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.059  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:26:51.059  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.059  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.059  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.059  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.059  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.059  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.059  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.059  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.059  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.059  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.059  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.061  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.061  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:26:51.061  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.061  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.061  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:26:51.062  4018  4065 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:26:51.062  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 11:26:51.066  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:26:51.066  4018  4065 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:26:51.066  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:26:51.067  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 11:26:51.067  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 11:26:51.068  4018  4065 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:26:51.068  2632  2659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:26:51.068  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.068  4018  4065 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 11:26:51.068  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:26:51.068  4018  4065 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:26:51.068  4018  4065 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 11:26:51.068  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:26:51.068  4018  4065 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:26:51.068  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 11:26:51.072  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 11:26:51.073  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 11:26:51.073  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 11:26:51.074  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-29 11:26:51.074  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 11:26:51.074  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 11:26:51.074  4018  4065 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:26:51.074  4018  4065 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 11:26:51.074  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.074  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.075  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.075  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.075  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.075  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:51.075  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 11:26:51.075  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.075  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.075  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.076  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.076  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.076  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.076  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.076  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.076  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 11:26:51.076  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.076  4018  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 433
08-29 11:26:51.077  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.077  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.077  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.077  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.078  4018  4065 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 11:26:51.078  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.078  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.078  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.079  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.079  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.079  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.079  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.079  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:26:51.079  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.079  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.079  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.079  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.079  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.079  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.080  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.080  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.080  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.080  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.081  4018  4065 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 11:26:51.081  4018  4068 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 433)
08-29 11:26:51.081  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.081  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.081  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.082  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.081  4018  4068 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 433)
08-29 11:26:51.082  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.082  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.082  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.082  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.082  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.082  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.082  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.082  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.082  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.082  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.083  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.083  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.083  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.083  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.083  2632  2659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:26:51.083  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.083  2632  2669 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 11:26:51.085  4018  4065 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:26:51.085  4018  4065 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:26:51.085  4018  4065 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:26:51.085  4018  4065 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:26:51.085  4018  4065 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:26:51.085  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:26:51.086  4018  4065 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 11:26:51.086  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.086  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.086  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.086  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.086  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.086  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.086  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.086  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.086  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.086  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.086  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.086  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.086  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.086  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.087  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.087  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.087  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.087  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.087  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.088  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.088  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.088  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.088  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.088  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.088  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.088  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.088  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.088  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.088  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.088  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.088  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.088  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.088  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.088  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.088  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.088  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.089  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.089  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.089  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.089  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.089  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.089  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.089  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.089  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.089  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.089  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.089  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.090  2632  2659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:26:51.090  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.090  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.090  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.090  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.091  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.090  2632  2669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:26:51.092  4018  4065 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 11:26:51.092  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:51.093  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 11:26:51.093  4018  4065 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 11:26:51.093  4018  4065 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 11:26:51.094  4018  4018 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 11:26:51.094  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 11:26:51.094  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:26:51.094  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.094  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 11:26:51.094  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 11:26:51.094  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 11:26:51.094  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.094  4018  4065 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 11:26:51.094  4018  4018 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 11:26:51.095  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.095  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.095  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:26:51.095  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:26:51.095  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:26:51.095  4018  4070 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 11:26:51.096  4018  4070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 11:26:51.097  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.097  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.099  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:51.099  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:51.099  4018  4018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 11:26:51.099  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:26:51.099  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:26:51.100  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.100  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.100  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.100  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.100  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.100  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.100  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.100  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.100  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.100  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.100  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.100  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.100  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.100  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.100  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.101  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.101  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.101  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.101  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.102  4018  4065 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 11:26:51.102  4018  4065 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:26:51.102  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:26:51.102  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:26:51.103  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.103  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.103  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.103  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.103  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.103  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.103  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.103  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.103  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.103  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.103  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.103  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.103  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.103  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:26:51.104  2632  2659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-29 11:26:51.104  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.104  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.105  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.105  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.104  2632  2659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:26:51.107  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.107  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.107  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.107  2632  2659 D BtGatt.GattService: current time is 197319827009
08-29 11:26:51.108  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.108  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.108  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.108  2632  2659 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 11:26:51.108  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.108  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.108  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.108  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.108  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.108  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.108  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.108  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.108  2632  2659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 11:26:51.109  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.109  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.109  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.109  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.110  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:26:51.110  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:26:51.110  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:26:51.110  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:26:51.110  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.111  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.111  4018  4065 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77e5fea not in the list
08-29 11:26:51.111  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.111  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.111  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:26:51.111  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.111  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.111  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:26:51.111  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:26:51.112  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:26:51.112  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:26:51.112  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:26:51.112  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0452db not in the list
08-29 11:26:51.112  4018  4065 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 11:26:51.113  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:26:51.113  4018  4065 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 11:26:51.113  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:26:51.113  4018  4065 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 11:26:51.113  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:26:51.114  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:26:51.114  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 11:26:51.115  4018  4065 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 11:26:51.115  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:26:51.115  4018  4065 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 11:26:51.115  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:26:51.115  4018  4065 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 11:26:51.115  4018  4065 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 11:26:51.115  4018  4065 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 11:26:51.116  4018  4065 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 11:26:51.116  4018  4065 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 11:26:51.116  4018  4065 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 11:26:51.116  4018  4065 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 11:26:51.116  4018  4065 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 11:26:51.117  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:26:51.117  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e5d445 added. We now have 2 listener(s)
08-29 11:26:51.117  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:26:51.118  4018  4065 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 11:26:51.119   873  1977 D WifiService: setWifiEnabled: true pid=4018, uid=10000
08-29 11:26:51.119   873  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:26:51.119  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:26:51.119  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e6979a added. We now have 3 listener(s)
08-29 11:26:51.119  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:26:51.124  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:26:51.124  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37ba8cb added. We now have 4 listener(s)
08-29 11:26:51.124  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:26:51.125  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:26:51.125  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@116e8a8 added. We now have 5 listener(s)
08-29 11:26:51.125  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:26:51.126   873  1389 D WifiService: setWifiEnabled: false pid=4018, uid=10000
08-29 11:26:51.126   873  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:26:51.132  2632  2650 D BluetoothAdapterState: Current state: ON, message: 23
08-29 11:26:51.132  2632  2650 D BluetoothAdapterProperties: Setting state to 13
08-29 11:26:51.132  2632  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:26:51.132  2632  2650 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:26:51.134  2632  2632 D BluetoothMapService: onReceive
08-29 11:26:51.134  2632  2632 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:26:51.134  2632  2632 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:26:51.134  2632  2632 D BluetoothMapService: MAP Service closeService in
08-29 11:26:51.135  2632  2632 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 11:26:51.135  2632  2632 D ObexServerSockets0: shutdown(block = true)
08-29 11:26:51.135  2632  2632 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:26:51.135  2632  2795 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 11:26:51.135  2632  2632 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:26:51.136  2632  2766 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 11:26:51.137  2632  2650 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:26:51.137  2632  2796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 11:26:51.141  2632  2632 I BtOppRfcommListener: stopping Accept Thread
08-29 11:26:51.142  2632  3559 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:26:51.143  2632  3559 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:26:51.144  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:51.144  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:26:51.144  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.145  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:51.151  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:26:51.152   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 11:26:51.153   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 11:26:51.153   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:26:51.153   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:26:51.156   873   886 I ActivityManager: Start proc 4073:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 11:26:51.157  2632  2659 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:26:51.157  2632  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 11:26:51.157  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:26:51.160  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:51.160  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:26:51.161  2632  2632 D HeadsetService: Received stop request...Stopping profile...
08-29 11:26:51.163   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 11:26:51.163   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 11:26:51.163  1360  2048 D BluetoothHeadset: Proxy object disconnected
08-29 11:26:51.163   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 11:26:51.163  1920  1930 D BluetoothHeadset: Proxy object disconnected
,08-29 11:26:51.164  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.164  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:51.164  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:26:51.165   873  1303 E native  : do suspend true
08-29 11:26:51.171  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.171  2632  2632 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:26:51.171  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:26:51.171  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:26:51.174  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-29 11:26:51.175  2632  2632 D A2dpService: Received stop request...Stopping profile...
,08-29 11:26:51.175  2632  2773 D A2dpStateMachine: Exit Disconnected: -1
08-29 11:26:51.176   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 11:26:51.177  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-29 11:26:51.177  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.179  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:51.180  2632  2632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 11:26:51.180  2632  2632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:26:51.180  2632  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 11:26:51.180  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:26:51.180  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:26:51.180  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:26:51.180  2632  2659 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 11:26:51.181  2632  2632 D HidService: Received stop request...Stopping profile...
08-29 11:26:51.181  2632  2632 D HidService: Stopping Bluetooth HidService
08-29 11:26:51.181  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-29 11:26:51.181  1360  1360 D HidProfile: Bluetooth service disconnected
08-29 11:26:51.182  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.183  2632  2632 D HealthService: Received stop request...Stopping profile...
08-29 11:26:51.184  2632  2632 D PanService: Received stop request...Stopping profile...
08-29 11:26:51.185  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:26:51.185  1360  1360 D PanProfile: Bluetooth service disconnected
08-29 11:26:51.186  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.187  2632  2632 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:26:51.187  2632  2632 D BluetoothMapService: stop()
,08-29 11:26:51.193   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:26:51.194   873  1877 D DhcpClient: Clearing IP address
,08-29 11:26:51.195   373   871 D CommandListener: Setting iface cfg
08-29 11:26:51.197  1513  3547 V NativeCrypto: Read error: ssl=0x9b3ffa00: I/O error during system call, Connection timed out
08-29 11:26:51.198  2632  2632 D BluetoothMapAppObserver: deinitObservers()
08-29 11:26:51.198  2632  2632 D BluetoothMapAppObserver: removeReceiver()
08-29 11:26:51.200   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 11:26:51.200   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 11:26:51.200   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 11:26:51.204   455   455 E Parcel  : Reading a NULL string not supported here.
,08-29 11:26:51.205   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 11:26:51.206   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:26:51.206   873  1303 E native  : do suspend true
08-29 11:26:51.208   873  1881 D DhcpClient: Receive thread stopped
08-29 11:26:51.208  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.208  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.208  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:26:51.208  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:26:51.210  2632  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 11:26:51.210  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:26:51.210  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:26:51.210  2632  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:26:51.210  2632  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:26:51.210  2632  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:26:51.210  2632  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:26:51.211  1513  3547 V NativeCrypto: SSL shutdown failed: ssl=0x9b3ffa00: I/O error during system call, Broken pipe
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:26:51.211  2632  2632 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:26:51.211  2632  2632 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:26:51.211  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:26:51.212  2632  2632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 11:26:51.212  2632  2632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:26:51.213  2632  2659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 11:26:51.213  2632  2659 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 11:26:51.212  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.213  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.215  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:26:51.215  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:26:51.216  2632  2632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:26:51.216  2632  2632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:26:51.217  2632  2632 D BluetoothMapService: MAP Service closeService in
08-29 11:26:51.217  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-29 11:26:51.217  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.217  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:26:51.218  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:26:51.218  2632  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 11:26:51.218  2632  2650 D BluetoothAdapterProperties: Setting state to 15
,08-29 11:26:51.218  2632  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 11:26:51.218  2632  2650 I BluetoothAdapterState: Entering BleOnState
08-29 11:26:51.219  1360  1372 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:26:51.219  1920  1930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:26:51.219   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:26:51.219  1360  2048 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:26:51.220  1360  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:26:51.220  2632  2632 D BluetoothMapService: cleanup()
,08-29 11:26:51.220  2632  2632 D BluetoothMapService: MAP Service closeService in
08-29 11:26:51.220   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:26:51.220  1360  2050 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:26:51.223   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:26:51.223  1360  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:26:51.224  1360  2048 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:26:51.225   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:26:51.225  2632  2650 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-29 11:26:51.225  2632  2650 D BluetoothAdapterProperties: Setting state to 16
08-29 11:26:51.225  2632  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 11:26:51.226  2632  2650 D BluetoothAdapterProperties: onBleDisable
08-29 11:26:51.226  2632  2650 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:26:51.227  2632  2652 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 11:26:51.228  2632  2750 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 11:26:51.228  2632  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:26:51.228  2632  2659 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:26:51.231  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:51.231  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:26:51.232  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.232  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:26:51.234  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:51.234  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:51.234  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.234  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:26:51.235  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:26:51.236  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:51.256   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:51.270  4073  4073 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 11:26:51.274   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:51.274   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:26:51.275   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 11:26:51.275   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:51.276   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 11:26:51.277   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:26:51.280  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:51.281  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:26:51.287  3564  3564 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@db4c4cb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 11:26:51.295   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:26:51.297   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 11:26:51.297  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:51.298  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:26:51.298  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.298  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:51.300  2149  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:26:51.300  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:51.300  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:51.300  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:51.300  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:51.303  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:26:51.307   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d4b3fc:true
,08-29 11:26:51.308  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-29 11:26:51.320   873  1934 I ActivityManager: Start proc 4093:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 11:26:51.326   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 11:26:51.328   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 11:26:51.333  4073  4073 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 11:26:51.335  4073  4073 D BluetoothMap: Create BluetoothMap proxy object
,08-29 11:26:51.342  4073  4073 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 11:26:51.353  4093  4093 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 11:26:51.354  4073  4073 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:26:51.359   873   883 I ActivityManager: Killing 3564:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 11:26:51.430  2632  2659 I bt_hci  : shut_down
,08-29 11:26:51.479  2632  2671 D bt_hwcfg: hw_epilog_process
08-29 11:26:51.480  2632  2671 I bt_vendor: low_power_mode_cb
,08-29 11:26:51.487  2632  2671 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 11:26:51.487  2632  2671 I bt_vendor: epilog_cb
,08-29 11:26:51.488  2632  2671 I bt_hci  : epilog_finished_callback
,08-29 11:26:51.491  2632  2659 I bt_hci_h4: hal_close
,08-29 11:26:51.491  2632  2659 I bt_userial_vendor: device fd = 51 close
,08-29 11:26:51.573  4093  4093 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
,08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.573  4093  4093 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(P,G:2265)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.573  4093  4093 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at c,om.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.573  4093  4093 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.573  4093  4093 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.573  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.574  4093  4093 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.574  4093  4093 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.574  4093  4093 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:26:51.574  4093  4093 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:26:51.581  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 11:26:51.587  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:26:51.589  4073  4073 D DockEventReceiver: finishStartingService: stopping service
08-29 11:26:51.600  4018  4018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 11:26:51.609   873   884 I ActivityManager: Killing 3723:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 11:26:51.662  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:26:51.668  2632  2652 D bt_stack_manager: event_shut_down_stack finished.
,08-29 11:26:51.669  2632  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 11:26:51.670  2632  2650 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 11:26:51.670  2632  2632 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:26:51.672  1707  1707 D SystemUpdateService: onCreate
08-29 11:26:51.671  2632  2632 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:26:51.672  2632  2632 D BtGatt.GattService: stop()
08-29 11:26:51.672  2632  2632 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:26:51.674  2632  2632 V BluetoothAdapterState: isTurningOff()=false
08-29 11:26:51.675  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-29 11:26:51.675  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:26:51.675  2632  2632 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 11:26:51.675  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:26:51.676  2632  2650 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 11:26:51.676  2632  2650 D BluetoothAdapterProperties: Setting state to 10
08-29 11:26:51.677  2632  2650 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 11:26:51.678  2632  2650 I BluetoothAdapterState: Entering OffState
08-29 11:26:51.679   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 11:26:51.680  1707  4123 I SystemUpdateService: active receiver: enabled
,08-29 11:26:51.688  1707  4123 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:26:51.690  1707  4123 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 11:26:51.690  1707  4123 I SystemUpdateService: now status is 0 (complete)
,08-29 11:26:51.690  1707  4123 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 11:26:51.690  1707  4123 I SystemUpdateService: file has been verified
08-29 11:26:51.690  1707  4123 I SystemUpdateService: OTA package size = 12249756
,08-29 11:26:51.699  2632  2632 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 11:26:51.699  2632  2632 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 11:26:51.699  2632  2632 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 11:26:51.701  2632  2652 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 11:26:51.701  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 11:26:51.703  1707  2437 I iu.UploadsManager: num queued entries: 0
,08-29 11:26:51.710  2632  2652 D bt_stack_manager: event_clean_up_stack finished.
,08-29 11:26:51.716  2632  2632 I art     : System.exit called, status: 0
08-29 11:26:51.716  2632  2632 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:26:51.719  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:26:51.720  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 11:26:51.721  1707  4123 I SystemUpdateService: showing system update notification
,08-29 11:26:51.731  1707  2437 I iu.UploadsManager: num updated entries: 0
,08-29 11:26:51.735   873  1934 I ActivityManager: Start proc 4126:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 11:26:51.755  1707  2437 I iu.SyncManager: NEXT; no task
,08-29 11:26:51.773   873  1958 I ActivityManager: Process com.android.bluetooth (pid 2632) has died
,08-29 11:26:51.779  1707  1707 D SystemUpdateService: onDestroy
,08-29 11:26:51.812  4126  4126 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 11:26:51.814  4126  4126 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:51.831  4126  4126 D SprintDMHelper: simOperator: 
,08-29 11:26:51.831  4126  4126 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:26:51.848  4093  4116 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 11:26:51.855   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1159ecf:true
,08-29 11:26:51.863   873  1958 I ActivityManager: Start proc 4141:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 11:26:51.864   873  1958 I ActivityManager: Killing 3609:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 11:26:52.030   873  1978 I ActivityManager: Start proc 4156:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 11:26:52.072  4156  4156 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 11:26:52.119  4156  4156 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 11:26:52.119  4156  4156 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 11:26:52.119  4156  4156 I GAv4    :   adb logcat -s GAv4
,08-29 11:26:52.139  4156  4156 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:26:52.146  4156  4156 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:26:52.175  4156  4174 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:26:52.291  4156  4156 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 11:26:52.333  4156  4156 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 11:26:52.340  4156  4156 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8549-8552)
,08-29 11:26:52.341  4156  4156 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 11:26:52.353  4156  4156 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce476bb}
,08-29 11:26:52.353  4156  4156 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:26:52.354  4156  4156 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:26:52.361  4156  4156 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 11:26:52.363  4156  4156 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 11:26:52.378  4156  4156 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 11:26:52.391  4156  4156 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 11:26:52.398  4156  4156 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:26:52.398  4156  4156 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 11:26:52.398  4156  4156 I Adreno  : Build Date                       : 10/20/15
08-29 11:26:52.398  4156  4156 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 11:26:52.398  4156  4156 I Adreno  : Local Branch                     : M14
08-29 11:26:52.398  4156  4156 I Adreno  : Remote Branch                    : 
08-29 11:26:52.398  4156  4156 I Adreno  : Remote Branch                    : 
08-29 11:26:52.398  4156  4156 I Adreno  : Reconstruct Branch               : 
,08-29 11:26:52.463  4156  4202 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 11:26:52.471  4156  4156 I NSApplication: Starting up...
,08-29 11:26:52.514   873  1699 I ActivityManager: Start proc 4207:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 11:26:52.515   873  1699 I ActivityManager: Killing 3652:android.process.acore/u0a5 (adj 15): empty #17
,08-29 11:26:52.590  4207  4207 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 11:26:52.772   873  1934 I ActivityManager: Killing 3831:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 11:26:52.874   873  1978 I ActivityManager: Start proc 4221:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 11:26:52.930  4221  4221 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 11:26:52.987  4221  4221 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 11:26:53.061   873  1977 I ActivityManager: Killing 3846:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 11:26:54.166   873  1958 D WifiService: setWifiEnabled: true pid=4018, uid=10000
,08-29 11:26:54.167   873  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:26:54.185   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-29 11:26:54.189  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:54.190  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:26:54.190  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:26:54.190  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:26:54.193  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:54.193  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:54.194  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:26:54.194  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:54.221   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-29 11:26:54.222   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 11:26:54.223   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 11:26:54.224   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 11:26:54.225   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 11:26:54.225   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 11:26:54.225   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 11:26:54.239   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 11:26:54.240   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 11:26:54.240   373   871 D CommandListener: Setting iface cfg
,08-29 11:26:54.241   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '138 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 138 Failed to set address (No such device)'
08-29 11:26:54.241   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 11:26:54.251   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 11:26:54.251   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-29 11:26:54.254   873  1303 E native  : do suspend true
,08-29 11:26:54.278   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:26:55.660   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 11:26:55.703   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.00 rxSuccessRate=14.81 delta 1000 -> 994
08-29 11:26:55.705   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 11:26:55.705   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:26:55.727   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 11:26:55.792   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 11:26:55.797  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 11:26:56.236  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:26:56.275  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 11:26:56.275  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-29 11:26:56.282   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:26:56.293   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 11:26:56.294   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:26:56.294   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 11:26:56.309   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:26:56.323   373   871 D CommandListener: Setting iface cfg
08-29 11:26:56.326   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 11:26:56.332   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 11:26:56.362   873  4257 D DhcpClient: Receive thread started
,08-29 11:26:56.444   873  1303 E native  : do suspend false
,08-29 11:26:56.453   873  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 11:26:56.473   873  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172620, domain null
,08-29 11:26:56.474   873  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172620 seconds
08-29 11:26:56.474   873  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 11:26:56.505   873  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 11:26:56.506   873  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 11:26:56.512   373   871 D CommandListener: Setting iface cfg
,08-29 11:26:56.524   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 11:26:56.528   873  1303 E native  : do suspend true
,08-29 11:26:56.529   873  1877 D DhcpClient: Scheduling renewal in 86399s
,08-29 11:26:56.543   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 11:26:56.544   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 11:26:56.545   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 11:26:56.547   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 11:26:56.548   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 11:26:56.614   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 11:26:56.615   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 11:26:56.617   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 11:26:56.619   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 11:26:56.621   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 11:26:56.637   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 11:26:56.650   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-29 11:26:56.651   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 11:26:56.651   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-29 11:26:56.651   873  1305 D ConnectivityService:    accepting network in place of null
08-29 11:26:56.651   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 11:26:56.652   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 11:26:56.652   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:26:56.698   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:56.726   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:56.731   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 11:26:56.731   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:56.734   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 11:26:56.737   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 11:26:56.748  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:56.748  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:26:56.748  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:56.749  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:56.751  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:26:56.751  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:26:56.751  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:56.752  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:26:56.758  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:26:56.760  1707  1707 D SystemUpdateService: onCreate
,08-29 11:26:56.765  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:26:56.767  1707  4270 I SystemUpdateService: active receiver: enabled
,08-29 11:26:56.770  1707  4270 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:26:56.775  1707  4270 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 11:26:56.775  1707  4270 I SystemUpdateService: now status is 0 (complete)
08-29 11:26:56.775  1707  4270 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 11:26:56.775  1707  4270 I SystemUpdateService: file has been verified
08-29 11:26:56.776  1707  4270 I SystemUpdateService: OTA package size = 12249756
,08-29 11:26:56.781  1707  4270 I SystemUpdateService: showing system update notification
,08-29 11:26:56.786  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 11:26:56.788  1707  2437 I iu.UploadsManager: num queued entries: 0
,08-29 11:26:56.789  1707  2437 I iu.UploadsManager: num updated entries: 0
,08-29 11:26:56.791  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 11:26:56.790  1707  2437 I iu.SyncManager: NEXT; no task
,08-29 11:26:56.794  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:26:56.795  1707  4273 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 11:26:56.795  1707  4273 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 11:26:56.797  1707  4273 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-29 11:26:56.798  1707  1707 D SystemUpdateService: onDestroy
,08-29 11:26:56.798  4126  4126 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:56.805  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:56.807  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:26:56.810  4126  4126 D SprintDMHelper: simOperator: 
,08-29 11:26:56.810  4126  4126 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:26:56.842  1513  2406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 11:26:56.842  1513  2406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 11:26:56.842  1513  2406 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:26:56.842  1513  2406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:26:56.857  1707  4273 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-29 11:26:57.173   873  1699 D WifiService: setWifiEnabled: false pid=4018, uid=10000
08-29 11:26:57.173   873  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:26:57.191  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:26:57.192   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 11:26:57.193   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 11:26:57.193   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:26:57.193   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:26:57.212   873  1303 E native  : do suspend true
,08-29 11:26:57.224   873  1877 D DhcpClient: Clearing IP address
,08-29 11:26:57.224   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:26:57.231   373   871 D CommandListener: Setting iface cfg
,08-29 11:26:57.237   873  4257 D DhcpClient: Receive thread stopped
,08-29 11:26:57.244   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 11:26:57.244   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 11:26:57.255   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 11:26:57.255   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:26:57.255   873  1303 E native  : do suspend true
08-29 11:26:57.256   455   455 E Parcel  : Reading a NULL string not supported here.
08-29 11:26:57.262   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 11:26:57.289   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:57.312   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:26:57.313   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:26:57.313   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 11:26:57.313   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:57.314  4221  4280 V GoogleAuthProtoRequest: [386] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 11:26:57.316   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 11:26:57.317  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:57.317  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:57.318  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.318  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:57.319   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 11:26:57.320  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:57.320  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:57.320  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.320  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:57.328  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:26:57.331  1707  1707 D SystemUpdateService: onCreate
,08-29 11:26:57.336  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:26:57.342   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:26:57.345  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:57.345  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:57.345  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.345  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:26:57.346  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:26:57.346  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:26:57.346  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:26:57.346  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:26:57.347  2149  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:26:57.348  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-29 11:26:57.350  1707  2437 I iu.UploadsManager: num queued entries: 0
,08-29 11:26:57.351  1707  2437 I iu.UploadsManager: num updated entries: 0
,08-29 11:26:57.351   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 11:26:57.360  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:26:57.365  1707  4286 I SystemUpdateService: active receiver: enabled
,08-29 11:26:57.365  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:26:57.367  4126  4126 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:26:57.372  4126  4126 D SprintDMHelper: simOperator: 
,08-29 11:26:57.372  4126  4126 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:26:57.375  1707  2437 I iu.SyncManager: NEXT; no task
,08-29 11:26:57.381  1707  4286 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:26:57.393  1707  4286 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 11:26:57.394  1707  4286 I SystemUpdateService: now status is 0 (complete)
,08-29 11:26:57.394  1707  4286 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 11:26:57.395  1707  4286 I SystemUpdateService: file has been verified
,08-29 11:26:57.395  1707  4286 I SystemUpdateService: OTA package size = 12249756
,08-29 11:26:57.423   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-29 11:26:57.425   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 11:26:57.426  1707  4286 I SystemUpdateService: showing system update notification
,08-29 11:26:57.432  1513  2291 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 11:26:57.432  1513  2291 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 11:26:57.432  1513  2291 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:26:57.432  1513  2291 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:26:57.461  1707  1707 D SystemUpdateService: onDestroy
,08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 11:26:57.467  4221  4280 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 11:26:57.730   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 11:27:00.219   873   890 I ActivityManager: Start proc 4294:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 11:27:00.345  4294  4294 D AdapterServiceConfig: Adding HeadsetService
,08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding A2dpService
08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding HidService
,08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding HealthService
08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding PanService
08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding GattService
,08-29 11:27:00.346  4294  4294 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 11:27:00.357   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90a3267:true
,08-29 11:27:00.358  4294  4294 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 11:27:00.364  4294  4294 I bt_bluedroid: init
,08-29 11:27:00.365  4294  4306 I BluetoothAdapterState: Entering OffState
,08-29 11:27:00.367  4294  4307 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:27:00.367  4294  4307 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:27:00.367  4294  4307 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:27:00.367  4294  4307 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 11:27:00.368  4294  4294 I bt_bluedroid: get_profile_interface socket
08-29 11:27:00.369  4294  4294 I bt_bluedroid: get_profile_interface sdp
,08-29 11:27:00.373  4294  4310 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:27:00.376  4294  4305 I bt_bluedroid: config_hci_snoop_log
08-29 11:27:00.381  4294  4310 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:27:00.382   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 11:27:00.395  4294  4306 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 11:27:00.396  4294  4306 D BluetoothAdapterProperties: Setting state to 14
,08-29 11:27:00.397  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 11:27:00.402  4294  4306 D BluetoothBondStateMachine: make
,08-29 11:27:00.405  4294  4311 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:27:00.411  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:27:00.411  4294  4294 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-29 11:27:00.413  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:00.414  4294  4294 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:27:00.414  4294  4294 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:27:00.414  4294  4294 D BtGatt.GattService: start()
08-29 11:27:00.415  4294  4294 I bt_bluedroid: get_profile_interface gatt
08-29 11:27:00.415  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:00.415  4294  4294 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:27:00.424  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:27:00.424  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:00.424  4294  4294 V BluetoothAdapterState: isBleTurningOn()=true
08-29 11:27:00.424  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:00.425  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 11:27:00.426  4294  4306 I bt_bluedroid: enable
,08-29 11:27:00.427  4294  4307 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 11:27:00.427  4294  4307 I bt_hci  : start_up
,08-29 11:27:00.432  4294  4307 I bt_vendor: alloc value 0xb3a14189
,08-29 11:27:00.432  4294  4307 I bt_vendor: init
08-29 11:27:00.432  4294  4307 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 11:27:00.432  4294  4307 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 11:27:00.539  4294  4307 D bt_hci  : start_up starting async portion
,08-29 11:27:00.539  4294  4314 I bt_hci  : event_finish_startup
08-29 11:27:00.539  4294  4314 I bt_hci_h4: hal_open
08-29 11:27:00.539  4294  4314 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 11:27:00.548  4294  4314 I bt_userial_vendor: device fd = 51 open
,08-29 11:27:00.582  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:27:00.614  4294  4314 D bt_hwcfg: Chipset BCM4354A2
,08-29 11:27:00.614  4294  4314 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 11:27:00.615  4294  4314 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 11:27:01.269  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 11:27:01.270  4294  4314 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 11:27:01.272  4294  4314 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 11:27:01.388  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:27:01.390  4294  4314 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 11:27:01.418  4294  4314 I bt_hwcfg: vendor lib fwcfg completed
,08-29 11:27:01.419  4294  4314 I bt_vendor: firmware callback
08-29 11:27:01.419  4294  4314 I bt_hci  : firmware_config_callback
,08-29 11:27:01.432  4294  4316 I bt_btu  : btu_task pending for preload complete event
,08-29 11:27:01.432  4294  4316 I bt_btu_task: Bluetooth chip preload is complete
,08-29 11:27:01.432  4294  4316 I bt_btu  : btu_task received preload complete event
,08-29 11:27:01.442  4294  4316 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:27:01.443  4294  4316 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 11:27:01.443  4294  4316 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 11:27:01.443  4294  4316 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:27:01.444  4294  4316 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:27:01.444  4294  4316 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 11:27:01.444  4294  4316 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:27:01.444  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 11:27:01.445  4294  4316 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:27:01.445  4294  4316 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:27:01.445  4294  4316 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 11:27:01.445  4294  4316 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:27:01.446  4294  4316 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:27:01.446  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:27:01.446  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:27:01.579  4294  4316 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3991d9d
,08-29 11:27:01.579  4294  4316 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3991d9d 
,08-29 11:27:01.590  4294  4310 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 11:27:01.591  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 11:27:01.592  4294  4310 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:27:01.597  4294  4310 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:27:01.602  4294  4310 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:27:01.603  4294  4310 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:27:01.603  4294  4310 D bt_hci  : do_postload posting postload work item
08-29 11:27:01.604  4294  4314 I bt_hci  : event_postload
08-29 11:27:01.604  4294  4314 I bt_vendor: sco_config_cb
,08-29 11:27:01.604  4294  4314 I bt_hci  : sco_config_callback postload finished.
,08-29 11:27:01.608  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:01.610  4294  4310 D bt_bte_conf: Device ID record 1 : primary
08-29 11:27:01.611  4294  4310 D bt_bte_conf:   vendorId            = 000f
08-29 11:27:01.611  4294  4314 I bt_vendor: low_power_mode_cb
,08-29 11:27:01.611  4294  4310 D bt_bte_conf:   vendorIdSource      = 0001
08-29 11:27:01.611  4294  4310 D bt_bte_conf:   product             = 1200
,08-29 11:27:01.612  4294  4310 D bt_bte_conf:   version             = 1436
08-29 11:27:01.612  4294  4310 D bt_bte_conf:   clientExecutableURL = 
08-29 11:27:01.612  4294  4310 D bt_bte_conf:   serviceDescription  = 
08-29 11:27:01.612  4294  4310 D bt_bte_conf:   documentationURL    = 
08-29 11:27:01.612  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:01.613  4294  4310 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 11:27:01.613  4294  4307 D bt_stack_manager: event_start_up_stack finished
08-29 11:27:01.617  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 11:27:01.619  4294  4306 D BluetoothAdapterProperties: Setting state to 15
08-29 11:27:01.619  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 11:27:01.620  4294  4306 I BluetoothAdapterState: Entering BleOnState
,08-29 11:27:01.623  4294  4306 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 11:27:01.623  4294  4306 D BluetoothAdapterProperties: Setting state to 11
08-29 11:27:01.623  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 11:27:01.632  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:01.634  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:01.642  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:01.643  4294  4294 D HeadsetService: Received start request. Starting profile...
08-29 11:27:01.645  4294  4294 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:27:01.646  4294  4294 D HeadsetStateMachine: make
,08-29 11:27:01.649  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:27:01.654  4294  4294 D HeadsetStateMachine: max_hf_connections = 1,
08-29 11:27:01.654  4294  4294 I bt_bluedroid: get_profile_interface handsfree
,08-29 11:27:01.655  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 11:27:01.655  4294  4310 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 11:27:01.660   873  4255 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 11:27:01.660  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:01.660  4294  4294 D A2dpService: Received start request. Starting profile...
08-29 11:27:01.660   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 11:27:01.661  4294  4294 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:27:01.662  4294  4294 I bt_bluedroid: get_profile_interface avrcp
08-29 11:27:01.662  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:27:01.668  4294  4294 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:27:01.669  4294  4294 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:27:01.669  4294  4294 D A2dpStateMachine: make
,08-29 11:27:01.670  4294  4294 I bt_bluedroid: get_profile_interface a2dp
,08-29 11:27:01.670  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 11:27:01.672  4294  4324 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:27:01.673  4294  4294 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:27:01.674  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:01.675  4294  4294 D HidService: Received start request. Starting profile...
,08-29 11:27:01.675  4073  4073 D BluetoothInputDevice: Proxy object connected
08-29 11:27:01.675  4294  4294 I bt_bluedroid: get_profile_interface hidhost
08-29 11:27:01.675  4294  4310 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39733e5
08-29 11:27:01.675  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 11:27:01.676  4294  4294 D HidService: setHidService(): set to: null
08-29 11:27:01.676  4073  4073 D HidProfile: Bluetooth service connected
08-29 11:27:01.676  4294  4294 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:27:01.677  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:01.678  4294  4294 D HealthService: Received start request. Starting profile...
08-29 11:27:01.679  4294  4294 I bt_bluedroid: get_profile_interface health
,08-29 11:27:01.680  4294  4294 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:27:01.681  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:01.682  4294  4294 D PanService: Received start request. Starting profile...
,08-29 11:27:01.682  4073  4073 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:27:01.683  4294  4294 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:27:01.683  4294  4294 I bt_bluedroid: get_profile_interface pan
,08-29 11:27:01.683  4294  4310 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 11:27:01.684  4073  4073 D PanProfile: Bluetooth service connected
,08-29 11:27:01.686  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:01.688  4294  4294 D BluetoothMapService: Received start request. Starting profile...
,08-29 11:27:01.688  4294  4294 D BluetoothMapService: start()
,08-29 11:27:01.688  4073  4073 D BluetoothMap: Proxy object connected
,08-29 11:27:01.689  4073  4073 D MapProfile: Bluetooth service connected
,08-29 11:27:01.689  4073  4073 D BluetoothMap: getConnectedDevices()
,08-29 11:27:01.690  4294  4294 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 11:27:01.691  4073  4073 D BluetoothMap: Bluetooth is Not enabled
,08-29 11:27:01.691  4294  4294 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 11:27:01.691  4294  4294 D BluetoothMapAppObserver: createReceiver()
,08-29 11:27:01.693  4294  4294 D BluetoothMapAppObserver: initObservers()
,08-29 11:27:01.693  4294  4294 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 11:27:01.704  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:27:01.704  4294  4294 V BluetoothAdapterState: isTurningOn()=true
,08-29 11:27:01.704  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:27:01.704  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:01.706  4294  4322 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 11:27:01.708  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:27:01.708  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:01.708  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:01.708  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:01.709  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:27:01.710  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:01.710  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 11:27:01.710  4294  4306 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:27:01.710  4294  4306 D BluetoothAdapterProperties: State =  11
08-29 11:27:01.713  4294  4310 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:27:01.713  4294  4306 D BluetoothAdapterProperties: Setting state to 12
08-29 11:27:01.713  4294  4310 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:27:01.713  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:27:01.713  4294  4306 I BluetoothAdapterState: Entering OnState
08-29 11:27:01.714  4073  4083 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:27:01.714  4073  4084 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:27:01.715  1360  1379 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:27:01.717  1360  1360 D BluetoothMap: Proxy object connected
08-29 11:27:01.717  1360  1360 D MapProfile: Bluetooth service connected
08-29 11:27:01.717  1360  1360 D BluetoothMap: getConnectedDevices()
08-29 11:27:01.717  4073  4083 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:27:01.717  1920  3381 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:01.718   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:01.718  1360  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:01.719  1360  2050 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:01.719  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:01.720  1360  1360 D BluetoothInputDevice: Proxy object connected
08-29 11:27:01.720  1360  1360 D HidProfile: Bluetooth service connected
08-29 11:27:01.721   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:01.721  4294  4294 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:27:01.721  1360  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:27:01.722  4294  4294 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 11:27:01.722  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:01.725  4294  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:01.726  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:01.726   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:01.727  1360  1372 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:27:01.728  4294  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:01.728  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:01.729  1360  2048 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:27:01.729  4294  4294 D ObexServerSockets: Succeed to create listening sockets 
08-29 11:27:01.730  4294  4294 D ObexServerSockets0: startAccept()
08-29 11:27:01.730  4294  4294 D ObexServerSockets0: prepareForNewConnect()
08-29 11:27:01.732  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:27:01.732   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:27:01.732  1360  1360 D PanProfile: Bluetooth service connected
08-29 11:27:01.733  4073  4084 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:27:01.733  4294  4294 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 11:27:01.733  4294  4294 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 11:27:01.734  4294  4332 D ObexServerSockets0: Accepting socket connection...
08-29 11:27:01.734  4294  4333 D ObexServerSockets0: Accepting socket connection...
08-29 11:27:01.738  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:01.739   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 11:27:01.739  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:01.740  4294  4294 D BluetoothMapService: onReceive
08-29 11:27:01.740  4294  4294 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:27:01.740  4294  4294 D BluetoothMapService: STATE_ON
08-29 11:27:01.740  1360  1360 D BluetoothA2dp: Proxy object connected
08-29 11:27:01.741   873   873 D BluetoothA2dp: Proxy object connected
08-29 11:27:01.741  4073  4073 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 11:27:01.744  4073  4073 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 11:27:01.750  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,08-29 11:27:01.753  4073  4073 D BluetoothA2dp: Proxy object connected,
,08-29 11:27:01.756  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-29 11:27:01.763  4073  4073 D DockEventReceiver: finishStartingService: stopping service,
,08-29 11:27:01.766  1360  1360 D BluetoothPbap: Proxy object connected
,08-29 11:27:01.766  1360  1360 D PbapServerProfile: Bluetooth service connected
08-29 11:27:01.767  4073  4073 D BluetoothPbap: Proxy object connected
08-29 11:27:01.767  4073  4073 D PbapServerProfile: Bluetooth service connected
08-29 11:27:01.767  4294  4294 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:27:01.767  4294  4294 D ObexServerSockets0: prepareForNewConnect()
,08-29 11:27:01.774  4294  4337 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:01.793  4294  4341 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:01.796  4294  4341 I BtOppRfcommListener: Accept thread started.
,08-29 11:27:01.818   873   873 D BluetoothHeadset: Proxy object connected
,08-29 11:27:01.819   873   890 D BluetoothHeadset: Proxy object connected
08-29 11:27:01.819   873   873 D BluetoothHeadset: Proxy object connected
,08-29 11:27:01.819  1360  1379 D BluetoothHeadset: Proxy object connected
08-29 11:27:01.819  1360  1360 D HeadsetProfile: Bluetooth service connected
08-29 11:27:01.819  1360  1379 D BluetoothHeadset: Proxy object connected
08-29 11:27:01.820   873   873 D BluetoothHeadset: Proxy object connected,
,08-29 11:27:01.821  1920  1932 D BluetoothHeadset: Proxy object connected
08-29 11:27:01.821  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-29 11:27:01.822   873   890 D BluetoothHeadset: Proxy object connected
,08-29 11:27:01.826   873   890 D BluetoothHeadset: Proxy object connected
,08-29 11:27:01.839  2476  4275 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-29 11:27:01.840  2476  4275 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 11:27:01.844  2476  4275 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 11:27:01.847  4073  4083 D BluetoothHeadset: Proxy object connected
,08-29 11:27:01.849  4073  4073 D HeadsetProfile: Bluetooth service connected
,08-29 11:27:01.852   873  1978 I ActivityManager: Killing 2232:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 11:27:03.190  4294  4306 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 11:27:03.191  4294  4306 D BluetoothAdapterProperties: Setting state to 13
,08-29 11:27:03.191  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 11:27:03.193  4294  4306 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:27:03.196  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:27:03.200  4294  4294 D BluetoothMapService: onReceive
08-29 11:27:03.201  4294  4294 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:27:03.201  4294  4294 D BluetoothMapService: STATE_TURNING_OFF
,08-29 11:27:03.202  4294  4294 D BluetoothMapService: MAP Service closeService in
,08-29 11:27:03.202  4294  4294 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 11:27:03.203  4294  4294 D ObexServerSockets0: shutdown(block = true)
,08-29 11:27:03.204  4294  4332 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 11:27:03.206  4294  4310 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:27:03.208  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:03.208  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:03.208  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 11:27:03.208  4294  4294 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:27:03.209  4294  4319 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 11:27:03.209  4294  4333 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 11:27:03.210  4294  4294 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:27:03.212  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:27:03.212  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:03.215  4294  4294 I BtOppRfcommListener: stopping Accept Thread
,08-29 11:27:03.218  4294  4341 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:27:03.218  4294  4341 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:27:03.222  4294  4294 D HeadsetService: Received stop request...Stopping profile...
08-29 11:27:03.223   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 11:27:03.223   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 11:27:03.223  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:03.223  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:03.223  1360  1379 D BluetoothHeadset: Proxy object disconnected
08-29 11:27:03.224   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 11:27:03.224  4073  4084 D BluetoothHeadset: Proxy object disconnected
08-29 11:27:03.224  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-29 11:27:03.224  1920  1930 D BluetoothHeadset: Proxy object disconnected
08-29 11:27:03.225  4018  4018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:27:03.225  4294  4294 D A2dpService: Received stop request...Stopping profile...
08-29 11:27:03.225  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:03.225  4294  4324 D A2dpStateMachine: Exit Disconnected: -1
,08-29 11:27:03.225  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 11:27:03.227  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:03.227   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 11:27:03.227  4294  4294 D HidService: Received stop request...Stopping profile...
08-29 11:27:03.228  4294  4294 D HidService: Stopping Bluetooth HidService
08-29 11:27:03.228  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:03.235  4073  4073 D HeadsetProfile: Bluetooth service disconnected
,08-29 11:27:03.235  4294  4294 D HealthService: Received stop request...Stopping profile...
,08-29 11:27:03.236  4073  4073 D BluetoothA2dp: Proxy object disconnected
08-29 11:27:03.236  4294  4294 V BluetoothAdapterState: isTurningOff()=true
08-29 11:27:03.236  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.237  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.237  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:03.238  4294  4294 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 11:27:03.238  4294  4294 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 11:27:03.239  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:27:03.239  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:27:03.239  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:27:03.239  4294  4294 D PanService: Received stop request...Stopping profile...
08-29 11:27:03.239  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 11:27:03.240  4294  4310 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-29 11:27:03.241  4294  4294 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 11:27:03.241  4294  4294 D BluetoothMapService: stop()
,08-29 11:27:03.242  4294  4294 D BluetoothMapAppObserver: deinitObservers()
08-29 11:27:03.242  4294  4294 D BluetoothMapAppObserver: removeReceiver()
08-29 11:27:03.243  1360  1360 D BluetoothA2dp: Proxy object disconnected,
,08-29 11:27:03.243  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-29 11:27:03.243  4294  4294 V BluetoothAdapterState: isTurningOff()=true
,08-29 11:27:03.243  1360  1360 D HidProfile: Bluetooth service disconnected
,08-29 11:27:03.243  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.243  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.244  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:03.244  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 11:27:03.244  1360  1360 D PanProfile: Bluetooth service disconnected
08-29 11:27:03.244  4073  4073 D DockEventReceiver: finishStartingService: stopping service
08-29 11:27:03.244  1360  1360 D BluetoothMap: Proxy object disconnected
08-29 11:27:03.244  1360  1360 D MapProfile: Bluetooth service disconnected
,08-29 11:27:03.245  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 11:27:03.245  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:27:03.245  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:27:03.245  4294  4316 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 11:27:03.245  4294  4316 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:27:03.245  4294  4316 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:27:03.245  4294  4316 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:27:03.245  4073  4073 D BluetoothInputDevice: Proxy object disconnected
08-29 11:27:03.245  4073  4073 D HidProfile: Bluetooth service disconnected
,08-29 11:27:03.246  4073  4073 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:27:03.246  4073  4073 D PanProfile: Bluetooth service disconnected
08-29 11:27:03.246  4073  4073 D BluetoothMap: Proxy object disconnected
08-29 11:27:03.246  4073  4073 D MapProfile: Bluetooth service disconnected
08-29 11:27:03.245  4294  4294 V BluetoothAdapterState: isTurningOff()=true
,08-29 11:27:03.248  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.248  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.248  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:03.248  4294  4294 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:27:03.248  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 11:27:03.248  4294  4294 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:27:03.250  4294  4294 V BluetoothAdapterState: isTurningOff()=true
08-29 11:27:03.250  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.250  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.250  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:03.250  4294  4294 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:27:03.250  4294  4310 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 11:27:03.251  4294  4294 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 11:27:03.251  4294  4294 V BluetoothAdapterState: isTurningOff()=true
08-29 11:27:03.251  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.251  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.251  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:03.251  4294  4294 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 11:27:03.252  4294  4294 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 11:27:03.253  4294  4294 D BluetoothMapService: MAP Service closeService in
08-29 11:27:03.253  4294  4294 V BluetoothAdapterState: isTurningOff()=true
08-29 11:27:03.253  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-29 11:27:03.253  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.253  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:03.254  4294  4294 D BluetoothMapService: cleanup()
,08-29 11:27:03.254  4294  4294 D BluetoothMapService: MAP Service closeService in
08-29 11:27:03.254  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 11:27:03.254  4294  4306 D BluetoothAdapterProperties: Setting state to 15
08-29 11:27:03.255  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 11:27:03.256  1360  1360 D BluetoothPbap: Proxy object disconnected
,08-29 11:27:03.256  1360  1360 D PbapServerProfile: Bluetooth service disconnected
08-29 11:27:03.256  4294  4306 I BluetoothAdapterState: Entering BleOnState
08-29 11:27:03.257  4073  4345 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:27:03.257  4073  4073 D BluetoothPbap: Proxy object disconnected
08-29 11:27:03.258  4073  4346 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:27:03.258  4073  4073 D PbapServerProfile: Bluetooth service disconnected
08-29 11:27:03.259  4073  4083 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:27:03.259  4073  4084 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 11:27:03.259  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:27:03.259  1360  1379 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:27:03.263  4073  4345 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:27:03.265  1920  2196 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:27:03.265   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:27:03.265  1360  2050 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:27:03.266  1360  2048 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:27:03.266   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:27:03.266  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:27:03.267   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 11:27:03.267  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:27:03.269  1360  2050 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:27:03.270   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:27:03.270  4073  4346 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:27:03.271  4294  4306 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 11:27:03.271  4294  4306 D BluetoothAdapterProperties: Setting state to 16
08-29 11:27:03.271  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 11:27:03.272  4294  4306 D BluetoothAdapterProperties: onBleDisable
08-29 11:27:03.272  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:27:03.273  4294  4307 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 11:27:03.274  4294  4316 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 11:27:03.274  4294  4316 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:27:03.274  4294  4310 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:27:03.276  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:03.278  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:03.280  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:03.280  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:27:03.281  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:03.285  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:27:03.289  4073  4073 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:27:03.475  4294  4310 I bt_hci  : shut_down
,08-29 11:27:03.475  4294  4314 D bt_hwcfg: hw_epilog_process
,08-29 11:27:03.487  4294  4314 I bt_vendor: low_power_mode_cb
,08-29 11:27:03.511  4294  4314 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 11:27:03.512  4294  4314 I bt_vendor: epilog_cb
08-29 11:27:03.512  4294  4314 I bt_hci  : epilog_finished_callback
,08-29 11:27:03.519  4294  4310 I bt_hci_h4: hal_close
,08-29 11:27:03.520  4294  4310 I bt_userial_vendor: device fd = 51 close
,08-29 11:27:03.640  4294  4307 D bt_stack_manager: event_shut_down_stack finished.
,08-29 11:27:03.641  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 11:27:03.647  4294  4306 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 11:27:03.647  4294  4294 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:27:03.648  4294  4294 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:27:03.649  4294  4294 D BtGatt.GattService: stop()
,08-29 11:27:03.649  4294  4294 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:27:03.654  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:27:03.654  4294  4294 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:27:03.654  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:03.655  4294  4294 V BluetoothAdapterState: isBleTurningOff()=true
08-29 11:27:03.656  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 11:27:03.656  4294  4306 D BluetoothAdapterProperties: Setting state to 10
,08-29 11:27:03.656  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 11:27:03.658  4294  4306 I BluetoothAdapterState: Entering OffState
,08-29 11:27:03.660   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 11:27:03.681  4294  4294 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 11:27:03.681  4294  4294 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 11:27:03.681  4294  4307 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 11:27:03.685  4294  4307 D bt_stack_manager: event_clean_up_stack finished.
,08-29 11:27:03.685  4294  4294 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 11:27:03.688  4294  4294 I art     : System.exit called, status: 0
,08-29 11:27:03.688  4294  4294 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:27:03.753   873   883 I ActivityManager: Process com.android.bluetooth (pid 4294) has died
,08-29 11:27:04.654   873  1305 D ConnectivityService: handlePromptUnvalidated 101
,08-29 11:27:06.187  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:27:06.188  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:09.198  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:09.198  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8869366 added. We now have 6 listener(s)
08-29 11:27:09.199  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:27:09.203  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:09.203  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@91a06a7 added. We now have 7 listener(s)
08-29 11:27:09.204  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:09.205  4018  4065 I System.out: IsBluetoothEnabled
,08-29 11:27:09.213  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:09.239   873   890 I ActivityManager: Start proc 4353:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 11:27:09.390  4353  4353 D AdapterServiceConfig: Adding HeadsetService
,08-29 11:27:09.390  4353  4353 D AdapterServiceConfig: Adding A2dpService
,08-29 11:27:09.390  4353  4353 D AdapterServiceConfig: Adding HidService
,08-29 11:27:09.390  4353  4353 D AdapterServiceConfig: Adding HealthService
,08-29 11:27:09.391  4353  4353 D AdapterServiceConfig: Adding PanService
,08-29 11:27:09.391  4353  4353 D AdapterServiceConfig: Adding GattService
,08-29 11:27:09.391  4353  4353 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 11:27:09.407  4353  4353 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 11:27:09.407   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d5ed228:true
,08-29 11:27:09.412  4353  4353 I bt_bluedroid: init
,08-29 11:27:09.412  4353  4365 I BluetoothAdapterState: Entering OffState
,08-29 11:27:09.418  4353  4366 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 11:27:09.418  4353  4366 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:27:09.418  4353  4366 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 11:27:09.419  4353  4366 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 11:27:09.421  4353  4353 I bt_bluedroid: get_profile_interface socket
,08-29 11:27:09.422  4353  4353 I bt_bluedroid: get_profile_interface sdp
08-29 11:27:09.426  4353  4369 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:27:09.427  4353  4364 I bt_bluedroid: config_hci_snoop_log
,08-29 11:27:09.429  4353  4369 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:27:09.432   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 11:27:09.442  4353  4365 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 11:27:09.442  4353  4365 D BluetoothAdapterProperties: Setting state to 14
08-29 11:27:09.443  4353  4365 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 11:27:09.447  4353  4365 D BluetoothBondStateMachine: make
,08-29 11:27:09.453  4353  4370 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:27:09.460  4353  4365 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:27:09.462  4353  4353 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 11:27:09.467  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:09.468  4353  4353 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:27:09.469  4353  4353 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:27:09.469  4353  4353 D BtGatt.GattService: start()
08-29 11:27:09.470  4353  4353 I bt_bluedroid: get_profile_interface gatt
,08-29 11:27:09.471  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:09.471  4353  4353 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:27:09.485  4353  4353 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:27:09.486  4353  4353 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:27:09.486  4353  4353 V BluetoothAdapterState: isBleTurningOn()=true
08-29 11:27:09.486  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:09.487  4353  4365 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 11:27:09.488  4353  4365 I bt_bluedroid: enable
08-29 11:27:09.488  4353  4366 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 11:27:09.489  4353  4366 I bt_hci  : start_up
,08-29 11:27:09.510  4353  4366 I bt_vendor: alloc value 0xb3a14189
,08-29 11:27:09.510  4353  4366 I bt_vendor: init
08-29 11:27:09.510  4353  4366 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 11:27:09.510  4353  4366 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 11:27:09.617  4353  4366 D bt_hci  : start_up starting async portion
,08-29 11:27:09.617  4353  4374 I bt_hci  : event_finish_startup
,08-29 11:27:09.617  4353  4374 I bt_hci_h4: hal_open
08-29 11:27:09.618  4353  4374 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 11:27:09.626  4353  4374 I bt_userial_vendor: device fd = 51 open
,08-29 11:27:09.659  4353  4374 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:27:09.690  4353  4374 D bt_hwcfg: Chipset BCM4354A2
,08-29 11:27:09.691  4353  4374 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 11:27:09.692  4353  4374 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 11:27:10.346  4353  4374 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 11:27:10.347  4353  4374 D bt_hwcfg: Settlement delay -- 100 ms
08-29 11:27:10.348  4353  4374 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 11:27:10.464  4353  4374 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:27:10.466  4353  4374 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 11:27:10.496  4353  4374 I bt_hwcfg: vendor lib fwcfg completed
,08-29 11:27:10.496  4353  4374 I bt_vendor: firmware callback
08-29 11:27:10.496  4353  4374 I bt_hci  : firmware_config_callback
,08-29 11:27:10.507  4353  4376 I bt_btu  : btu_task pending for preload complete event
,08-29 11:27:10.507  4353  4376 I bt_btu_task: Bluetooth chip preload is complete
08-29 11:27:10.508  4353  4376 I bt_btu  : btu_task received preload complete event
,08-29 11:27:10.520  4353  4376 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:27:10.520  4353  4376 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:27:10.521  4353  4376 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:27:10.521  4353  4376 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 11:27:10.521  4353  4376 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:27:10.522  4353  4376 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:27:10.522  4353  4376 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:27:10.522  4353  4376 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 11:27:10.522  4353  4376 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:27:10.523  4353  4376 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:27:10.523  4353  4376 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 11:27:10.523  4353  4376 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:27:10.523  4353  4376 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 11:27:10.523  4353  4376 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:27:10.524  4353  4376 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:27:10.654  4353  4376 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3991d9d
08-29 11:27:10.655  4353  4376 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3991d9d 
,08-29 11:27:10.667  4353  4369 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 11:27:10.670  4353  4369 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 11:27:10.672  4353  4369 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:27:10.676  4353  4369 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:27:10.679  4353  4369 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:27:10.679  4353  4369 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:27:10.682  4353  4369 D bt_hci  : do_postload posting postload work item
08-29 11:27:10.682  4353  4374 I bt_hci  : event_postload
08-29 11:27:10.683  4353  4374 I bt_vendor: sco_config_cb
08-29 11:27:10.683  4353  4374 I bt_hci  : sco_config_callback postload finished.
,08-29 11:27:10.683  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:10.689  4353  4374 I bt_vendor: low_power_mode_cb
08-29 11:27:10.688  4353  4369 D bt_bte_conf: Device ID record 1 : primary
,08-29 11:27:10.689  4353  4369 D bt_bte_conf:   vendorId            = 000f
08-29 11:27:10.689  4353  4369 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 11:27:10.689  4353  4369 D bt_bte_conf:   product             = 1200
08-29 11:27:10.689  4353  4369 D bt_bte_conf:   version             = 1436
,08-29 11:27:10.690  4353  4369 D bt_bte_conf:   clientExecutableURL = 
08-29 11:27:10.690  4353  4369 D bt_bte_conf:   serviceDescription  = 
08-29 11:27:10.690  4353  4369 D bt_bte_conf:   documentationURL    = 
,08-29 11:27:10.690  4353  4369 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 11:27:10.691  4353  4366 D bt_stack_manager: event_start_up_stack finished,
08-29 11:27:10.691  4353  4365 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 11:27:10.692  4353  4365 D BluetoothAdapterProperties: Setting state to 15
08-29 11:27:10.692  4353  4365 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 11:27:10.693  4353  4365 I BluetoothAdapterState: Entering BleOnState
,08-29 11:27:10.698  4353  4365 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 11:27:10.698  4353  4365 D BluetoothAdapterProperties: Setting state to 11
08-29 11:27:10.698  4353  4365 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 11:27:10.703  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:10.704  4353  4353 D HeadsetService: Received start request. Starting profile...
,08-29 11:27:10.709  4353  4353 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 11:27:10.710  4353  4353 D HeadsetStateMachine: make
,08-29 11:27:10.712  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:10.721  4353  4353 D HeadsetStateMachine: max_hf_connections = 1
,08-29 11:27:10.721  4353  4353 I bt_bluedroid: get_profile_interface handsfree
08-29 11:27:10.722  4353  4369 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 11:27:10.722  4353  4369 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-29 11:27:10.726  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:10.726  4353  4353 D A2dpService: Received start request. Starting profile...
08-29 11:27:10.726  4353  4365 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:27:10.727  4353  4353 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:27:10.727  4353  4353 I bt_bluedroid: get_profile_interface avrcp
,08-29 11:27:10.734  4353  4353 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:27:10.734  4353  4353 I BluetoothA2dpServiceJni: classInitNative: succeeds,
08-29 11:27:10.735  4353  4353 D A2dpStateMachine: make
,08-29 11:27:10.736  4353  4353 I bt_bluedroid: get_profile_interface a2dp
,08-29 11:27:10.737  4353  4369 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 11:27:10.740  4353  4385 D A2dpStateMachine: Enter Disconnected: -2
,08-29 11:27:10.741  4353  4353 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 11:27:10.742  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:10.743  4353  4353 D HidService: Received start request. Starting profile...
,08-29 11:27:10.743  4353  4353 I bt_bluedroid: get_profile_interface hidhost
,08-29 11:27:10.744  4353  4369 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39733e5
08-29 11:27:10.744  4353  4353 D HidService: setHidService(): set to: null
,08-29 11:27:10.744  4353  4369 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 11:27:10.746  4353  4353 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:27:10.747  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:10.747  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:27:10.749  4353  4353 D HealthService: Received start request. Starting profile...
,08-29 11:27:10.751  4353  4353 I bt_bluedroid: get_profile_interface health
,08-29 11:27:10.753  4353  4353 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 11:27:10.754  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:10.755  4353  4353 D PanService: Received start request. Starting profile...
,08-29 11:27:10.755  4353  4353 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:27:10.755  4353  4353 I bt_bluedroid: get_profile_interface pan
,08-29 11:27:10.756  4353  4369 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:27:10.758  4353  4382 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 11:27:10.759  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.759  4353  4353 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:10.759  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:10.759  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:10.763  4353  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
08-29 11:27:10.764  4353  4353 D BluetoothMapService: Received start request. Starting profile...
08-29 11:27:10.764  4353  4353 D BluetoothMapService: start()
,08-29 11:27:10.767  4353  4353 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 11:27:10.767  4353  4353 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 11:27:10.768  4353  4353 D BluetoothMapAppObserver: createReceiver()
,08-29 11:27:10.769  4353  4353 D BluetoothMapAppObserver: initObservers()
08-29 11:27:10.769  4353  4353 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 11:27:10.776  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.776  4353  4353 V BluetoothAdapterState: isTurningOn()=true
,08-29 11:27:10.776  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:10.776  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:10.776  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.777  4353  4353 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:10.777  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:10.777  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:27:10.777  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.778  4353  4353 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:10.778  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:10.778  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:10.778  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.778  4353  4353 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isTurningOff()=false
08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isTurningOn()=true
08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:27:10.779  4353  4353 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:27:10.780  4353  4365 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 11:27:10.780  4353  4365 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:27:10.780  4353  4365 D BluetoothAdapterProperties: State =  11
,08-29 11:27:10.780  4353  4365 D BluetoothAdapterProperties: Setting state to 12
08-29 11:27:10.780  4353  4365 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:27:10.781  4073  4345 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:27:10.782  4353  4365 I BluetoothAdapterState: Entering OnState
08-29 11:27:10.784  4353  4369 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:27:10.784  4353  4369 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:27:10.788  4073  4083 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:10.790  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:10.790  4073  4084 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:27:10.793  4073  4345 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:10.793  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:10.794  4073  4073 D BluetoothInputDevice: Proxy object connected
08-29 11:27:10.794  4073  4073 D HidProfile: Bluetooth service connected
08-29 11:27:10.794  1360  2048 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:27:10.797  4353  4353 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:27:10.798  4073  4073 D BluetoothA2dp: Proxy object connected
08-29 11:27:10.798  4353  4353 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 11:27:10.799  4073  4084 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:27:10.801  4353  4353 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:10.802  1920  1930 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 11:27:10.804   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:10.804  4353  4353 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:10.804  1360  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 11:27:10.806  4353  4353 D ObexServerSockets: Succeed to create listening sockets 
,08-29 11:27:10.806  1360  2050 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:27:10.806  4353  4353 D ObexServerSockets0: startAccept()
08-29 11:27:10.806  4353  4353 D ObexServerSockets0: prepareForNewConnect()
,08-29 11:27:10.809   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:10.809  1360  1360 D BluetoothInputDevice: Proxy object connected
08-29 11:27:10.809  1360  1360 D HidProfile: Bluetooth service connected
08-29 11:27:10.810  1360  2048 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:27:10.810  4353  4353 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 11:27:10.811  4353  4353 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 11:27:10.813  4353  4390 D ObexServerSockets0: Accepting socket connection...
,08-29 11:27:10.813  4353  4391 D ObexServerSockets0: Accepting socket connection...
,08-29 11:27:10.813  1360  1360 D BluetoothMap: Proxy object connected
08-29 11:27:10.813  1360  1360 D MapProfile: Bluetooth service connected
08-29 11:27:10.814  1360  1360 D BluetoothMap: getConnectedDevices()
08-29 11:27:10.814  4073  4073 D BluetoothMap: Proxy object connected
,08-29 11:27:10.814  4073  4073 D MapProfile: Bluetooth service connected
,08-29 11:27:10.814  4073  4073 D BluetoothMap: getConnectedDevices()
,08-29 11:27:10.815   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:27:10.816  1360  1372 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:27:10.816  1360  1360 D BluetoothA2dp: Proxy object connected
,08-29 11:27:10.820  1360  1379 D BluetoothPan: onBluetoothStateChange on: true
,08-29 11:27:10.824   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:27:10.824  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:27:10.824  1360  1360 D PanProfile: Bluetooth service connected
,08-29 11:27:10.826   873   873 D BluetoothA2dp: Proxy object connected
,08-29 11:27:10.827  4073  4083 D BluetoothPan: onBluetoothStateChange on: true
,08-29 11:27:10.829  4073  4073 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:27:10.830  4073  4073 D PanProfile: Bluetooth service connected
,08-29 11:27:10.831   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 11:27:10.832  4353  4353 D BluetoothMapService: onReceive
,08-29 11:27:10.832  4353  4353 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:27:10.832  4353  4353 D BluetoothMapService: STATE_ON
,08-29 11:27:10.832  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:10.838  4073  4073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:27:10.846  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:27:10.847  4073  4073 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:27:10.854  4073  4073 D BluetoothPbap: Proxy object connected
,08-29 11:27:10.854  4073  4073 D PbapServerProfile: Bluetooth service connected
,08-29 11:27:10.859  1360  1360 D BluetoothPbap: Proxy object connected
,08-29 11:27:10.860  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-29 11:27:10.861  4353  4353 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:27:10.861  4353  4353 D ObexServerSockets0: prepareForNewConnect()
08-29 11:27:10.863  4353  4397 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:10.883  4353  4401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:27:10.885  4353  4401 I BtOppRfcommListener: Accept thread started.
,08-29 11:27:10.895   873   873 D BluetoothHeadset: Proxy object connected
08-29 11:27:10.895   873   873 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.895  1360  2050 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.896  1360  1360 D HeadsetProfile: Bluetooth service connected
08-29 11:27:10.896   873   873 D BluetoothHeadset: Proxy object connected
08-29 11:27:10.896  4073  4083 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.897  1920  2196 D BluetoothHeadset: Proxy object connected
08-29 11:27:10.898  4073  4073 D HeadsetProfile: Bluetooth service connected
,08-29 11:27:10.903  1920  2199 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.905   873   890 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.905  1360  2048 D BluetoothHeadset: Proxy object connected
08-29 11:27:10.905  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-29 11:27:10.910   873   890 D BluetoothHeadset: Proxy object connected
,08-29 11:27:10.915   873   890 D BluetoothHeadset: Proxy object connected
,08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:11.235  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:11.242  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:11.246  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:11.246  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a45e754 added. We now have 8 listener(s)
08-29 11:27:11.247  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:27:11.253   873  1699 D WifiService: setWifiEnabled: false pid=4018, uid=10000
,08-29 11:27:11.253   873  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:27:11.266  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:11.267   873  1390 D WifiService: setWifiEnabled: true pid=4018, uid=10000
08-29 11:27:11.267   873  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:27:11.280   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:11.299  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:11.306  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:11.324   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-29 11:27:11.325   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 11:27:11.326   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 11:27:11.327   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 11:27:11.327   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 11:27:11.327   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 11:27:11.327   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 11:27:11.341   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 11:27:11.341   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 11:27:11.342   373   871 D CommandListener: Setting iface cfg
,08-29 11:27:11.393   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '163 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 163 Failed to set address (No such device)'
08-29 11:27:11.393   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:27:11.400   873  1303 E native  : do suspend true
,08-29 11:27:11.416   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
08-29 11:27:11.417   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 11:27:11.428   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:12.290  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:12.297  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:12.311  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 11:27:12.313  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 11:27:12.319  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7e85685 Bundle[{}]
,08-29 11:27:12.320  4018  4065 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:27:12.320  4018  4065 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 11:27:12.320  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 11:27:12.321  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 11:27:12.322  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 11:27:12.322  4018  4065 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 11:27:12.326  4018  4065 I System.out: Running OutgoingSocketThread
,08-29 11:27:12.329  4018  4407 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 463)
,08-29 11:27:12.331  4018  4407 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38051
,08-29 11:27:12.332  4018  4407 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 11:27:12.807   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 11:27:12.938   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.44 rxSuccessRate=15.06 delta 1000 -> 994
,08-29 11:27:12.943   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 11:27:12.944   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:27:12.961   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 11:27:13.037   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 11:27:13.040  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 11:27:13.330  4018  4065 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 464)
,08-29 11:27:13.330  4018  4065 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 464)
,08-29 11:27:13.340  4018  4065 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 469)
,08-29 11:27:13.342  4018  4065 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 11:27:13.343  4018  4065 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 470)
,08-29 11:27:13.347  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:27:13.347  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3746fd added. We now have 2 listener(s)
,08-29 11:27:13.349  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.349  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.349  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:27:13.349  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:13.350  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d87ff2 added. We now have 9 listener(s)
08-29 11:27:13.350  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.351  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:27:13.358  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:13.364  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:13.368  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:13.368  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:27:13.368  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:27:13.368  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c424c0 added. We now have 3 listener(s)
,08-29 11:27:13.370  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:27:13.370  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:27:13.370  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:27:13.371  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:13.371  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13655f9 added. We now have 10 listener(s)
,08-29 11:27:13.371  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:27:13.371  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:27:13.371  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:27:13.371  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:27:13.371  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:13.371  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:27:13.371  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.371  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:27:13.372  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.372  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3746fd removed from the list
08-29 11:27:13.372  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.372  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d87ff2 removed from the list
08-29 11:27:13.374  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:13.374  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:27:13.374  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.375  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.375  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.377  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.377  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:27:13.378  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.378  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d87ff2 not in the list
,08-29 11:27:13.378  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.378  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.381  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.381  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.381  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.382  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13655f9 removed from the list
08-29 11:27:13.382  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.382  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.382  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.382  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:27:13.383  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c424c0 removed from the list
,08-29 11:27:13.385  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:27:13.385  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eaa93e added. We now have 2 listener(s)
08-29 11:27:13.391  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:27:13.391  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.391  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:27:13.392  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:27:13.392  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6f239f added. We now have 9 listener(s)
08-29 11:27:13.393  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.394  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:27:13.401  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:13.407  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:27:13.412  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:13.413  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:27:13.413  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:27:13.414  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d58b5 added. We now have 3 listener(s)
,08-29 11:27:13.416  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:13.419  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:13.419  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.420  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.420  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:27:13.420  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:13.421  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4641b4a added. We now have 10 listener(s)
08-29 11:27:13.421  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.422  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:27:13.422  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:27:13.422  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:27:13.422  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:27:13.423  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:27:13.428  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 11:27:13.428  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:27:13.435  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:27:13.436  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:27:13.436  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:27:13.441  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:27:13.442  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:27:13.442  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:27:13.444  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:27:13.449  4353  4392 D BtGatt.GattService: registerClient() - UUID=25f064bd-423f-4eff-8cdb-c6f2dfff6b92,
08-29 11:27:13.451  4353  4369 D BtGatt.GattService: onClientRegistered() - UUID=25f064bd-423f-4eff-8cdb-c6f2dfff6b92, clientIf=5
,08-29 11:27:13.452  4018  4028 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:27:13.454  4353  4383 D BtGatt.GattService: start scan with filters
,08-29 11:27:13.463  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:27:13.464  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:27:13.464  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:27:13.464  4353  4372 D BtGatt.ScanManager: handling starting scan
08-29 11:27:13.465  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:27:13.469  4353  4372 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39e16c9
,08-29 11:27:13.475  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:27:13.477  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:27:13.477  4353  4369 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 11:27:13.478  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-29 11:27:13.478  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-29 11:27:13.480  4353  4372 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:27:13.481  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:27:13.487  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:27:13.496  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:27:13.496  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:27:13.497  4018  4065 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:27:13.497  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:27:13.497  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 11:27:13.497  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.497  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 11:27:13.497  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:27:13.497  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:27:13.497  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 11:27:13.498  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:27:13.498  4353  4372 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:27:13.498  4353  4372 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-29 11:27:13.500  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:27:13.501  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:27:13.502  4018  4065 D BluetoothAdapter: STATE_ON
08-29 11:27:13.504  4353  4383 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:27:13.506  4353  4393 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:27:13.506  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 11:27:13.506  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:27:13.506  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 11:27:13.506  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:27:13.507  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:27:13.508  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:27:13.509  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:27:13.509  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:27:13.509  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:27:13.509  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.511  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:27:13.511  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:27:13.511  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:27:13.514  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:27:13.514  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:27:13.514  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:27:13.514  4353  4369 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:27:13.514  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 11:27:13.515  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.515  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.515  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 11:27:13.515  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:27:13.515  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eaa93e removed from the list
08-29 11:27:13.515  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.515  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6f239f removed from the list
,08-29 11:27:13.515  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:27:13.515  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 11:27:13.516  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.516  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.517  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.517  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:27:13.517  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.518  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6f239f not in the list
,08-29 11:27:13.518  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.518  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.519  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.519  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.519  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.519  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4641b4a removed from the list
08-29 11:27:13.520  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:27:13.520  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.520  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.520  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.520  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d58b5 removed from the list
08-29 11:27:13.521  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:27:13.521  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a50a216 added. We now have 2 listener(s)
,08-29 11:27:13.521  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:27:13.521  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.522  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.523  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.523  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:27:13.523  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:13.523  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbe797 added. We now have 9 listener(s)
08-29 11:27:13.523  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.524  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:27:13.528  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:27:13.529  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:27:13.529  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.529  4353  4372 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:27:13.529  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:27:13.529  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:13.532  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:13.533   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 11:27:13.535  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:27:13.535  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:13.536  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.536  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:27:13.536  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:27:13.536  4353  4372 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 11:27:13.536  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcce96d added. We now have 3 listener(s)
08-29 11:27:13.537  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:13.538  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:13.540  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.540  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.540  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:27:13.540  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:27:13.540  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6acc9a2 added. We now have 10 listener(s)
,08-29 11:27:13.540  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.540  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:27:13.542  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:27:13.542  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:27:13.542  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:27:13.542  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:27:13.542  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:27:13.542   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 11:27:13.542  4353  4369 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:27:13.542   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 11:27:13.542  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.542   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:27:13.545  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:27:13.545  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:27:13.548  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:27:13.548  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:27:13.548  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:27:13.551  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:27:13.551  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:27:13.551  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 11:27:13.552  4018  4065 D BluetoothAdapter: STATE_ON
08-29 11:27:13.553  4353  4364 D BtGatt.GattService: registerClient() - UUID=6c692b6b-8bdc-4406-91f8-7b05f3f58ade
08-29 11:27:13.554  4353  4369 D BtGatt.GattService: onClientRegistered() - UUID=6c692b6b-8bdc-4406-91f8-7b05f3f58ade, clientIf=5
08-29 11:27:13.554  4018  4029 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:27:13.554  4353  4392 D BtGatt.GattService: start scan with filters
,08-29 11:27:13.556  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:27:13.556  4353  4372 D BtGatt.ScanManager: handling starting scan
08-29 11:27:13.556  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:27:13.556  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:27:13.556  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 11:27:13.556   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:27:13.559  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:27:13.559  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:27:13.559  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:27:13.561  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 11:27:13.561  4353  4369 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:27:13.561  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.562  4353  4372 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:27:13.562  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:27:13.562  4018  4065 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 11:27:13.563  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:27:13.563  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:27:13.563  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:27:13.563  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.563  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.563  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:27:13.563  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.563  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a50a216 removed from the list
,08-29 11:27:13.563  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.563  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbe797 removed from the list
08-29 11:27:13.564  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:27:13.564  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.564  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.564  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 11:27:13.564  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.564  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.565   373   871 D CommandListener: Setting iface cfg
08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.565  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbe797 not in the list
08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:27:13.565  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:27:13.565  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:27:13.565  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:27:13.566  4018  4065 D BluetoothAdapter: STATE_ON
08-29 11:27:13.566  4353  4392 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:27:13.567  4353  4393 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:27:13.567  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:27:13.567  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:27:13.567  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 11:27:13.567  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:27:13.567  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.567  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:27:13.567  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:27:13.567  4353  4372 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:27:13.567  4353  4372 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 11:27:13.568   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 11:27:13.571  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:27:13.571  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 11:27:13.571  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:27:13.571  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:27:13.571  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.572  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:27:13.572  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:27:13.572  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:27:13.572  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:27:13.572  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.573  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.573  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6acc9a2 removed from the list
,08-29 11:27:13.573  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.573  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.573  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 11:27:13.573  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.573  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcce96d removed from the list
08-29 11:27:13.573  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:27:13.573  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b1ddee added. We now have 2 listener(s)
08-29 11:27:13.574   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 11:27:13.575  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.575  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.575  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:27:13.575  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:27:13.575  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e328f added. We now have 9 listener(s)
08-29 11:27:13.575  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.575  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:27:13.578  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:27:13.579  4353  4369 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:27:13.579  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.579   873  4410 D DhcpClient: Receive thread started
,08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:27:13.582  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:13.583  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:27:13.583  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.584  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:27:13.584  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:27:13.585  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:13.586  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:27:13.586  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f6d925 added. We now have 3 listener(s)
08-29 11:27:13.587  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:13.587  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.587  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.587  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:27:13.587  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:27:13.587  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be1eafa added. We now have 10 listener(s)
08-29 11:27:13.587  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.587  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:27:13.587  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:27:13.588  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:27:13.588  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:27:13.588  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:27:13.588  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:27:13.588  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.588  4353  4372 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:27:13.590  4018  4065 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 11:27:13.591  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:27:13.593  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:27:13.593  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:27:13.593  4353  4372 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:27:13.595  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:27:13.596  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:27:13.596  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:27:13.598  4353  4369 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 11:27:13.598  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.599  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:27:13.599  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 11:27:13.599  4018  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:27:13.600  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:27:13.601  4353  4383 D BtGatt.GattService: registerClient() - UUID=199eec45-6163-4fe7-8dc5-909b6d965cbb
,08-29 11:27:13.601  4353  4369 D BtGatt.GattService: onClientRegistered() - UUID=199eec45-6163-4fe7-8dc5-909b6d965cbb, clientIf=5
08-29 11:27:13.602  4018  4029 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:27:13.602  4353  4364 D BtGatt.GattService: start scan with filters
,08-29 11:27:13.604  4353  4372 D BtGatt.ScanManager: handling starting scan
,08-29 11:27:13.604  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:27:13.604  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:27:13.604  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:27:13.604  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:27:13.606  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:27:13.606  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:27:13.606  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:27:13.608  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:27:13.611  4353  4369 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:27:13.611  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:27:13.611  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:27:13.611  4353  4372 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:27:13.611  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:27:13.611  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:27:13.611  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 11:27:13.611  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.612  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:27:13.612  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:27:13.612  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b1ddee removed from the list
,08-29 11:27:13.612  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.612  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e328f removed from the list
,08-29 11:27:13.612  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:27:13.612  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.612  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.612  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 11:27:13.612  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.612  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.613  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:27:13.613  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:27:13.613  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.613  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e328f not in the list
08-29 11:27:13.613  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 11:27:13.613  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:27:13.613  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:27:13.614  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:27:13.614  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:27:13.614  4018  4065 D BluetoothAdapter: STATE_ON
,08-29 11:27:13.614  4353  4392 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:27:13.615  4353  4383 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:27:13.615  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:27:13.615  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 11:27:13.615  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:27:13.615  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:27:13.616  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:27:13.616  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:27:13.616  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:27:13.616  4018  4065 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:27:13.617  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-29 11:27:13.617  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.617  4353  4372 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:27:13.617  4353  4372 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:27:13.617  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:27:13.617  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.618  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:27:13.618  4018  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:27:13.618  4018  4018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:27:13.618  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.618  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:27:13.618  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.618  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be1eafa removed from the list
08-29 11:27:13.618  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:27:13.618  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.618  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.619  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:27:13.619  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f6d925 removed from the list
,08-29 11:27:13.619  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:27:13.619  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d3bcc6 added. We now have 2 listener(s)
,08-29 11:27:13.620  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:27:13.620  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.620  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-29 11:27:13.620  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:27:13.620  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cfe487 added. We now have 9 listener(s)
,08-29 11:27:13.620  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.621  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:27:13.623  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:27:13.624  4353  4369 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:27:13.624  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-29 11:27:13.625  4018  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:27:13.626  4018  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:27:13.626  4018  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:27:13.626  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:27:13.626  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0807dd added. We now have 3 listener(s)
,08-29 11:27:13.627  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:27:13.628  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:27:13.628  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:27:13.628  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:27:13.628  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.628  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:27:13.628  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bedf52 added. We now have 10 listener(s)
08-29 11:27:13.628  4018  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:27:13.628  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:27:13.629  4018  4065 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:27:13.629  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:27:13.629  4018  4065 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:27:13.629  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.629  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.629  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:27:13.629  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.629  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d3bcc6 removed from the list
08-29 11:27:13.629  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:27:13.629  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cfe487 removed from the list
,08-29 11:27:13.629  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:27:13.630  4018  4065 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 11:27:13.630  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.630  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.630  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.630  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:27:13.630  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.630  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.631  4018  4065 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cfe487 not in the list
08-29 11:27:13.631  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:27:13.631  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:27:13.631  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:27:13.631  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:27:13.631  4018  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:27:13.631  4018  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bedf52 removed from the list
08-29 11:27:13.631  4018  4065 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:27:13.631  4018  4065 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:27:13.631  4018  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:27:13.632  4018  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:27:13.632  4018  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0807dd removed from the list
08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-29 11:27:13.632  4018  4065 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:27:13.633  4353  4369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:27:13.633  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:27:13.634  4353  4372 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:27:13.636  4018  4411 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 477, name: My test thread name)
08-29 11:27:13.636  4018  4411 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 477, thread name: My test thread name),
08-29 11:27:13.637  4018  4411 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 477, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:27:13.638  4018  4412 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 479, name: My test thread name)
08-29 11:27:13.638  4353  4369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-29 11:27:13.638  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.638  4353  4372 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 11:27:13.638  4018  4412 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 479, thread name: My test thread name)
08-29 11:27:13.639  4018  4412 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 479, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:27:13.640  4018  4065 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 11:27:13.640  4018  4065 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 11:27:13.640  4018  4065 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 11:27:13.640  4018  4065 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-29 11:27:13.640  4018  4065 D com.test.thalitest.ThaliTestRunner: Total duration: 22838 ms
08-29 11:27:13.641  4018  4065 I jxcore-log: Total number of executed tests:  80
08-29 11:27:13.641  4018  4065 I jxcore-log: 
,08-29 11:27:13.642  4018  4065 I jxcore-log: Number of passed tests:  80
08-29 11:27:13.642  4018  4065 I jxcore-log: 
08-29 11:27:13.642  4018  4065 I jxcore-log: Number of failed tests:  0
08-29 11:27:13.642  4018  4065 I jxcore-log: 
,08-29 11:27:13.642  4018  4065 I jxcore-log: Number of ignored tests:  0
08-29 11:27:13.642  4018  4065 I jxcore-log: 
08-29 11:27:13.642  4018  4065 I jxcore-log: Total duration:  22838
08-29 11:27:13.642  4018  4065 I jxcore-log: 
08-29 11:27:13.642  4353  4369 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 11:27:13.642  4353  4369 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:27:13.643  4018  4065 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 11:27:13.643  4018  4065 I jxcore-log: 
08-29 11:27:13.648  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.648  4018  4065 I jxcore-log: 
,08-29 11:27:13.649  4018  4018 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 11:27:13.651  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.651  4018  4065 I jxcore-log: 
08-29 11:27:13.652  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.652  4018  4065 I jxcore-log: 
08-29 11:27:13.653  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.653  4018  4065 I jxcore-log: 
08-29 11:27:13.653  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.653  4018  4065 I jxcore-log: 
08-29 11:27:13.654  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.654  4018  4065 I jxcore-log: 
08-29 11:27:13.656  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.656  4018  4065 I jxcore-log: 
08-29 11:27:13.657  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.657  4018  4065 I jxcore-log: 
08-29 11:27:13.657  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.657  4018  4065 I jxcore-log: 
08-29 11:27:13.658  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.658  4018  4065 I jxcore-log: 
08-29 11:27:13.658  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.658  4018  4065 I jxcore-log: 
08-29 11:27:13.659  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:27:13.659  4018  4065 I jxcore-log: 
08-29 11:27:13.659  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.659  4018  4065 I jxcore-log: 
08-29 11:27:13.660  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.660  4018  4065 I jxcore-log: 
08-29 11:27:13.660  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.660  4018  4065 I jxcore-log: 
08-29 11:27:13.661  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.661  4018  4065 I jxcore-log: 
08-29 11:27:13.661  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.661  4018  4065 I jxcore-log: 
08-29 11:27:13.662  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.662  4018  4065 I jxcore-log: 
08-29 11:27:13.662  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.662  4018  4065 I jxcore-log: 
08-29 11:27:13.663  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.663  4018  4065 I jxcore-log: 
08-29 11:27:13.663  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.663  4018  4065 I jxcore-log: 
08-29 11:27:13.663   873  1303 E native  : do suspend false
08-29 11:27:13.664  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.664  4018  4065 I jxcore-log: 
08-29 11:27:13.664  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.664  4018  4065 I jxcore-log: 
08-29 11:27:13.664  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.664  4018  4065 I jxcore-log: 
,08-29 11:27:13.665  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.665  4018  4065 I jxcore-log: 
08-29 11:27:13.665  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:27:13.665  4018  4065 I jxcore-log: 
08-29 11:27:13.666  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.666  4018  4065 I jxcore-log: 
08-29 11:27:13.666  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.666  4018  4065 I jxcore-log: 
08-29 11:27:13.667  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.667  4018  4065 I jxcore-log: 
08-29 11:27:13.667  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.667  4018  4065 I jxcore-log: 
08-29 11:27:13.667  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.667  4018  4065 I jxcore-log: 
08-29 11:27:13.668  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.668  4018  4065 I jxcore-log: 
08-29 11:27:13.668  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:27:13.668  4018  4065 I jxcore-log: 
08-29 11:27:13.672   873  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 11:27:13.742   873  4410 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-29 11:27:13.743   873  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
08-29 11:27:13.744   873  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 11:27:13.757   873  4410 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 11:27:13.758   873  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 11:27:13.761   373   871 D CommandListener: Setting iface cfg
,08-29 11:27:13.768   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 11:27:13.769   873  1303 E native  : do suspend true
08-29 11:27:13.769   873  1877 D DhcpClient: Scheduling renewal in 86399s
,08-29 11:27:13.784   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 11:27:13.785   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 11:27:13.785   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 11:27:13.789   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 11:27:13.794   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:27:13.850   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 11:27:13.850   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 11:27:13.851   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 11:27:13.852   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 11:27:13.853   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 11:27:13.859   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 11:27:13.863   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 11:27:13.863   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 11:27:13.863   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 11:27:13.863   873  1305 D ConnectivityService:    accepting network in place of null
,08-29 11:27:13.865   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 11:27:13.865   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 11:27:13.866   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:27:13.891   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:27:13.920   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:27:13.924   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 11:27:13.924   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:27:13.927   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 11:27:13.927   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:27:13.940  4018  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:27:13.941  4018  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:27:13.943  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:27:13.943  4018  4065 I jxcore-log: 
,08-29 11:27:13.947  1707  1707 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:27:13.952  1707  1707 D SystemUpdateService: onCreate
,08-29 11:27:13.956  1707  1707 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:27:13.976  1707  1707 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 11:27:13.982  1707  2437 I iu.UploadsManager: num queued entries: 0
,08-29 11:27:13.982  1707  2437 I iu.UploadsManager: num updated entries: 0
,08-29 11:27:13.982  1707  2437 I iu.SyncManager: NEXT; no task
08-29 11:27:13.984  1707  1707 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:27:13.985  1707  1707 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:27:13.988  4126  4126 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:27:13.994  4126  4126 D SprintDMHelper: simOperator: 
,08-29 11:27:13.995  4126  4126 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:27:14.001  1707  4423 I SystemUpdateService: active receiver: enabled
,08-29 11:27:14.011  4018  4018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 11:27:14.017  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:27:14.017  4018  4065 I jxcore-log: 
,08-29 11:27:14.019  1707  4425 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 11:27:14.019  1707  4425 W BaseAppContext: Using Auth Proxy for data requests.
08-29 11:27:14.024  1707  4425 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 11:27:14.039  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:27:14.041  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:27:14.047  1707  4423 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:27:14.069  1707  4423 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 11:27:14.069  1707  4423 I SystemUpdateService: now status is 0 (complete)
08-29 11:27:14.069  1707  4423 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 11:27:14.069  1707  4423 I SystemUpdateService: file has been verified
08-29 11:27:14.069  1707  4423 I SystemUpdateService: OTA package size = 12249756
08-29 11:27:14.072  4018  4018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 11:27:14.074  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:27:14.074  4018  4065 I jxcore-log: 
,08-29 11:27:14.082  1707  4423 I SystemUpdateService: showing system update notification
,08-29 11:27:14.111  1513  2406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 11:27:14.111  1513  2406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 11:27:14.111  1513  2406 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:27:14.111  1513  2406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:27:14.118  4018  4018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 11:27:14.119  4018  4065 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:27:14.119  4018  4065 I jxcore-log: 
,08-29 11:27:14.125  1707  1707 D SystemUpdateService: onDestroy
,08-29 11:27:14.134  1707  4425 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-29 11:27:14.396  4413  4413 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 11:27:14.401  4413  4413 D AndroidRuntime: CheckJNI is OFF
,08-29 11:27:14.444  4413  4413 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 11:27:14.491  4413  4413 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 11:27:14.516  4413  4413 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 11:27:14.526   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 11:27:14.526   873   886 I ActivityManager: Killing 4018:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 11:27:14.630   873   883 D GraphicsStats: Buffer count: 2
,08-29 11:27:14.630   873  1304 D WifiService: Client connection lost with reason: 4
08-29 11:27:14.630   873  1957 I WindowState: WIN DEATH: Window{2800441 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:27:14.653   873   896 W PackageSettings: Skipping PackageSetting{c08ea52 com.example.hello/10273} due to missing metadata
,08-29 11:27:14.681   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 11:27:14.681   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 11:27:14.682   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-29 11:27:14.682   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 11:27:14.682   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:14.682   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:14.682   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:27:14.682   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 11:27:14.682   873   886 I ActivityManager:   Force finishing activity ActivityRecord{ea07312 u0 com.test.thalitest/.MainActivity t2}
,08-29 11:27:14.684   873   896 I art     : Starting a blocking GC Explicit
,08-29 11:27:14.689   873  1977 W ActivityManager: Spurious death for ProcessRecord{a193024 0:com.test.thalitest/u0a0}, curProc for 4018: null
,08-29 11:27:14.726   873   896 I art     : Explicit concurrent mark sweep GC freed 27692(1765KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 806us total 41.648ms
,08-29 11:27:14.780   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 11:27:14.786   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 11:27:14.786  4413  4413 I art     : System.exit called, status: 0
08-29 11:27:14.787  4413  4413 I AndroidRuntime: VM exiting with result code 0.
,08-29 11:27:14.817   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 11:27:14.821  4353  4353 D BluetoothMapAppObserver: onReceive
,08-29 11:27:14.821  4353  4353 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 11:27:14.823  2149  2273 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 11:27:14.825  3817  3817 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-29 11:27:14.826  1860  1860 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 11:27:14.829   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 11:27:14.842  1860  4442 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 11:27:14.846   873  1700 I ActivityManager: Start proc 4444:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-29 11:27:14.848  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 11:27:14.867  1860  4442 I Decoder : createOrResetDecoder
,08-29 11:27:14.919  1513  1513 I ConfigService: onCreate
,08-29 11:27:14.931   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 11:27:14.935   873  4439 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4018 uid 10000
,08-29 11:27:14.935  4444  4444 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-29 11:27:14.936  1860  1860 I Keyboard.Facilitator: onFinishInput()
,08-29 11:27:14.939  1513  4457 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 11:27:14.939  1513  4457 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 11:27:14.939  1513  4457 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 11:27:14.941  1513  4457 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-29 11:27:14.960   873  4409 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221172, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 11:27:14.962  1860  4442 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 11:27:14.966  1936  2033 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 11:27:14.971   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 11:27:14.972   873   885 E PackageManager: Failed to write settings, restoring backup
08-29 11:27:14.972   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 11:27:14.972   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 11:27:14.972   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 11:27:14.972   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 11:27:14.972   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 11:27:14.972   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:14.972   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:14.972   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:27:14.978   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-29 11:27:14.978   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 11:27:14.978   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:14.978   873   886 E DropBoxManagerService: 	... 13 more
,08-29 11:27:14.982   873   883 I ActivityManager: Start proc 4459:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 11:27:14.982  1936  2033 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 11:27:14.982  1936  2033 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1936
08-29 11:27:14.982  1936  2033 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:14.982  1936  2033 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:27:14.985   873  1389 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:27:14.986   873  4465 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:14.986   873  4465 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:14.986   873  4465 E DropBoxManagerService: 	... 5 more
,08-29 11:27:14.989  1936  2033 I Process : Sending signal. PID: 1936 SIG: 9
,08-29 11:27:15.006  1860  4442 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 11:27:15.008  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 11:27:15.008  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 11:27:15.010  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 11:27:15.010  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 11:27:15.011  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 11:27:15.011  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 11:27:15.013  1860  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 11:27:15.013  1860  4442 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 11:27:15.013  1860  4442 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-29 11:27:15.013  1860  4442 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-29 11:27:15.014  1860  4442 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 11:27:15.014  1860  4442 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 11:27:15.028  4444  4444 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 11:27:15.038  4444  4476 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 11:27:15.041  4444  4460 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.041  4444  4460 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.042  4444  4460 E SQLiteOpenHelper: 	,at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:27:15.046   873  4439 I ActivityManager: Start proc 4477:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 11:27:15.050   873  1389 D GraphicsStats: Buffer count: 1
08-29 11:27:15.050   873  1389 I WindowState: WIN DEATH: Window{48ea43d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 11:27:15.061   873  1958 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1936) has died
08-29 11:27:15.062   873  1958 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 11:27:15.063   873  1958 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 11:27:15.084   873   884 I ActivityManager: Start proc 4490:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:27:15.102  4477  4477 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 11:27:15.138  4490  4490 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.138  4490  4490 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:27:15.138  4490  4490 D AndroidRuntime: Shutting down VM
,08-29 11:27:15.141  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 11:27:15.143  1513  1513 D AndroidRuntime: Shutting down VM
,08-29 11:27:15.144  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:27:15.144  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
08-29 11:27:15.144  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 11:27:15.144  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 11:27:15.144  1513  1513 E AndroidRuntime: 	... 8 more
,08-29 11:27:15.149   873  4507 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:15.149   873  4507 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:15.149   873  4507 E DropBoxManagerService: 	... 5 more
,08-29 11:27:15.153  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
,08-29 11:27:15.155  4490  4490 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:27:15.155  4490  4490 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4490
08-29 11:27:15.155  4490  4490 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:27:15.155  4490  4490 E AndroidRuntime: 	... 10 more
08-29 11:27:15.158   873  1957 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 11:27:15.159  4490  4490 I Process : Sending signal. PID: 4490 SIG: 9
08-29 11:27:15.160   873  4508 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:15.160   873  4508 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:15.160   873  4508 E DropBoxManagerService: 	... 5 more
,08-29 11:27:15.185   873   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4490) has died,
,08-29 11:27:15.187   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 11:27:15.190   873  1304 D WifiService: Client connection lost with reason: 4
,08-29 11:27:15.192  1707  4505 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@1fe6011
,08-29 11:27:15.195  1707  1707 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 11:27:15.196  4444  4460 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 11:27:15.200  4444  4476 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.200  4444  4476 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:27:15.201  4444  4476 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 11:27:15.201  4444  4476 E AndroidRuntime: Process: android.process.acore, PID: 4444
08-29 11:27:15.201  4444  4476 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.201  4444  4476 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:27:15.202   873   886 I ActivityManager: Start proc 4509:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 11:27:15.203   873   884 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
08-29 11:27:15.203   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-29 11:27:15.203   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-29 11:27:15.203   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-29 11:27:15.203   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
08-29 11:27:15.202  4444  4460 I Process : Sending signal. PID: 4444 SIG: 9
08-29 11:27:15.218   873   886 I ActivityManager: Start proc 4521:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
08-29 11:27:15.226   873  4529 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:15.226   873  4529 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:15.226   873  4529 E DropBoxManagerService: 	... 5 more
,08-29 11:27:15.253  4509  4509 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.253  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 11:27:15.254  4509  4509 D AndroidRuntime: Shutting down VM
,08-29 11:27:15.262  4509  4509 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:27:15.262  4509  4509 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4509
08-29 11:27:15.262  4509  4509 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:27:15.262  4509  4509 E AndroidRuntime: 	... 10 more
08-29 11:27:15.263  4521  4521 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-29 11:27:15.263   873  1958 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 11:27:15.264  4509  4509 I Process : Sending signal. PID: 4509 SIG: 9
08-29 11:27:15.265   873  4534 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:15.265   873  4534 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:15.265   873  4534 E DropBoxManagerService: 	... 5 more
08-29 11:27:15.272  4521  4521 I MultiDex: VM with version 2.1.0 has multidex support
08-29 11:27:15.272  4521  4521 I MultiDex: install
08-29 11:27:15.272  4521  4521 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 11:27:15.277  4521  4521 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 11:27:15.281  4521  4521 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.283  4521  4521 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:27:15.283  4521  4521 D AndroidRuntime: Shutting down VM
,08-29 11:27:15.285  4521  4521 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:27:15.285  4521  4521 E AndroidRuntime: Process: com.google.process.gapps, PID: 4521
08-29 11:27:15.285  4521  4521 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
08-29 11:27:15.285  4521  4521 E AndroidRuntime: 	... 10 more
,08-29 11:27:15.287   873  1933 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4509) has died
,08-29 11:27:15.289   873  1933 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 11:27:15.293   873  1390 I ActivityManager: Process android.process.acore (pid 4444) has died
,08-29 11:27:15.293   873  1390 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-29 11:27:15.295   873  4535 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:27:15.295   873  4535 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:27:15.295   873  4535 E DropBoxManagerService: 	... 5 more
,08-29 11:27:15.303   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
