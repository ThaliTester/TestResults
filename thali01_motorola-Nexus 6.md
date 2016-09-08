#### Test 829120305478790_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 17:24:07.396   872  1843 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:24:08.127  3866  3866 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 17:24:08.131  3866  3866 D AndroidRuntime: CheckJNI is OFF
09-08 17:24:08.167  3866  3866 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 17:24:08.210  3866  3866 I Radio-JNI: register_android_hardware_Radio DONE
09-08 17:24:08.229  3866  3866 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 17:24:08.233   872  2012 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 17:24:08.293   872  2012 I ActivityManager: Start proc 3876:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 17:24:08.309  3866  3866 D AndroidRuntime: Shutting down VM
09-08 17:24:08.377  3876  3876 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 17:24:08.401  3876  3876 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 17:24:08.411  3876  3876 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 2206-2212)
09-08 17:24:08.411  3876  3876 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 17:24:08.424  3876  3876 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e8297b4}
09-08 17:24:08.424  3876  3876 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 17:24:08.424  3876  3876 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 17:24:08.430  3876  3876 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 17:24:08.431  3876  3876 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 17:24:08.444  3876  3876 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 17:24:08.452  3876  3876 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 17:24:08.452  3876  3876 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 17:24:08.453  3876  3876 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 17:24:08.453  3876  3876 I Adreno  : Build Date                       : 10/20/15
09-08 17:24:08.453  3876  3876 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 17:24:08.453  3876  3876 I Adreno  : Local Branch                     : M14
09-08 17:24:08.453  3876  3876 I Adreno  : Remote Branch                    : 
09-08 17:24:08.453  3876  3876 I Adreno  : Remote Branch                    : 
09-08 17:24:08.453  3876  3876 I Adreno  : Reconstruct Branch               : 
,09-08 17:24:08.546   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66d5489:true
,09-08 17:24:08.590  3876  3876 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 17:24:08.603  3876  3876 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 17:24:08.672  3876  3913 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 17:24:08.690  3876  3900 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 17:24:08.740  3876  3913 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 17:24:08.812   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +481ms (total +542ms)
,09-08 17:24:08.815  1883  1883 I Keyboard.Facilitator: onFinishInput()
,09-08 17:24:08.870  3876  3876 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3876
,09-08 17:24:08.949  3876  3876 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 17:24:09.105  3876  3916 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1689056976
,09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 17:24:09.113  3876  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a16a5b added. We now have 1 listener(s)
,09-08 17:24:09.121  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 17:24:09.130  3876  3916 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:24:09.141  3876  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:24:09.142  3876  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 17:24:09.152  3876  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bae2e36 added. We now have 1 listener(s)
09-08 17:24:09.152  3876  3916 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:24:09.161   872  1310 D WifiService: New client listening to asynchronous messages
,09-08 17:24:09.164  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:24:09.165  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 17:24:09.165  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 17:24:09.166  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 17:24:09.166  3876  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 17:24:09.173  3876  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:09.174  3876  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 17:24:09.184  3876  3916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:09.184  3876  3916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:24:09.184  3876  3916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-08 17:24:09.184  3876  3916 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:24:09.188  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:09.189  3876  3916 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 17:24:09.191  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:09.256  3876  3876 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 17:24:10.509  3876  3922 W jxcore-log: Initializing JXcore engine
,09-08 17:24:10.509  3876  3922 W jxcore-log: JXcore engine is ready
,09-08 17:24:10.545  3922  3922 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 17:24:10.545  3922  3922 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9665]" dev="sockfs" ino=9665 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 17:24:10.545  3922  3922 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 17:24:10.545  3922  3922 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25067]" dev="sockfs" ino=25067 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 17:24:10.563  3876  3922 W jxcore-log: Starting JXcore engine
,09-08 17:24:10.645  3876  3922 W jxcore-log: Platform android
09-08 17:24:10.645  3876  3922 W jxcore-log: 
,09-08 17:24:10.645  3876  3922 W jxcore-log: Process ARCH arm
09-08 17:24:10.645  3876  3922 W jxcore-log: 
,09-08 17:24:10.841  3876  3922 I jxcore-log: JXcore Cordova bridge is ready!
09-08 17:24:10.841  3876  3922 I jxcore-log: 
,09-08 17:24:10.842  3876  3922 W jxcore-log: JXcore engine is started
,09-08 17:24:10.851  3876  3916 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 17:24:10.856  3876  3876 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 17:24:16.568  3766  3923 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 17:24:16.589  3766  3924 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 17:24:16.604  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:16.607  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:16.640  1511  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 17:24:16.641  1511  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 17:24:16.641  1511  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:24:16.641  1511  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:24:16.680  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:16.683  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:16.717  1511  2308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 17:24:16.717  1511  2308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 17:24:16.717  1511  2308 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:24:16.717  1511  2308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:24:16.734  3766  3924 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 17:24:16.735  3766  3923 E BooksSync: Soft error
09-08 17:24:16.735  3766  3923 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:24:16.735  3766  3923 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 17:24:16.736  3766  3923 E BooksSync: Sync error
09-08 17:24:16.736  3766  3923 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:24:16.736  3766  3923 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 17:24:16.736  3766  3923 I BooksSync: Finished books sync
,09-08 17:24:16.744   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 319228, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:24:21.502   872  1843 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 17:24:25.129  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 17:24:25.129  3876  3922 I jxcore-log: 
,09-08 17:24:25.132  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 17:24:25.132  3876  3922 I jxcore-log: 
,09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:25.144  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:25.147  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:24:25.150  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 17:24:25.150  3876  3922 I jxcore-log: 
,09-08 17:24:25.151  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 17:24:25.151  3876  3922 I jxcore-log: 
,09-08 17:24:25.497  3876  3922 I jxcore-log: Running unit tests
09-08 17:24:25.497  3876  3922 I jxcore-log: 
,09-08 17:24:25.498  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:24:25.498  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfb8cdb added. We now have 2 listener(s)
09-08 17:24:25.499  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:24:25.499  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 17:24:25.500  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:24:25.500  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:24:25.500  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@867e378 added. We now have 2 listener(s)
09-08 17:24:25.500  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:24:25.500  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:24:25.502  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:25.510  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:25.511  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:24:25.511  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:24:25.512  3876  3922 D executeNativeTests: Running unit tests
,09-08 17:24:25.519  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:25.527  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:25.573  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 17:24:25.573  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 added. We now have 3 listener(s)
09-08 17:24:25.574  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:24:25.575  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:24:25.575  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:24:25.575  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:24:25.575  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 added. We now have 3 listener(s)
09-08 17:24:25.575  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:24:25.575  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:24:25.577  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:25.593  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:25.596  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:24:25.596  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:24:25.598  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:25.598  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 17:24:25.600  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:24:25.600  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:24:25.600  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:24:25.602  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:25.602  3876  3922 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 17:24:25.603  3876  3922 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 17:24:25.603  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 17:24:25.603  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:25.603  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:25.603  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:25.603  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:25.604  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:24:25.604  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:25.604  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:25.604  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.604  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:24:25.604  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 17:24:25.605  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 removed from the list
,09-08 17:24:25.605  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.605  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 removed from the list
09-08 17:24:25.605  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:25.605  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.606  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.606  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:25.608  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:24:25.609  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:24:25.609  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.609  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:25.612  3876  3922 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 17:24:25.613  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:25.613  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:24:25.613  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:25.614  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:25.614  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.614  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.614  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:25.614  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.614  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:25.614  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:25.615  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.615  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.615  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.615  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.616  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:25.616  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:24:25.616  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.616  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 17:24:25.620  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 17:24:25.621  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 17:24:25.621  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:25.622  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:25.622  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:25.622  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:25.622  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.622  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.622  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:25.622  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.622  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:25.622  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:25.622  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.622  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.622  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:25.622  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:25.623  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:25.623  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:25.623  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:25.623  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:25.624  3876  3922 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 17:24:25.625  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:25.629  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:24:25.631  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:25.632  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:24:25.632  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:24:25.632  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:24:25.632  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:24:25.632  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:25.632  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 17:24:25.634  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:25.636  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:24:25.636  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 17:24:25.637  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:25.642  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 17:24:25.643  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:24:25.644  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 17:24:25.646  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 17:24:25.650  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 17:24:25.651  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 17:24:25.652  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:24:25.652  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 17:24:25.655  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:24:25.664  2689  2845 D BtGatt.GattService: registerClient() - UUID=d14d9096-cdfa-4941-a218-487ad8dd25b6
09-08 17:24:25.664  2689  2714 D BtGatt.GattService: onClientRegistered() - UUID=d14d9096-cdfa-4941-a218-487ad8dd25b6, clientIf=5
09-08 17:24:25.665  3876  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 17:24:25.666  2689  2702 D BtGatt.GattService: start scan with filters
09-08 17:24:25.670  2689  2717 D BtGatt.ScanManager: handling starting scan
09-08 17:24:25.670  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 17:24:25.671  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:24:25.671  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:24:25.671  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 17:24:25.672  2689  2717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:24:25.675  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:24:25.675  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 17:24:25.675  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:24:25.678  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 17:24:25.680  2689  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 17:24:25.680  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:25.680  2689  2717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 17:24:25.683  3876  3922 I io.jxcore.node.ConnectionHelper: start: OK
09-08 17:24:25.685  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 17:24:25.685  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:25.686  2689  2717 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:24:25.686  2689  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 17:24:25.694  2689  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 17:24:25.695  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:25.702  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:24:25.702  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:26.177  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:24:26.178  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:24:26.178  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:24:27.209  2689  2689 D BtGatt.ScanManager: awakened up at time 331011
,09-08 17:24:27.212  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:27.254  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 17:24:27.254  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:27.255  2689  2714 D BtGatt.GattService: current time is 331057013188
09-08 17:24:27.257  2689  2714 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -94, 2, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:24:27.261  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 17:24:27.262  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 17:24:27.263  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-08 17:24:27.263  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 17:24:27.263  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:24:27.263  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:24:28.757  2689  2689 D BtGatt.ScanManager: awakened up at time 332559
,09-08 17:24:28.760  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:28.790  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-08 17:24:28.790  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:28.791  2689  2714 D BtGatt.GattService: current time is 332593026876
09-08 17:24:28.792  2689  2714 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 17:24:28.792  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 17:24:28.793  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:24:28.794  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 17:24:30.294  2689  2689 D BtGatt.ScanManager: awakened up at time 334095
,09-08 17:24:30.296  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:30.307  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:24:30.308  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:30.692  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:30.693  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:30.693  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:24:30.693  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:30.694  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:24:30.694  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:24:30.694  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:24:30.695  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:24:30.695  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 17:24:30.697  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:24:30.699  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:24:30.702  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:24:30.704  2689  2700 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:24:30.706  2689  2872 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:24:30.709  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:24:30.709  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:24:30.710  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:24:30.710  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:24:30.710  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 17:24:30.714  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:30.715  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:24:30.716  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:24:30.716  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:24:30.717  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:24:30.720  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:30.721  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:24:30.721  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:30.722  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:30.722  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:30.722  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:24:30.723  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:30.723  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:30.723  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:30.723  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:30.723  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:30.727  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:24:30.727  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:30.728  2689  2717 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:24:30.741  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:24:30.742  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:30.742  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:30.753  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 17:24:30.754  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:31.222  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:24:35.727  3876  3922 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 17:24:35.734  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:35.752  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:35.761  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:24:35.762  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:24:35.763  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 17:24:35.763  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 17:24:35.763  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:24:35.764  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:35.764  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:24:35.770  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:35.779  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:24:35.780  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:35.780  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:24:35.799  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:24:35.802  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 17:24:35.803  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:24:35.818  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 17:24:35.818  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:24:35.819  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 17:24:35.822  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:24:35.831  2689  2845 D BtGatt.GattService: registerClient() - UUID=40951aba-c0ff-496a-bd30-bfad39f8c3ba
,09-08 17:24:35.832  2689  2714 D BtGatt.GattService: onClientRegistered() - UUID=40951aba-c0ff-496a-bd30-bfad39f8c3ba, clientIf=5
,09-08 17:24:35.833  3876  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 17:24:35.835  2689  2702 D BtGatt.GattService: start scan with filters
,09-08 17:24:35.845  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 17:24:35.846  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 17:24:35.846  2689  2717 D BtGatt.ScanManager: handling starting scan
,09-08 17:24:35.846  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 17:24:35.846  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:24:35.857  2689  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 17:24:35.858  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:35.859  2689  2717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:24:35.860  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:24:35.862  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:24:35.862  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:24:35.870  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:24:35.875  3876  3922 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 17:24:35.880  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:24:35.881  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:35.881  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:35.881  3876  3922 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 17:24:35.881  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:35.881  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:24:35.882  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:35.882  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:24:35.882  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:24:35.885  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:24:35.882  2689  2717 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 17:24:35.888  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:24:35.889  2689  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 17:24:35.889  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:24:35.889  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:24:35.889  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:24:35.891  3876  3922 D BluetoothAdapter: STATE_ON
09-08 17:24:35.893  2689  2700 D BtGatt.GattService: stopScan() - queue size =1
09-08 17:24:35.894  2689  2872 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 17:24:35.894  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:24:35.895  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 17:24:35.895  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:24:35.895  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:24:35.895  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 17:24:35.897  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:35.898  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 17:24:35.899  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:24:35.899  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:24:35.903  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:24:35.908  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:35.908  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:35.909  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:35.909  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:35.909  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:35.909  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:24:35.909  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:35.909  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:35.910  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:35.910  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:35.910  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:35.912  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:35.912  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:35.916  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:35.916  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:24:35.917  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:35.917  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:35.919  3876  3922 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 17:24:35.924  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:24:35.925  2689  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 17:24:35.925  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:35.934  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:35.937  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:24:35.938  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:35.939  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:24:35.939  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:24:35.939  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:24:35.939  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:24:35.939  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:24:35.939  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:35.940  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:24:35.945  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:35.949  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:24:35.949  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:24:35.951  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 17:24:35.951  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:35.951  2689  2717 D BtGatt.ScanManager: stopping BLe Batch
09-08 17:24:35.952  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:35.958  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:24:35.959  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:24:35.959  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:24:35.964  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:24:35.964  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:35.964  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:35.966  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 17:24:35.966  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:24:35.966  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 17:24:35.968  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:24:35.975  2689  2702 D BtGatt.GattService: registerClient() - UUID=0483c526-8fe1-47b7-b41d-2a6ec1d270df
,09-08 17:24:35.976  2689  2714 D BtGatt.GattService: onClientRegistered() - UUID=0483c526-8fe1-47b7-b41d-2a6ec1d270df, clientIf=5
09-08 17:24:35.977  3876  3886 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 17:24:35.979  2689  2845 D BtGatt.GattService: start scan with filters
,09-08 17:24:35.982  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 17:24:35.982  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:35.982  2689  2714 D BtGatt.GattService: current time is 339784216764
09-08 17:24:35.982  2689  2714 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, -128, -95, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0]
09-08 17:24:35.982  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
,09-08 17:24:35.987  2689  2717 D BtGatt.ScanManager: handling starting scan
,09-08 17:24:35.987  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 17:24:35.988  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:24:35.988  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 17:24:35.988  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:24:35.993  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:24:35.993  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:24:35.994  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:24:35.996  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:24:36.001  2689  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 17:24:36.001  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:36.002  2689  2717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:24:36.005  3876  3922 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 17:24:36.013  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:24:36.013  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:36.014  2689  2717 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:24:36.014  2689  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:24:36.046  2689  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 17:24:36.046  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:36.066  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 17:24:36.066  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:36.495  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:24:36.496  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:24:36.496  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:24:37.569  2689  2689 D BtGatt.ScanManager: awakened up at time 341371
,09-08 17:24:37.575  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:37.626  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-08 17:24:37.627  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:37.627  2689  2714 D BtGatt.GattService: current time is 341429288792
09-08 17:24:37.628  2689  2714 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 17:24:37.629  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 17:24:37.630  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:24:37.631  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 17:24:37.632  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 17:24:37.633  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:24:37.634  2689  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 17:24:38.286  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:38.297  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:38.302  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:24:38.352  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 17:24:38.352  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 17:24:38.353  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:24:38.353  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:24:38.387  1511  1523 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 17:24:38.387  1511  1523 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 17:24:38.398  3528  3557 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 17:24:38.398  3528  3557 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 17:24:38.398  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 17:24:38.398  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 17:24:38.398  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 17:24:38.398  3528  3557 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 17:24:38.398  3528  3557 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 17:24:39.130  2689  2689 D BtGatt.ScanManager: awakened up at time 342931
,09-08 17:24:39.133  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:39.142  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 17:24:39.142  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:40.643  2689  2689 D BtGatt.ScanManager: awakened up at time 344445
,09-08 17:24:40.646  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:40.657  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:24:40.658  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:41.005  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:41.006  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:41.006  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 17:24:41.006  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:41.007  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:24:41.007  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:24:41.007  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 17:24:41.008  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:24:41.008  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:24:41.009  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 17:24:41.009  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 17:24:41.012  3876  3922 D BluetoothAdapter: STATE_ON
09-08 17:24:41.013  2689  2872 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:24:41.016  2689  2845 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:24:41.017  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:24:41.017  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:24:41.017  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:24:41.018  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:24:41.018  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 17:24:41.021  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:41.022  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 17:24:41.022  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:24:41.023  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:24:41.024  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:24:41.027  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:41.027  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:24:41.028  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:24:41.032  2689  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:24:41.032  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:41.033  2689  2717 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:24:41.045  2689  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:24:41.045  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:24:41.045  2689  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:24:41.057  2689  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 17:24:41.057  2689  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:24:41.529  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:24:41.530  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:41.530  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:24:46.029  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:46.029  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.029  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.030  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:24:46.030  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.030  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:24:46.031  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.031  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:46.031  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.032  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop,
,09-08 17:24:46.032  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.034  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:46.034  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.039  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.039  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.039  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.040  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.042  3876  3922 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 17:24:46.044  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.044  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.046  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.046  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.047  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.047  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.048  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.048  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.048  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.049  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.049  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.049  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.049  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.050  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:46.052  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:24:46.053  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.053  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.053  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.056  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 17:24:46.056  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.057  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.057  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.058  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:24:46.058  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.058  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.058  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.059  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.059  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.059  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.059  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.060  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.060  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.060  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:46.062  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.062  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.063  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.063  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.065  3876  3922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 17:24:46.065  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:46.066  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.066  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.067  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.067  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:46.067  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.067  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.068  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.068  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.068  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.068  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.069  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.069  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.069  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:46.071  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.071  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:24:46.071  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.071  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.072  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 17:24:46.072  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.072  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:24:46.072  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.072  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.072  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.072  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.072  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
,09-08 17:24:46.073  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.073  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.073  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.073  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:46.073  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.073  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.073  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.074  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.074  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:24:46.074  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.074  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.075  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 17:24:46.075  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:24:46.075  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 17:24:46.075  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 17:24:46.075  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:46.076  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 17:24:46.076  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 17:24:46.076  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:24:46.076  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 17:24:46.076  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:46.076  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.076  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.076  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:24:46.077  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.077  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.077  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.077  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.077  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.077  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.077  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.077  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.077  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.077  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.078  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.078  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.079  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.079  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.080  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:24:46.080  3876  3922 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 17:24:46.080  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 17:24:46.084  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:24:46.084  3876  3922 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 17:24:46.084  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:,810:810:810]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 17:24:46.085  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 17:24:46.086  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-08 17:24:46.088  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 17:24:46.088  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 17:24:46.088  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 17:24:46.088  3876  3922 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 17:24:46.089  3876  3922 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 17:24:46.089  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:24:46.089  3876  3922 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 17:24:46.089  3876  3922 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 17:24:46.089  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:24:46.089  3876  3922 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 17:24:46.089  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 17:24:46.096  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-08 17:24:46.097  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 17:24:46.097  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-08 17:24:46.098  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 17:24:46.098  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-08 17:24:46.098  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 17:24:46.099  3876  3922 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 17:24:46.099  3876  3922 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 17:24:46.100  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.100  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.100  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.100  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.100  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:46.100  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.101  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 17:24:46.104  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.104  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:46.104  3876  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-08 17:24:46.104  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.105  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.105  3876  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-08 17:24:46.105  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.105  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.105  3876  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,09-08 17:24:46.105  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.106  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.109  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.109  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.109  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.109  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list,
09-08 17:24:46.110  3876  3922 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 17:24:46.110  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.111  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.111  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:24:46.111  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.111  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.111  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.111  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.111  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:46.111  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.111  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.112  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.112  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.112  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.112  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:46.113  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.114  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.114  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.114  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.114  3876  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-08 17:24:46.115  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:46.115  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.115  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.115  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.115  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.115  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.115  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
,09-08 17:24:46.115  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.115  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.115  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.115  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.116  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.116  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.116  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:46.117  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.117  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.117  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.117  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.118  3876  3922 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 17:24:46.118  3876  3922 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 17:24:46.118  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 17:24:46.118  3876  3922 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-08 17:24:46.118  3876  3922 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 17:24:46.119  3876  3922 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 17:24:46.119  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 17:24:46.119  3876  3922 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 17:24:46.119  3876  3922 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 17:24:46.119  3876  3922 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 17:24:46.119  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 17:24:46.119  3876  3922 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 17:24:46.119  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:46.119  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:46.119  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:46.120  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.120  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.120  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.120  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.120  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:46.120  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:46.120  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.120  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.120  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.120  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.120  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.122  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:46.122  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:46.122  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.122  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.123  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:46.123  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.123  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:46.123  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:46.123  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:46.123  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:46.124  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:46.124  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:46.124  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:51.125  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:51.125  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.126  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:24:51.126  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.126  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.127  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:51.127  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:51.127  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:51.128  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:51.128  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.129  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:51.129  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.129  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
,09-08 17:24:51.129  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.130  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.130  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:51.130  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.130  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.131  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.131  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.135  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:24:51.135  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:51.135  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.135  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:51.140  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 17:24:51.142  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:24:51.143  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 17:24:51.144  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 17:24:51.145  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 17:24:51.145  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 17:24:51.145  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 17:24:51.145  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:24:51.146  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.146  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 17:24:51.146  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 17:24:51.146  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 17:24:51.146  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.146  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 17:24:51.146  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 17:24:51.146  3876  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 17:24:51.146  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:51.147  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:51.147  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:24:51.147  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 17:24:51.147  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:24:51.147  3876  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 17:24:51.147  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:51.147  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.148  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:24:51.149  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:51.149  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:24:51.149  3876  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 17:24:51.149  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:24:51.149  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.149  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:51.149  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:24:51.149  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:24:51.150  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.150  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.150  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.150  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:51.150  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:51.150  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.150  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:51.150  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.150  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.150  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.150  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.152  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:51.152  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:51.153  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.153  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.156  3876  3922 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 17:24:51.156  3876  3922 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 17:24:51.156  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 17:24:51.160  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:51.161  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 17:24:51.161  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:51.161  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:51.161  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:51.161  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.161  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.161  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.162  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:51.162  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.162  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.162  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:51.162  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.162  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.162  ,3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.162  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.165  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:51.165  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:51.165  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.165  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:51.173  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:24:51.173  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:24:51.173  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:51.174  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.174  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.174  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.174  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
,09-08 17:24:51.174  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.175  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.175  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:51.175  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.175  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.175  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.175  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:51.177  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:24:51.177  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:51.177  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:51.177  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
09-08 17:24:51.178  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:24:51.178  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:24:51.178  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 17:24:51.179  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:24:51.179  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.179  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.179  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ef1566 not in the list
09-08 17:24:51.179  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.179  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:51.179  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:51.179  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.179  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.179  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:24:51.179  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:24:51.181  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:24:51.181  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:24:51.181  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:24:51.181  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3560a7 not in the list
,09-08 17:24:51.182  3876  3922 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 17:24:51.183  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 17:24:51.183  3876  3922 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 17:24:51.183  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 17:24:51.183  3876  3922 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 17:24:51.183  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 17:24:51.185  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 17:24:51.186  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 17:24:51.186  3876  3922 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 17:24:51.186  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 17:24:51.187  3876  3922 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-08 17:24:51.187  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 17:24:51.187  3876  3922 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 17:24:51.188  3876  3922 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 17:24:51.188  3876  3922 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 17:24:51.188  3876  3922 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
09-08 17:24:51.189  3876  3922 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 17:24:51.189  3876  3922 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 17:24:51.189  3876  3922 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 17:24:51.189  3876  3922 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 17:24:51.190  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:24:51.190  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6f9531 added. We now have 3 listener(s)
09-08 17:24:51.191  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:24:51.193  3876  3922 D BluetoothAdapter: enable(): BT is already enabled..!,
09-08 17:24:51.193   872   882 D WifiService: setWifiEnabled: true pid=3876, uid=10000
09-08 17:24:51.193   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:24:51.651  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:24:56.205  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:24:56.206  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdda416 added. We now have 4 listener(s)
,09-08 17:24:56.206  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:24:56.223  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:56.223  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdda416 removed from the list,
09-08 17:24:56.223  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:24:56.224  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:56.224  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:56.227  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:24:56.227  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@161c197 added. We now have 4 listener(s)
,09-08 17:24:56.228  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:24:56.232  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:24:56.233  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@161c197 removed from the list
09-08 17:24:56.233  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:24:56.234  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:24:56.234  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:24:56.237  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:24:56.237  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1659f84 added. We now have 4 listener(s)
09-08 17:24:56.238  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:24:56.245   872   883 D WifiService: setWifiEnabled: false pid=3876, uid=10000
09-08 17:24:56.245   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:24:56.257  2689  2710 D BluetoothAdapterState: Current state: ON, message: 23
09-08 17:24:56.257  2689  2710 D BluetoothAdapterProperties: Setting state to 13
,09-08 17:24:56.257  2689  2710 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 17:24:56.258  2689  2710 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 17:24:56.259  2689  2710 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:24:56.259  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:24:56.262  2689  2714 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:24:56.262  2689  2710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 17:24:56.269  2689  2689 D HeadsetService: Received stop request...Stopping profile...
,09-08 17:24:56.277  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:56.278  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:24:56.279  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.279  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.279  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:24:56.282  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:56.284  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:56.287  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:56.287  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:24:56.288  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.288  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.289  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 17:24:56.289   872   885 I ActivityManager: Start proc 3936:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 17:24:56.291   872  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 17:24:56.291   872  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 17:24:56.291   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 17:24:56.291   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:24:56.292   872   872 D BluetoothHeadset: Proxy object disconnected
,09-08 17:24:56.292   872   872 D BluetoothHeadset: Proxy object disconnected
,09-08 17:24:56.293  1351  1931 D BluetoothHeadset: Proxy object disconnected
09-08 17:24:56.293  1997  2010 D BluetoothHeadset: Proxy object disconnected
09-08 17:24:56.294   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 17:24:56.294  2689  2689 D A2dpService: Received stop request...Stopping profile...
09-08 17:24:56.294  2689  2851 D A2dpStateMachine: Exit Disconnected: -1
09-08 17:24:56.295  1351  1351 D HeadsetProfile: Bluetooth service disconnected
,09-08 17:24:56.296  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:24:56.296  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:24:56.297  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.297  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:24:56.297   872   872 D BluetoothA2dp: Proxy object disconnected
09-08 17:24:56.298  1351  1351 D BluetoothA2dp: Proxy object disconnected
09-08 17:24:56.298  2689  2689 D BluetoothMapService: onReceive
09-08 17:24:56.298  2689  2689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 17:24:56.298  2689  2689 D BluetoothMapService: STATE_TURNING_OFF
09-08 17:24:56.299  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.299  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.299  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.299  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:24:56.300  2689  2689 D HidService: Received stop request...Stopping profile...
09-08 17:24:56.300  2689  2689 D HidService: Stopping Bluetooth HidService
09-08 17:24:56.301  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:56.301   872  1309 E native  : do suspend true
09-08 17:24:56.301  1351  1351 D BluetoothInputDevice: Proxy object disconnected
09-08 17:24:56.301  1351  1351 D HidProfile: Bluetooth service disconnected
09-08 17:24:56.303  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 17:24:56.303  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.303  2689  2689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 17:24:56.304  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.304  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.304  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.304  2689  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 17:24:56.304  2689  2689 D HealthService: Received stop request...Stopping profile...
09-08 17:24:56.304  2689  2714 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 17:24:56.305  2689  2689 D PanService: Received stop request...Stopping profile...
09-08 17:24:56.306  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.307  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.307  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.307  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:24:56.308  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 17:24:56.308  1351  1351 D PanProfile: Bluetooth service disconnected
09-08 17:24:56.308  2689  2689 D BluetoothMapService: Received stop request...Stopping profile...
09-08 17:24:56.308  2689  2689 D BluetoothMapService: stop()
09-08 17:24:56.309  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.310  2689  2689 D BluetoothMapAppObserver: deinitObservers()
09-08 17:24:56.310  2689  2689 D BluetoothMapAppObserver: removeReceiver()
09-08 17:24:56.311  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.312  1351  1351 D BluetoothMap: Proxy object disconnected
09-08 17:24:56.312  1351  1351 D MapProfile: Bluetooth service disconnected
09-08 17:24:56.313   872  1846 D DhcpClient: Clearing IP address
09-08 17:24:56.313  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.313  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.313  2689  2812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:24:56.313   373   870 D CommandListener: Clearing all IP addresses on wlan0
09-08 17:24:56.313  2689  2812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 17:24:56.313  2689  2812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:24:56.314  2689  2812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 17:24:56.314  2689  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 17:24:56.314  2689  2689 I BtOppRfcommListener: stopping Accept Thread
,09-08 17:24:56.314  2689  3448 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 17:24:56.316  2689  3448 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 17:24:56.316   373   870 D CommandListener: Setting iface cfg
09-08 17:24:56.317  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.317  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.317  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.317  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:24:56.318  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 17:24:56.318  2689  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:24:56.318  2689  2689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 17:24:56.318  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.319  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.319  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.319  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:24:56.319  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 17:24:56.319  2689  2714 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 17:24:56.319  2689  2689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 17:24:56.320  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.320  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.320  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:24:56.320  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:24:56.320  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 17:24:56.321  2689  2689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 17:24:56.321   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 17:24:56.321   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 17:24:56.323   448   448 E Parcel  : Reading a NULL string not supported here.
09-08 17:24:56.323   872  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 17:24:56.324   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:24:56.324   872  1309 E native  : do suspend true
09-08 17:24:56.327  2689  2689 D BluetoothMapService: MAP Service closeService in
09-08 17:24:56.327  2689  2689 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 17:24:56.327  2689  2689 D ObexServerSockets0: shutdown(block = true)
09-08 17:24:56.327  2689  2874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 17:24:56.328  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:24:56.329  2689  2875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 17:24:56.329  2689  2836 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 17:24:56.329  2689  2689 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:24:56.329  2689  2689 V BluetoothAdapterState: isTurningOff()=true
09-08 17:24:56.329   872  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 17:24:56.329  2689  2689 V BluetoothAdapterState: isTurningOn()=false
09-08 17:24:56.329  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.329  2689  2689 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:24:56.330  2689  2710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 17:24:56.330  2689  2710 D BluetoothAdapterProperties: Setting state to 15
09-08 17:24:56.330  2689  2710 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 17:24:56.330  2689  2689 D BluetoothMapService: cleanup()
09-08 17:24:56.330  2689  2689 D BluetoothMapService: MAP Service closeService in
09-08 17:24:56.330  2689  2710 I BluetoothAdapterState: Entering BleOnState
09-08 17:24:56.331  1351  1370 D BluetoothPan: onBluetoothStateChange on: false
09-08 17:24:56.331  1351  1374 D BluetoothMap: onBluetoothStateChange: up=false
09-08 17:24:56.332  1351  1931 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 17:24:56.333  1351  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:24:56.333  1351  1374 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 17:24:56.336  1997  2010 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:24:56.336  1351  1931 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:24:56.336   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:24:56.336   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:24:56.336   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:24:56.336   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:24:56.336  2689  2710 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 17:24:56.337  2689  2710 D BluetoothAdapterProperties: Setting state to 16
09-08 17:24:56.337  2689  2710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 17:24:56.337  2689  2710 D BluetoothAdapterProperties: onBleDisable
09-08 17:24:56.337  2689  2710 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:24:56.337  2689  2711 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 17:24:56.338  2689  2714 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:24:56.339  2689  2812 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 17:24:56.340  2689  2812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:24:56.342  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.342  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.342  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.342  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:24:56.345  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.346  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.346  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:24:56.347  1511  2426 V NativeCrypto: Read error: ssl=0x9b03d800: I/O error during system call, Connection timed out
09-08 17:24:56.347  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.347  3876  3876 V io.jxcore.no,de.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.347  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.348  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.348  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:24:56.349  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.350  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.351  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.359  1511  2426 V NativeCrypto: SSL shutdown failed: ssl=0x9b03d800: I/O error during system call, Broken pipe
09-08 17:24:56.363   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:24:56.375   872  1851 D DhcpClient: Receive thread stopped
,09-08 17:24:56.379  3936  3936 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 17:24:56.380   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:24:56.380   373   870 D CommandListener: Clearing all IP addresses on wlan0
09-08 17:24:56.381   872  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 17:24:56.381   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 17:24:56.382   872   889 D Tethering: MasterInitialState.processMessage what=3
09-08 17:24:56.384  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.385  3395  3395 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a8432f8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 17:24:56.386   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 17:24:56.389  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:24:56.390  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:24:56.391  2091  2091 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-08 17:24:56.401   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:24:56.404  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.404  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.405  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.405  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:24:56.405   872  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 17:24:56.406  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.406  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.407  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.407  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:24:56.408  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:24:56.408  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:24:56.409  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:24:56.409  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:24:56.409  1916  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 17:24:56.412  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:24:56.418  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:24:56.419   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4eea44:true
,09-08 17:24:56.430   872  2012 I ActivityManager: Start proc 3955:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 17:24:56.438  3936  3936 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 17:24:56.440  3936  3936 D BluetoothMap: Create BluetoothMap proxy object
,09-08 17:24:56.441   373   870 E Netd    : netlink response contains error (No such file or directory)
,09-08 17:24:56.449  3936  3936 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 17:24:56.459  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:24:56.463  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 17:24:56.470   872  2016 I ActivityManager: Killing 3395:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 17:24:56.543  2689  2714 I bt_hci  : shut_down
,09-08 17:24:56.544  2689  2718 D bt_hwcfg: hw_epilog_process
,09-08 17:24:56.546  2689  2718 I bt_vendor: low_power_mode_cb
,09-08 17:24:56.565  2689  2718 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 17:24:56.565  2689  2718 I bt_vendor: epilog_cb
,09-08 17:24:56.566  2689  2718 I bt_hci  : epilog_finished_callback
,09-08 17:24:56.574  2689  2714 I bt_hci_h4: hal_close
,09-08 17:24:56.575  2689  2714 I bt_userial_vendor: device fd = 51 close
,09-08 17:24:56.632  3955  3955 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.632  3955  3955 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.632  3955  3955 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.632  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.633  3955  3955 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.633  3955  3955 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.633  3955  3955 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.633  3955  3955 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.633  3955  3955 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:24:56.633  3955  3955 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:24:56.639  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 17:24:56.648  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:24:56.668  3936  3936 D DockEventReceiver: finishStartingService: stopping service
09-08 17:24:56.686   872  2016 I ActivityManager: Killing 3580:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-08 17:24:56.764  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:24:56.768  2689  2711 D bt_stack_manager: event_shut_down_stack finished.
,09-08 17:24:56.769  2689  2710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-08 17:24:56.769  1727  1727 D SystemUpdateService: onCreate
,09-08 17:24:56.782  2689  2689 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:24:56.783  2689  2689 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 17:24:56.783  2689  2689 D BtGatt.GattService: stop()
09-08 17:24:56.783  2689  2689 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 17:24:56.788  2689  2710 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 17:24:56.791  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-08 17:24:56.791  2689  2689 V BluetoothAdapterState: isTurningOff()=false
09-08 17:24:56.792  2689  2689 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:24:56.792  2689  2689 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:24:56.792  2689  2689 V BluetoothAdapterState: isBleTurningOff()=true
09-08 17:24:56.793  2689  2710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 17:24:56.793  2689  2710 D BluetoothAdapterProperties: Setting state to 10
09-08 17:24:56.793  2689  2710 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 17:24:56.798  2689  2710 I BluetoothAdapterState: Entering OffState
09-08 17:24:56.799   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 17:24:56.818  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 17:24:56.819  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 17:24:56.820  2689  2689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 17:24:56.820  2689  2711 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 17:24:56.823  2689  2689 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 17:24:56.824  2689  2711 D bt_stack_manager: event_clean_up_stack finished.
,09-08 17:24:56.827  1727  2398 I iu.UploadsManager: num queued entries: 0
,09-08 17:24:56.827  1727  2398 I iu.UploadsManager: num updated entries: 0
,09-08 17:24:56.831  2689  2689 I art     : System.exit called, status: 0
,09-08 17:24:56.831  2689  2689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 17:24:56.842  1727  3988 I SystemUpdateService: active receiver: enabled
,09-08 17:24:56.849  1727  2398 I iu.SyncManager: NEXT; no task
,09-08 17:24:56.868  1727  3988 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:24:56.870  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:24:56.876  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:24:56.879  1727  3988 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 17:24:56.879  1727  3988 I SystemUpdateService: now status is 0 (complete)
09-08 17:24:56.879  1727  3988 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:24:56.879  1727  3988 I SystemUpdateService: file has been verified
09-08 17:24:56.879  1727  3988 I SystemUpdateService: OTA package size = 12249756
,09-08 17:24:56.896   872  1915 I ActivityManager: Start proc 3992:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 17:24:56.904   872   882 I ActivityManager: Process com.android.bluetooth (pid 2689) has died
,09-08 17:24:56.909  1727  3988 I SystemUpdateService: showing system update notification
,09-08 17:24:56.940  3992  3992 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 17:24:56.945  3992  3992 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:24:56.958  3992  3992 D SprintDMHelper: simOperator: 
,09-08 17:24:56.959  3992  3992 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:24:56.978   872  1394 I ActivityManager: Start proc 4006:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-08 17:24:56.980  1727  1727 D SystemUpdateService: onDestroy
09-08 17:24:56.982   872  1390 I ActivityManager: Killing 3461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 17:24:57.012  3955  3974 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 17:24:57.025   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66f4e5b:true
,09-08 17:24:57.245   872   882 I ActivityManager: Start proc 4022:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 17:24:57.324  4022  4022 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 17:24:57.378  4022  4022 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 17:24:57.378  4022  4022 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 17:24:57.378  4022  4022 I GAv4    :   adb logcat -s GAv4
,09-08 17:24:57.397  4022  4022 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:24:57.403  4022  4022 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:24:57.425  4022  4039 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 17:24:57.542  4022  4022 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 17:24:57.586  4022  4022 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 17:24:57.593  4022  4022 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1392-1394)
09-08 17:24:57.593  4022  4022 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 17:24:57.600  4022  4022 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e64a28}
09-08 17:24:57.601  4022  4022 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 17:24:57.601  4022  4022 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 17:24:57.607  4022  4022 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 17:24:57.609  4022  4022 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 17:24:57.630  4022  4022 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 17:24:57.641  4022  4022 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 17:24:57.641  4022  4022 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 17:24:57.642  4022  4022 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 17:24:57.642  4022  4022 I Adreno  : Build Date                       : 10/20/15
09-08 17:24:57.642  4022  4022 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 17:24:57.642  4022  4022 I Adreno  : Local Branch                     : M14
09-08 17:24:57.642  4022  4022 I Adreno  : Remote Branch                    : 
09-08 17:24:57.642  4022  4022 I Adreno  : Remote Branch                    : 
09-08 17:24:57.642  4022  4022 I Adreno  : Reconstruct Branch               : 
,09-08 17:24:57.704  4022  4022 I NSApplication: Starting up...
,09-08 17:24:57.706  4022  4068 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 17:24:57.752   872  1390 I ActivityManager: Start proc 4073:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 17:24:57.753   872  1390 I ActivityManager: Killing 3511:android.process.acore/u0a5 (adj 15): empty #17
,09-08 17:24:57.847  4073  4073 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 17:24:58.017   872  2012 I ActivityManager: Killing 3667:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 17:24:58.111   872  1915 I ActivityManager: Start proc 4087:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 17:24:58.204  4087  4087 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 17:24:58.260  4087  4087 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 17:24:58.285   872  2016 I ActivityManager: Killing 3682:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 17:25:01.284   872  1393 D WifiService: setWifiEnabled: true pid=3876, uid=10000
,09-08 17:25:01.285   872  1393 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:25:01.299   872  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-08 17:25:01.304  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:01.304  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:01.304  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:01.304  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:01.306  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:01.306  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:01.306  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:25:01.306  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:01.308  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-08 17:25:01.308  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:01.308  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:01.308  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:01.317   872  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-08 17:25:01.318   872  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 17:25:01.319   872  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 17:25:01.320   872  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 17:25:01.320   872  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 17:25:01.321   872  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 17:25:01.321   872  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,09-08 17:25:01.337   373   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 17:25:01.338   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:25:01.338   373   870 D CommandListener: Setting iface cfg
09-08 17:25:01.339   872  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 17:25:01.339   872  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 17:25:01.352   872  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 17:25:01.353   872  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 17:25:01.353   872  1309 E native  : do suspend true
,09-08 17:25:01.384   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:25:02.318   872   883 I ActivityManager: Killing 2131:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 17:25:02.665   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:25:02.724   872  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.00 rxSuccessRate=13.94 delta 1000 -> 994
,09-08 17:25:02.728   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 17:25:02.728   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:25:02.745   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 17:25:02.818   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 17:25:02.820  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 17:25:03.345  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 17:25:03.392  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 17:25:03.392  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 17:25:03.395   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:25:03.402   872  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:25:03.402   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 17:25:03.403   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 17:25:03.416   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:25:03.424   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:03.424   872  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 17:25:03.430   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 17:25:03.481   872  4125 D DhcpClient: Receive thread started
,09-08 17:25:03.571   872  1309 E native  : do suspend false
,09-08 17:25:03.592   872  1846 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 17:25:03.606   872  4125 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172454, domain null
,09-08 17:25:03.607   872  1846 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172454 seconds
,09-08 17:25:03.611   872  1846 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 17:25:03.624   872  4125 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 17:25:03.625   872  1846 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 17:25:03.630   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:03.641   872  1846 D DhcpClient: Scheduling renewal in 86399s
,09-08 17:25:03.641   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 17:25:03.647   872  1309 E native  : do suspend true
,09-08 17:25:03.670   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 17:25:03.673   872  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 17:25:03.674   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 17:25:03.675   872  1311 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 17:25:03.683   872  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 17:25:03.729   872  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 17:25:03.729   872  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 17:25:03.731   872  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 17:25:03.732   872  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 17:25:03.734   872  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 17:25:03.745   872  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 17:25:03.751   872  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 17:25:03.751   872  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-08 17:25:03.751   872  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 17:25:03.751   872  1311 D ConnectivityService:    accepting network in place of null
09-08 17:25:03.751   872  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 17:25:03.752   872  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 17:25:03.754   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 17:25:03.770   872  4124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:25:03.786   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:03.839   872  4123 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 17:25:03.853   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:03.858   872  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 17:25:03.865   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 17:25:03.867   872  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 17:25:03.868   872   889 D Tethering: MasterInitialState.processMessage what=3
09-08 17:25:03.884  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:03.886  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:25:03.886  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.886  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:03.888  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:03.888  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:25:03.888  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.888  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:03.890  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:03.890  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 17:25:03.890  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:03.890  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:03.904  2091  2091 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-08 17:25:03.908   872  4123 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 15:25:03 GMT], X-Android-Received-Millis=[1473348303907], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473348303882]}
,09-08 17:25:03.909   872  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 17:25:03.909   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 17:25:03.909   872  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 17:25:03.910   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 17:25:03.913  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:25:03.919  1727  1727 D SystemUpdateService: onCreate
,09-08 17:25:03.922  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:25:03.940  1727  4136 I SystemUpdateService: active receiver: enabled
,09-08 17:25:03.946  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 17:25:03.952  1727  2398 I iu.UploadsManager: num queued entries: 0
,09-08 17:25:03.953  1727  2398 I iu.UploadsManager: num updated entries: 0
09-08 17:25:03.953  1727  2398 I iu.SyncManager: NEXT; no task
,09-08 17:25:03.954  1727  4136 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:25:03.956  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:25:03.958  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:25:03.963  3992  3992 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:25:03.963  1727  4136 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 17:25:03.963  1727  4136 I SystemUpdateService: now status is 0 (complete)
09-08 17:25:03.963  1727  4136 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:25:03.963  1727  4136 I SystemUpdateService: file has been verified
09-08 17:25:03.963  1727  4136 I SystemUpdateService: OTA package size = 12249756
,09-08 17:25:03.970  3992  3992 D SprintDMHelper: simOperator: 
,09-08 17:25:03.970  3992  3992 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:25:03.977  1727  4139 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 17:25:03.977  1727  4139 W BaseAppContext: Using Auth Proxy for data requests.
09-08 17:25:03.978  1727  4139 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 17:25:03.993  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:25:03.999  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:25:04.021  1727  4136 I SystemUpdateService: showing system update notification
,09-08 17:25:04.065  1727  1727 D SystemUpdateService: onDestroy
,09-08 17:25:04.072  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 17:25:04.072  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 17:25:04.072  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:25:04.072  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:25:04.089  1727  4139 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-08 17:25:04.149  2294  4143 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 17:25:04.860   872  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 17:25:06.291   872  2009 D WifiService: setWifiEnabled: false pid=3876, uid=10000
,09-08 17:25:06.291   872  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:25:06.333  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 17:25:06.343   872  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 17:25:06.344   872  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 17:25:06.345   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 17:25:06.346   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:25:06.366   872  1309 E native  : do suspend true
,09-08 17:25:06.378   872  1846 D DhcpClient: Clearing IP address
,09-08 17:25:06.378   373   870 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:25:06.382   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:06.393  1511  4148 V NativeCrypto: Read error: ssl=0x9a995a00: I/O error during system call, Connection timed out
,09-08 17:25:06.395   872  4125 D DhcpClient: Receive thread stopped
,09-08 17:25:06.400   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 17:25:06.400   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 17:25:06.400  1511  4148 V NativeCrypto: SSL shutdown failed: ssl=0x9a995a00: I/O error during system call, Broken pipe
,09-08 17:25:06.406   448   448 E Parcel  : Reading a NULL string not supported here.
09-08 17:25:06.411   872  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-08 17:25:06.416   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 17:25:06.416   872  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 17:25:06.416   872  1309 E native  : do suspend true
,09-08 17:25:06.462   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:06.506   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:06.506   373   870 D CommandListener: Clearing all IP addresses on wlan0
,09-08 17:25:06.508   872  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 17:25:06.508   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:25:06.513   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-08 17:25:06.521  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.521  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:06.522  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.522  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:06.526  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.526  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:06.527   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:25:06.527  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.529  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:06.532  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.532  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:06.532  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.533  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:06.538  2091  2091 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-08 17:25:06.543  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:25:06.548  1727  1727 D SystemUpdateService: onCreate
,09-08 17:25:06.550  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:25:06.552   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:25:06.554  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.554  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:06.554  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 17:25:06.554  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:06.557  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.557  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:06.557  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.557  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:06.558  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:06.558  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:06.558  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:06.558  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:06.559   872  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 17:25:06.562  1916  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 17:25:06.569  1727  4157 I SystemUpdateService: active receiver: enabled
,09-08 17:25:06.569  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 17:25:06.574  1727  4157 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:25:06.575  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:25:06.577  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:25:06.578  3992  3992 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:25:06.582  3992  3992 D SprintDMHelper: simOperator: 
,09-08 17:25:06.583  3992  3992 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:25:06.583  1727  4157 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 17:25:06.584  1727  4157 I SystemUpdateService: now status is 0 (complete)
,09-08 17:25:06.584  1727  4157 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:25:06.584  1727  4157 I SystemUpdateService: file has been verified
,09-08 17:25:06.586  1727  4157 I SystemUpdateService: OTA package size = 12249756
,09-08 17:25:06.590  1727  2398 I iu.UploadsManager: num queued entries: 0
,09-08 17:25:06.595  1727  2398 I iu.UploadsManager: num updated entries: 0
,09-08 17:25:06.600  2294  4161 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 17:25:06.609   373   870 E Netd    : netlink response contains error (No such file or directory)
,09-08 17:25:06.610   872  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 17:25:06.619  1727  2398 I iu.SyncManager: NEXT; no task
,09-08 17:25:06.640  1727  4157 I SystemUpdateService: showing system update notification
,09-08 17:25:06.649  1727  1727 D SystemUpdateService: onDestroy
,09-08 17:25:08.856  1883  1977 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 17:25:08.856  1883  1977 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 17:25:08.889  1511  1511 I ConfigService: onCreate
,09-08 17:25:11.325   872   889 I ActivityManager: Start proc 4168:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 17:25:11.434  4168  4168 D AdapterServiceConfig: Adding HeadsetService
09-08 17:25:11.435  4168  4168 D AdapterServiceConfig: Adding A2dpService
,09-08 17:25:11.435  4168  4168 D AdapterServiceConfig: Adding HidService
09-08 17:25:11.435  4168  4168 D AdapterServiceConfig: Adding HealthService
09-08 17:25:11.436  4168  4168 D AdapterServiceConfig: Adding PanService
09-08 17:25:11.436  4168  4168 D AdapterServiceConfig: Adding GattService
09-08 17:25:11.436  4168  4168 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 17:25:11.457   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@baf91e2:true
,09-08 17:25:11.458  4168  4168 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 17:25:11.463  4168  4168 I bt_bluedroid: init
09-08 17:25:11.464  4168  4180 I BluetoothAdapterState: Entering OffState
,09-08 17:25:11.469  4168  4181 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 17:25:11.470  4168  4181 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 17:25:11.470  4168  4181 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 17:25:11.470  4168  4181 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 17:25:11.472  4168  4168 I bt_bluedroid: get_profile_interface socket
,09-08 17:25:11.474  4168  4168 I bt_bluedroid: get_profile_interface sdp
,09-08 17:25:11.477  4168  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:25:11.478  4168  4178 I bt_bluedroid: config_hci_snoop_log
,09-08 17:25:11.479   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-08 17:25:11.480  4168  4184 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:25:11.488  4168  4180 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 17:25:11.488  4168  4180 D BluetoothAdapterProperties: Setting state to 14
09-08 17:25:11.489  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-08 17:25:11.491  4168  4180 D BluetoothBondStateMachine: make
,09-08 17:25:11.495  4168  4185 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 17:25:11.501  4168  4168 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 17:25:11.502  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:25:11.507  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:11.509  4168  4168 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:25:11.510  4168  4168 D BtGatt.GattService: Received start request. Starting profile...
,09-08 17:25:11.510  4168  4168 D BtGatt.GattService: start()
09-08 17:25:11.510  4168  4168 I bt_bluedroid: get_profile_interface gatt
,09-08 17:25:11.512  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:25:11.512  4168  4168 D BtGatt.AdvertiseManager: advertise manager created
,09-08 17:25:11.524  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:11.524  4168  4168 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:25:11.524  4168  4168 V BluetoothAdapterState: isBleTurningOn()=true
09-08 17:25:11.524  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:11.525  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 17:25:11.525  4168  4180 I bt_bluedroid: enable
,09-08 17:25:11.526  4168  4181 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 17:25:11.527  4168  4181 I bt_hci  : start_up
,09-08 17:25:11.548  4168  4181 I bt_vendor: alloc value 0xb3a79189
09-08 17:25:11.549  4168  4181 I bt_vendor: init
09-08 17:25:11.549  4168  4181 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 17:25:11.549  4168  4181 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 17:25:11.657  4168  4181 D bt_hci  : start_up starting async portion
,09-08 17:25:11.657  4168  4188 I bt_hci  : event_finish_startup
09-08 17:25:11.658  4168  4188 I bt_hci_h4: hal_open
09-08 17:25:11.658  4168  4188 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 17:25:11.666  4168  4188 I bt_userial_vendor: device fd = 51 open
,09-08 17:25:11.699  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:25:11.731  4168  4188 D bt_hwcfg: Chipset BCM4354A2
,09-08 17:25:11.731  4168  4188 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 17:25:11.732  4168  4188 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 17:25:11.757   872  1311 D ConnectivityService: handlePromptUnvalidated 101
,09-08 17:25:12.389  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 17:25:12.390  4168  4188 D bt_hwcfg: Settlement delay -- 100 ms
09-08 17:25:12.391  4168  4188 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 17:25:12.507  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:25:12.509  4168  4188 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
09-08 17:25:12.538  4168  4188 I bt_hwcfg: vendor lib fwcfg completed
09-08 17:25:12.538  4168  4188 I bt_vendor: firmware callback
,09-08 17:25:12.538  4168  4188 I bt_hci  : firmware_config_callback
,09-08 17:25:12.550  4168  4190 I bt_btu  : btu_task pending for preload complete event
,09-08 17:25:12.550  4168  4190 I bt_btu_task: Bluetooth chip preload is complete
,09-08 17:25:12.550  4168  4190 I bt_btu  : btu_task received preload complete event
,09-08 17:25:12.560  4168  4190 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 17:25:12.560  4168  4190 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 17:25:12.561  4168  4190 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 17:25:12.561  4168  4190 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 17:25:12.561  4168  4190 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 17:25:12.561  4168  4190 I         : BTE_InitTraceLevels -- TRC_A2D
,09-08 17:25:12.562  4168  4190 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 17:25:12.562  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 17:25:12.563  4168  4190 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 17:25:12.564  4168  4190 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 17:25:12.564  4168  4190 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 17:25:12.565  4168  4190 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 17:25:12.565  4168  4190 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 17:25:12.565  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 17:25:12.567  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 17:25:12.703  4168  4190 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,09-08 17:25:12.703  4168  4190 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,09-08 17:25:12.715  4168  4184 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 17:25:12.717  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 17:25:12.717  4168  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:25:12.720  4168  4184 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:25:12.724  4168  4184 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:25:12.726  4168  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 17:25:12.726  4168  4184 D bt_hci  : do_postload posting postload work item
,09-08 17:25:12.727  4168  4188 I bt_hci  : event_postload
,09-08 17:25:12.727  4168  4188 I bt_vendor: sco_config_cb
,09-08 17:25:12.727  4168  4188 I bt_hci  : sco_config_callback postload finished.
,09-08 17:25:12.729  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.731  4168  4184 D bt_bte_conf: Device ID record 1 : primary
,09-08 17:25:12.731  4168  4184 D bt_bte_conf:   vendorId            = 000f
,09-08 17:25:12.732  4168  4184 D bt_bte_conf:   vendorIdSource      = 0001
09-08 17:25:12.732  4168  4184 D bt_bte_conf:   product             = 1200
,09-08 17:25:12.732  4168  4188 I bt_vendor: low_power_mode_cb
,09-08 17:25:12.732  4168  4184 D bt_bte_conf:   version             = 1436
09-08 17:25:12.732  4168  4184 D bt_bte_conf:   clientExecutableURL = 
,09-08 17:25:12.733  4168  4184 D bt_bte_conf:   serviceDescription  = 
09-08 17:25:12.733  4168  4184 D bt_bte_conf:   documentationURL    = 
,09-08 17:25:12.733  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:12.733  4168  4184 D bt_bte_conf: bte_load_did_conf no section named DID2.,
09-08 17:25:12.733  4168  4181 D bt_stack_manager: event_start_up_stack finished
09-08 17:25:12.734  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 17:25:12.735  4168  4180 D BluetoothAdapterProperties: Setting state to 15
,09-08 17:25:12.735  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 17:25:12.735  4168  4180 I BluetoothAdapterState: Entering BleOnState
,09-08 17:25:12.737  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.741  4168  4180 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 17:25:12.741  4168  4180 D BluetoothAdapterProperties: Setting state to 11,
09-08 17:25:12.741  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 17:25:12.753  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.756  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.758  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:12.758  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:12.760  4168  4168 D HeadsetService: Received start request. Starting profile...
,09-08 17:25:12.767  4168  4168 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 17:25:12.767  4168  4168 D HeadsetStateMachine: make
,09-08 17:25:12.775  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:25:12.778  4168  4168 D HeadsetStateMachine: max_hf_connections = 1
,09-08 17:25:12.779  4168  4168 I bt_bluedroid: get_profile_interface handsfree
,09-08 17:25:12.780  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 17:25:12.780  4168  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 17:25:12.788  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:12.790  4168  4168 D A2dpService: Received start request. Starting profile...
,09-08 17:25:12.791  4168  4168 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 17:25:12.792  4168  4168 I bt_bluedroid: get_profile_interface avrcp
,09-08 17:25:12.800  4168  4168 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 17:25:12.800  4168  4168 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 17:25:12.801  4168  4168 D A2dpStateMachine: make
,09-08 17:25:12.803  4168  4168 I bt_bluedroid: get_profile_interface a2dp
,09-08 17:25:12.805  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 17:25:12.807  4168  4199 D A2dpStateMachine: Enter Disconnected: -2
,09-08 17:25:12.810  4168  4168 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 17:25:12.811  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 17:25:12.811  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:12.814  4168  4168 D HidService: Received start request. Starting profile...
09-08 17:25:12.815  4168  4168 I bt_bluedroid: get_profile_interface hidhost
09-08 17:25:12.815  4168  4168 D HidService: setHidService(): set to: null
09-08 17:25:12.815  4168  4184 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
,09-08 17:25:12.816  4168  4168 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 17:25:12.816  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 17:25:12.816  3936  3936 D BluetoothInputDevice: Proxy object connected
,09-08 17:25:12.816  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:25:12.817  4168  4168 D HealthService: Received start request. Starting profile...
,09-08 17:25:12.818  3936  3936 D HidProfile: Bluetooth service connected
09-08 17:25:12.819  4168  4168 I bt_bluedroid: get_profile_interface health
,09-08 17:25:12.819  4168  4168 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 17:25:12.820  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:12.822  4168  4168 D PanService: Received start request. Starting profile...
,09-08 17:25:12.822  4168  4168 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 17:25:12.822  3936  3936 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 17:25:12.823  4168  4168 I bt_bluedroid: get_profile_interface pan
,09-08 17:25:12.823  3936  3936 D PanProfile: Bluetooth service connected
,09-08 17:25:12.824  4168  4184 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 17:25:12.826  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:12.827  4168  4168 D BluetoothMapService: Received start request. Starting profile...
09-08 17:25:12.827  4168  4168 D BluetoothMapService: start()
,09-08 17:25:12.828  3936  3936 D BluetoothMap: Proxy object connected
,09-08 17:25:12.829  3936  3936 D MapProfile: Bluetooth service connected
,09-08 17:25:12.829  3936  3936 D BluetoothMap: getConnectedDevices()
,09-08 17:25:12.830  4168  4168 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-08 17:25:12.830  3936  3936 D BluetoothMap: Bluetooth is Not enabled
09-08 17:25:12.831  4168  4168 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 17:25:12.831  4168  4168 D BluetoothMapAppObserver: createReceiver()
,09-08 17:25:12.832  4168  4168 D BluetoothMapAppObserver: initObservers()
09-08 17:25:12.832  4168  4168 D BluetoothMapAppObserver: getEnabledAccountItems()
09-08 17:25:12.841  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:12.841  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:12.841  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:25:12.841  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:12.841  4168  4197 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 17:25:12.843  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:12.843  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:12.843  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:25:12.843  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:12.845  4168  4168 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:25:12.845  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:12.846  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:12.846  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:12.847  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:12.847  4168  4168 V BluetoothAdapterState: isTurningOn()=true
,09-08 17:25:12.848  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:12.848  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:12.849  4168  4168 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:25:12.850  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:12.850  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:12.850  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:12.850  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:12.851  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:12.851  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:25:12.851  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:12.852  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 17:25:12.852  4168  4180 D BluetoothAdapterProperties: ScanMode =  20
09-08 17:25:12.852  4168  4180 D BluetoothAdapterProperties: State =  11
09-08 17:25:12.853  4168  4180 D BluetoothAdapterProperties: Setting state to 12
09-08 17:25:12.853  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 17:25:12.853  4168  4180 I BluetoothAdapterState: Entering OnState
09-08 17:25:12.854  1351  1374 D BluetoothPan: onBluetoothStateChange on: true
09-08 17:25:12.855  4168  4184 D BluetoothAdapterProperties: Scan Mode:21
09-08 17:25:12.856  4168  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 17:25:12.856  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 17:25:12.857  1351  1351 D PanProfile: Bluetooth service connected
09-08 17:25:12.857  3936  3946 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 17:25:12.859  1351  1370 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:12.861  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:12.862  4168  4168 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:25:12.862  1351  1351 D BluetoothMap: Proxy object connected
09-08 17:25:12.862  1351  1351 D MapProfile: Bluetooth service connected
,09-08 17:25:12.863  1351  1351 D BluetoothMap: getConnectedDevices()
,09-08 17:25:12.864  4168  4168 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 17:25:12.864  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:12.864  1351  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 17:25:12.867  1351  1351 D BluetoothInputDevice: Proxy object connected
,09-08 17:25:12.867  1351  1351 D HidProfile: Bluetooth service connected
09-08 17:25:12.868  1351  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:25:12.869  4168  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 17:25:12.870  1351  1931 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:12.870  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:12.872  1997  2260 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:12.872  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:12.873  3936  3948 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:25:12.873  4168  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:12.874  4168  4168 D ObexServerSockets: Succeed to create listening sockets 
09-08 17:25:12.874  4168  4168 D ObexServerSockets0: startAccept()
09-08 17:25:12.875  4168  4168 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:25:12.875  1351  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:12.876  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:12.877  3936  3946 D BluetoothPan: onBluetoothStateChange on: true
,09-08 17:25:12.877  4168  4168 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 17:25:12.877  4168  4168 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 17:25:12.878   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 17:25:12.878  4168  4205 D ObexServerSockets0: Accepting socket connection...
09-08 17:25:12.878  4168  4206 D ObexServerSockets0: Accepting socket connection...
09-08 17:25:12.878   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:25:12.879  1351  1351 D BluetoothA2dp: Proxy object connected
09-08 17:25:12.879  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:12.880   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:12.880   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:12.880   872   872 D BluetoothA2dp: Proxy object connected
09-08 17:25:12.880  3936  3948 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 17:25:12.883   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 17:25:12.886  4168  4168 D BluetoothMapService: onReceive
,09-08 17:25:12.886  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:12.886  4168  4168 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 17:25:12.886  4168  4168 D BluetoothMapService: STATE_ON
09-08 17:25:12.887  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.888  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:12.889  3936  3936 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 17:25:12.893  3936  3936 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 17:25:12.901  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:25:12.904  3936  3936 D BluetoothA2dp: Proxy object connected
,09-08 17:25:12.907  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:25:12.911  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:25:12.915  1351  1351 D BluetoothPbap: Proxy object connected
,09-08 17:25:12.915  1351  1351 D PbapServerProfile: Bluetooth service connected
09-08 17:25:12.915  4168  4168 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:25:12.915  3936  3936 D BluetoothPbap: Proxy object connected
09-08 17:25:12.916  4168  4168 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:25:12.916  3936  3936 D PbapServerProfile: Bluetooth service connected
,09-08 17:25:12.923  4168  4210 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:12.938  4168  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:12.939  4168  4214 I BtOppRfcommListener: Accept thread started.
,09-08 17:25:12.974   872   872 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.974   872   872 D BluetoothHeadset: Proxy object connected,
09-08 17:25:12.974  1351  1931 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.975  1351  1351 D HeadsetProfile: Bluetooth service connected
09-08 17:25:12.975  1997  2010 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.976   872   872 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.977  1351  1370 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.977   872   889 D BluetoothHeadset: Proxy object connected
09-08 17:25:12.977  1351  1351 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:12.980   872   889 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.981   872   889 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.996  3936  3946 D BluetoothHeadset: Proxy object connected
,09-08 17:25:12.997  3936  3936 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:13.944  1511  1511 I ConfigService: onDestroy
,09-08 17:25:16.307  4168  4180 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 17:25:16.308  4168  4180 D BluetoothAdapterProperties: Setting state to 13
09-08 17:25:16.308  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 17:25:16.310  4168  4180 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 17:25:16.316  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:25:16.322  4168  4168 D BluetoothMapService: onReceive
09-08 17:25:16.323  4168  4168 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 17:25:16.323  4168  4168 D BluetoothMapService: STATE_TURNING_OFF
09-08 17:25:16.324  4168  4168 D BluetoothMapService: MAP Service closeService in
09-08 17:25:16.324  4168  4168 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 17:25:16.324  4168  4168 D ObexServerSockets0: shutdown(block = true)
09-08 17:25:16.326  4168  4205 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 17:25:16.327  4168  4168 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:25:16.328  4168  4206 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 17:25:16.328  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:16.329  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:16.330  4168  4168 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 17:25:16.332  4168  4192 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 17:25:16.333  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.333  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:16.333  4168  4184 D BluetoothAdapterProperties: Scan Mode:20
09-08 17:25:16.335  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 17:25:16.334  4168  4168 I BtOppRfcommListener: stopping Accept Thread
,09-08 17:25:16.339  4168  4214 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 17:25:16.339  4168  4214 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 17:25:16.341  4168  4168 D HeadsetService: Received stop request...Stopping profile...
09-08 17:25:16.341  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:16.341  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:16.342  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.342  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:16.342   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 17:25:16.343   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 17:25:16.343  3936  3948 D BluetoothHeadset: Proxy object disconnected
,09-08 17:25:16.344  1351  1370 D BluetoothHeadset: Proxy object disconnected
09-08 17:25:16.344  4168  4168 D A2dpService: Received stop request...Stopping profile...
09-08 17:25:16.344  4168  4199 D A2dpStateMachine: Exit Disconnected: -1
09-08 17:25:16.344  1997  2020 D BluetoothHeadset: Proxy object disconnected
09-08 17:25:16.344   872   872 D BluetoothHeadset: Proxy object disconnected
09-08 17:25:16.345  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:16.345  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:16.346  3876  3876 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 17:25:16.346  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 17:25:16.346   872   872 D BluetoothA2dp: Proxy object disconnected
09-08 17:25:16.348  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:16.349  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:16.350  4168  4168 D HidService: Received stop request...Stopping profile...
09-08 17:25:16.350  4168  4168 D HidService: Stopping Bluetooth HidService
09-08 17:25:16.350  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.351  1351  1351 D HeadsetProfile: Bluetooth service disconnected
,09-08 17:25:16.351  1351  1351 D BluetoothA2dp: Proxy object disconnected
09-08 17:25:16.351  1351  1351 D BluetoothInputDevice: Proxy object disconnected
09-08 17:25:16.352  1351  1351 D HidProfile: Bluetooth service disconnected
09-08 17:25:16.352  4168  4168 V BluetoothAdapterState: isTurningOff()=true
09-08 17:25:16.351  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:25:16.352  4168  4168 V BluetoothAdapterState: isTurningOn()=false
09-08 17:25:16.352  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.352  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:16.357  4168  4168 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 17:25:16.357  4168  4168 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 17:25:16.357  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 17:25:16.357  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:25:16.357  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:25:16.357  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 17:25:16.358  4168  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 17:25:16.359  4168  4168 D HealthService: Received stop request...Stopping profile...
09-08 17:25:16.360  4168  4168 V BluetoothAdapterState: isTurningOff()=true
09-08 17:25:16.360  4168  4168 V BluetoothAdapterState: isTurningOn()=false
09-08 17:25:16.360  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.360  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:16.361  4168  4168 D PanService: Received stop request...Stopping profile...
,09-08 17:25:16.363  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 17:25:16.363  1351  1351 D PanProfile: Bluetooth service disconnected
09-08 17:25:16.363  3936  3936 D HeadsetProfile: Bluetooth service disconnected
09-08 17:25:16.364  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 17:25:16.364  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:25:16.364  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:25:16.364  4168  4190 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:25:16.364  4168  4190 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 17:25:16.364  4168  4190 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 17:25:16.364  4168  4190 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 17:25:16.365  4168  4168 D BluetoothMapService: Received stop request...Stopping profile...
09-08 17:25:16.365  4168  4168 D BluetoothMapService: stop()
,09-08 17:25:16.365  3936  3936 D BluetoothA2dp: Proxy object disconnected
09-08 17:25:16.365  3936  3936 D BluetoothInputDevice: Proxy object disconnected
09-08 17:25:16.365  4168  4168 D BluetoothMapAppObserver: deinitObservers()
09-08 17:25:16.365  3936  3936 D HidProfile: Bluetooth service disconnected
,09-08 17:25:16.365  4168  4168 D BluetoothMapAppObserver: removeReceiver()
09-08 17:25:16.367  4168  4168 V BluetoothAdapterState: isTurningOff()=true
09-08 17:25:16.367  4168  4168 V BluetoothAdapterState: isTurningOn()=false
09-08 17:25:16.367  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.367  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:16.367  4168  4168 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 17:25:16.368  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:25:16.368  4168  4168 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 17:25:16.368  1351  1351 D BluetoothMap: Proxy object disconnected
09-08 17:25:16.368  1351  1351 D MapProfile: Bluetooth service disconnected
,09-08 17:25:16.370  4168  4168 V BluetoothAdapterState: isTurningOff()=true
,09-08 17:25:16.371  4168  4168 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:25:16.371  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.371  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:16.371  4168  4168 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 17:25:16.371  4168  4184 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 17:25:16.371  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:25:16.372  4168  4168 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 17:25:16.372  4168  4168 V BluetoothAdapterState: isTurningOff()=true
,09-08 17:25:16.372  4168  4168 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:25:16.372  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.372  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:16.373  4168  4168 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 17:25:16.373  4168  4168 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 17:25:16.374  4168  4168 D BluetoothMapService: MAP Service closeService in
09-08 17:25:16.374  4168  4168 V BluetoothAdapterState: isTurningOff()=true
09-08 17:25:16.374  4168  4168 V BluetoothAdapterState: isTurningOn()=false
09-08 17:25:16.374  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false,
09-08 17:25:16.374  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:16.374  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 17:25:16.374  4168  4180 D BluetoothAdapterProperties: Setting state to 15
09-08 17:25:16.374  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 17:25:16.375  4168  4168 D BluetoothMapService: cleanup()
09-08 17:25:16.375  4168  4168 D BluetoothMapService: MAP Service closeService in
09-08 17:25:16.375  4168  4180 I BluetoothAdapterState: Entering BleOnState
09-08 17:25:16.376  1351  1370 D BluetoothPan: onBluetoothStateChange on: false
,09-08 17:25:16.376  3936  3936 D DockEventReceiver: finishStartingService: stopping service
09-08 17:25:16.376  3936  3946 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 17:25:16.377  1351  1351 D BluetoothPbap: Proxy object disconnected
09-08 17:25:16.377  1351  1351 D PbapServerProfile: Bluetooth service disconnected
09-08 17:25:16.377  3936  3948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:25:16.378  3936  3936 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 17:25:16.378  3936  3936 D PanProfile: Bluetooth service disconnected
09-08 17:25:16.379  3936  3936 D BluetoothMap: Proxy object disconnected
09-08 17:25:16.381  1351  1370 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 17:25:16.379  3936  3936 D MapProfile: Bluetooth service disconnected
09-08 17:25:16.381  3936  3936 D BluetoothPbap: Proxy object disconnected
09-08 17:25:16.382  3936  3936 D PbapServerProfile: Bluetooth service disconnected
09-08 17:25:16.383  1351  1931 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 17:25:16.384  1351  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:25:16.385  1351  1370 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 17:25:16.385  1997  2129 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:25:16.386  3936  3948 D BluetoothPbap: onBluetoothStateChange: up=false,
09-08 17:25:16.386  1351  1931 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:25:16.386  3936  4218 D BluetoothPan: onBluetoothStateChange on: false
09-08 17:25:16.387   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:25:16.387   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 17:25:16.387  3936  3946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:25:16.387   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 17:25:16.387   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 17:25:16.387  3936  3948 D BluetoothMap: onBluetoothStateChange: up=false
09-08 17:25:16.388  4168  4180 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 17:25:16.388  4168  4180 D BluetoothAdapterProperties: Setting state to 16
09-08 17:25:16.388  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 17:25:16.389  4168  4180 D BluetoothAdapterProperties: onBleDisable
09-08 17:25:16.389  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:25:16.389  4168  4181 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 17:25:16.390  4168  4190 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 17:25:16.390  4168  4190 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 17:25:16.391  4168  4184 D BluetoothAdapterProperties: Scan Mode:20
,09-08 17:25:16.395  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:25:16.395  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.396  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.397  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.398  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.400  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:16.400  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 17:25:16.401  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:16.407  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:25:16.592  4168  4184 I bt_hci  : shut_down
,09-08 17:25:16.592  4168  4188 D bt_hwcfg: hw_epilog_process
,09-08 17:25:16.604  4168  4188 I bt_vendor: low_power_mode_cb
,09-08 17:25:16.631  4168  4188 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 17:25:16.631  4168  4188 I bt_vendor: epilog_cb
09-08 17:25:16.631  4168  4188 I bt_hci  : epilog_finished_callback
,09-08 17:25:16.639  4168  4184 I bt_hci_h4: hal_close
,09-08 17:25:16.640  4168  4184 I bt_userial_vendor: device fd = 51 close
,09-08 17:25:16.753  4168  4181 D bt_stack_manager: event_shut_down_stack finished.
,09-08 17:25:16.755  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 17:25:16.760  4168  4168 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:25:16.761  4168  4180 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 17:25:16.762  4168  4168 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 17:25:16.763  4168  4168 D BtGatt.GattService: stop()
09-08 17:25:16.764  4168  4168 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 17:25:16.770  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:16.770  4168  4168 V BluetoothAdapterState: isTurningOn()=false
,09-08 17:25:16.770  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:16.771  4168  4168 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 17:25:16.772  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 17:25:16.772  4168  4180 D BluetoothAdapterProperties: Setting state to 10
09-08 17:25:16.773  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 17:25:16.775  4168  4180 I BluetoothAdapterState: Entering OffState
,09-08 17:25:16.776   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 17:25:16.807  4168  4168 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 17:25:16.807  4168  4168 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 17:25:16.808  4168  4181 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 17:25:16.817  4168  4181 D bt_stack_manager: event_clean_up_stack finished.
,09-08 17:25:16.817  4168  4168 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 17:25:16.822  4168  4168 I art     : System.exit called, status: 0
,09-08 17:25:16.822  4168  4168 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 17:25:16.873   872  2017 I ActivityManager: Process com.android.bluetooth (pid 4168) has died
,09-08 17:25:21.304  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:25:21.305  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:21.309  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:25:21.310  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1659f84 removed from the list
09-08 17:25:21.311  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:25:21.311  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:21.312  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:21.317  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:25:21.317  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@207eba2 added. We now have 4 listener(s)
09-08 17:25:21.317  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:25:21.319  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:25:21.320  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@207eba2 removed from the list
,09-08 17:25:21.321  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:25:21.321  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:25:21.322  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:21.324  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:25:21.325  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@876e033 added. We now have 4 listener(s)
,09-08 17:25:21.325  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:25:26.337  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:26.386   872   889 I ActivityManager: Start proc 4225:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 17:25:26.519  4225  4225 D AdapterServiceConfig: Adding HeadsetService
,09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding A2dpService
09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding HidService
09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding HealthService
09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding PanService
09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding GattService
,09-08 17:25:26.520  4225  4225 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 17:25:26.533   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec0d297:true
,09-08 17:25:26.533  4225  4225 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 17:25:26.543  4225  4225 I bt_bluedroid: init
,09-08 17:25:26.543  4225  4237 I BluetoothAdapterState: Entering OffState
,09-08 17:25:26.547  4225  4238 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 17:25:26.547  4225  4238 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 17:25:26.547  4225  4238 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 17:25:26.547  4225  4238 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 17:25:26.548  4225  4225 I bt_bluedroid: get_profile_interface socket
,09-08 17:25:26.551  4225  4225 I bt_bluedroid: get_profile_interface sdp
09-08 17:25:26.554  4225  4241 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:25:26.557  4225  4236 I bt_bluedroid: config_hci_snoop_log
09-08 17:25:26.557  4225  4241 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 17:25:26.558   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 17:25:26.568  4225  4237 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 17:25:26.569  4225  4237 D BluetoothAdapterProperties: Setting state to 14
,09-08 17:25:26.569  4225  4237 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-08 17:25:26.574  4225  4237 D BluetoothBondStateMachine: make
,09-08 17:25:26.580  4225  4242 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 17:25:26.592  4225  4237 I BluetoothAdapterState: Entering PendingCommandState
09-08 17:25:26.594  4225  4225 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 17:25:26.604  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:26.606  4225  4225 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 17:25:26.608  4225  4225 D BtGatt.GattService: Received start request. Starting profile...
09-08 17:25:26.608  4225  4225 D BtGatt.GattService: start()
09-08 17:25:26.609  4225  4225 I bt_bluedroid: get_profile_interface gatt
,09-08 17:25:26.613  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:26.613  4225  4225 D BtGatt.AdvertiseManager: advertise manager created
,09-08 17:25:26.624  4225  4225 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:25:26.624  4225  4225 V BluetoothAdapterState: isTurningOn()=false
09-08 17:25:26.624  4225  4225 V BluetoothAdapterState: isBleTurningOn()=true
09-08 17:25:26.624  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:26.625  4225  4237 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 17:25:26.625  4225  4237 I bt_bluedroid: enable
09-08 17:25:26.626  4225  4238 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 17:25:26.627  4225  4238 I bt_hci  : start_up
,09-08 17:25:26.647  4225  4238 I bt_vendor: alloc value 0xb3a79189
09-08 17:25:26.648  4225  4238 I bt_vendor: init
09-08 17:25:26.648  4225  4238 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 17:25:26.648  4225  4238 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 17:25:26.757  4225  4238 D bt_hci  : start_up starting async portion
,09-08 17:25:26.758  4225  4245 I bt_hci  : event_finish_startup
,09-08 17:25:26.758  4225  4245 I bt_hci_h4: hal_open
09-08 17:25:26.759  4225  4245 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 17:25:26.770  4225  4245 I bt_userial_vendor: device fd = 51 open
,09-08 17:25:26.800  4225  4245 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:25:26.831  4225  4245 D bt_hwcfg: Chipset BCM4354A2
09-08 17:25:26.832  4225  4245 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 17:25:26.832  4225  4245 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 17:25:27.624  4225  4245 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 17:25:27.626  4225  4245 D bt_hwcfg: Settlement delay -- 100 ms
09-08 17:25:27.627  4225  4245 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 17:25:27.743  4225  4245 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 17:25:27.744  4225  4245 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 17:25:27.774  4225  4245 I bt_hwcfg: vendor lib fwcfg completed
,09-08 17:25:27.774  4225  4245 I bt_vendor: firmware callback
09-08 17:25:27.774  4225  4245 I bt_hci  : firmware_config_callback
,09-08 17:25:27.785  4225  4248 I bt_btu  : btu_task pending for preload complete event
,09-08 17:25:27.786  4225  4248 I bt_btu_task: Bluetooth chip preload is complete
09-08 17:25:27.786  4225  4248 I bt_btu  : btu_task received preload complete event
,09-08 17:25:27.796  4225  4248 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 17:25:27.796  4225  4248 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 17:25:27.796  4225  4248 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 17:25:27.797  4225  4248 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 17:25:27.797  4225  4248 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 17:25:27.797  4225  4248 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 17:25:27.798  4225  4248 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 17:25:27.798  4225  4248 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 17:25:27.798  4225  4248 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 17:25:27.798  4225  4248 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 17:25:27.799  4225  4248 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 17:25:27.799  4225  4248 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 17:25:27.799  4225  4248 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 17:25:27.799  4225  4248 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 17:25:27.800  4225  4248 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 17:25:27.931  4225  4248 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d,
09-08 17:25:27.932  4225  4248 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,09-08 17:25:27.942  4225  4241 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-08 17:25:27.944  4225  4241 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 17:25:27.945  4225  4241 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 17:25:27.948  4225  4241 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 17:25:27.951  4225  4241 D BluetoothAdapterProperties: Scan Mode:20
,09-08 17:25:27.952  4225  4241 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 17:25:27.952  4225  4241 D bt_hci  : do_postload posting postload work item
,09-08 17:25:27.954  4225  4245 I bt_hci  : event_postload
09-08 17:25:27.954  4225  4245 I bt_vendor: sco_config_cb
,09-08 17:25:27.954  4225  4245 I bt_hci  : sco_config_callback postload finished.
09-08 17:25:27.957  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:27.958  4225  4241 D bt_bte_conf: Device ID record 1 : primary
09-08 17:25:27.958  4225  4241 D bt_bte_conf:   vendorId            = 000f
09-08 17:25:27.959  4225  4241 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 17:25:27.959  4225  4241 D bt_bte_conf:   product             = 1200
09-08 17:25:27.959  4225  4241 D bt_bte_conf:   version             = 1436
09-08 17:25:27.959  4225  4245 I bt_vendor: low_power_mode_cb
09-08 17:25:27.959  4225  4241 D bt_bte_conf:   clientExecutableURL = 
,09-08 17:25:27.960  4225  4241 D bt_bte_conf:   serviceDescription  = 
09-08 17:25:27.960  4225  4241 D bt_bte_conf:   documentationURL    = 
09-08 17:25:27.961  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:27.961  4225  4241 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 17:25:27.962  4225  4238 D bt_stack_manager: event_start_up_stack finished
,09-08 17:25:27.964  4225  4237 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 17:25:27.965  4225  4237 D BluetoothAdapterProperties: Setting state to 15
09-08 17:25:27.965  4225  4237 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 17:25:27.968  4225  4237 I BluetoothAdapterState: Entering BleOnState
,09-08 17:25:27.972  4225  4237 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 17:25:27.972  4225  4237 D BluetoothAdapterProperties: Setting state to 11
,09-08 17:25:27.973  4225  4237 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 17:25:27.984  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:25:27.985  4225  4225 D HeadsetService: Received start request. Starting profile...
,09-08 17:25:27.988  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:27.988  4225  4225 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 17:25:27.988  4225  4225 D HeadsetStateMachine: make
,09-08 17:25:27.991  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:28.004  4225  4225 D HeadsetStateMachine: max_hf_connections = 1
,09-08 17:25:28.004  4225  4225 I bt_bluedroid: get_profile_interface handsfree
,09-08 17:25:28.004  4225  4241 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 17:25:28.004  4225  4237 I BluetoothAdapterState: Entering PendingCommandState
,09-08 17:25:28.005  4225  4241 E bt_btif : btif_hf_upstreams_evt: Invalid index 1024
,09-08 17:25:28.010  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:28.011  4225  4225 D A2dpService: Received start request. Starting profile...
,09-08 17:25:28.012  4225  4225 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 17:25:28.012  4225  4225 I bt_bluedroid: get_profile_interface avrcp
,09-08 17:25:28.019  4225  4225 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 17:25:28.020  4225  4225 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 17:25:28.020  4225  4225 D A2dpStateMachine: make
,09-08 17:25:28.022  4225  4225 I bt_bluedroid: get_profile_interface a2dp
,09-08 17:25:28.022  4225  4241 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 17:25:28.025  4225  4225 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 17:25:28.026  4225  4256 D A2dpStateMachine: Enter Disconnected: -2
,09-08 17:25:28.026  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:28.027  4225  4225 D HidService: Received start request. Starting profile...
,09-08 17:25:28.027  4225  4225 I bt_bluedroid: get_profile_interface hidhost
09-08 17:25:28.027  4225  4225 D HidService: setHidService(): set to: null
,09-08 17:25:28.027  4225  4241 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
,09-08 17:25:28.027  4225  4241 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-08 17:25:28.028  4225  4225 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 17:25:28.029  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:28.030  4225  4225 D HealthService: Received start request. Starting profile...
,09-08 17:25:28.031  4225  4225 I bt_bluedroid: get_profile_interface health
,09-08 17:25:28.034  4225  4225 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 17:25:28.035  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:25:28.035  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:25:28.036  4225  4225 D PanService: Received start request. Starting profile...
09-08 17:25:28.036  4225  4225 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 17:25:28.036  4225  4225 I bt_bluedroid: get_profile_interface pan
09-08 17:25:28.037  4225  4241 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 17:25:28.041  4225  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
,09-08 17:25:28.041  4225  4225 D BluetoothMapService: Received start request. Starting profile...
09-08 17:25:28.041  4225  4225 D BluetoothMapService: start()
,09-08 17:25:28.044  4225  4225 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 17:25:28.045  4225  4225 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 17:25:28.045  4225  4225 D BluetoothMapAppObserver: createReceiver()
,09-08 17:25:28.046  4225  4225 D BluetoothMapAppObserver: initObservers()
09-08 17:25:28.046  4225  4225 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 17:25:28.052  4225  4225 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:25:28.052  4225  4225 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:28.053  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:28.053  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:28.054  4225  4225 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:28.054  4225  4225 V BluetoothAdapterState: isTurningOn()=true
,09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:28.055  4225  4254 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isTurningOff()=false
,09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isTurningOn()=true
,09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:28.055  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:28.056  4225  4225 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:28.056  4225  4225 V BluetoothAdapterState: isTurningOn()=true
09-08 17:25:28.056  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
09-08 17:25:28.056  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
09-08 17:25:28.056  4225  4225 V BluetoothAdapterState: isTurningOff()=false
09-08 17:25:28.057  4225  4225 V BluetoothAdapterState: isTurningOn()=true
,09-08 17:25:28.057  4225  4225 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 17:25:28.057  4225  4225 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 17:25:28.057  4225  4237 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 17:25:28.057  4225  4237 D BluetoothAdapterProperties: ScanMode =  20
09-08 17:25:28.057  4225  4237 D BluetoothAdapterProperties: State =  11
09-08 17:25:28.057  4225  4237 D BluetoothAdapterProperties: Setting state to 12
,09-08 17:25:28.058  4225  4237 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 17:25:28.059  4225  4237 I BluetoothAdapterState: Entering OnState
09-08 17:25:28.059  1351  1370 D BluetoothPan: onBluetoothStateChange on: true
,09-08 17:25:28.059  4225  4241 D BluetoothAdapterProperties: Scan Mode:21
09-08 17:25:28.059  4225  4241 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 17:25:28.062  3936  3946 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:28.063  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 17:25:28.066  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:28.067  3936  3948 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 17:25:28.068  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 17:25:28.069  1351  1351 D PanProfile: Bluetooth service connected
,09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:28.070  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:28.071  1351  1931 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 17:25:28.072  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:28.073  4225  4225 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 17:25:28.073  3936  3936 D BluetoothInputDevice: Proxy object connected
,09-08 17:25:28.073  1351  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 17:25:28.073  3936  3936 D HidProfile: Bluetooth service connected
,09-08 17:25:28.073  4225  4225 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 17:25:28.075  3936  3936 D BluetoothA2dp: Proxy object connected
09-08 17:25:28.075  4225  4225 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:28.075  1351  1351 D BluetoothInputDevice: Proxy object connected
,09-08 17:25:28.075  1351  1351 D HidProfile: Bluetooth service connected
,09-08 17:25:28.075  1351  1931 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 17:25:28.077  1351  1351 D BluetoothA2dp: Proxy object connected
09-08 17:25:28.077  1351  1370 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:25:28.077  4225  4225 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:28.079  1997  2129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:28.079  4225  4225 D ObexServerSockets: Succeed to create listening sockets 
09-08 17:25:28.079  4225  4225 D ObexServerSockets0: startAccept()
09-08 17:25:28.079  4225  4225 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:25:28.079  3936  4218 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 17:25:28.081  1351  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:28.081  3936  3948 D BluetoothPan: onBluetoothStateChange on: true
09-08 17:25:28.083   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 17:25:28.083   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 17:25:28.083  3936  4218 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 17:25:28.083   872   872 D BluetoothA2dp: Proxy object connected
09-08 17:25:28.084   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 17:25:28.084   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 17:25:28.084  4225  4225 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 17:25:28.084  4225  4225 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 17:25:28.084  3936  3948 D BluetoothMap: onBluetoothStateChange: up=true
09-08 17:25:28.084  3936  3936 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 17:25:28.085  1351  1351 D BluetoothMap: Proxy object connected
09-08 17:25:28.085  1351  1351 D MapProfile: Bluetooth service connected
,09-08 17:25:28.085  1351  1351 D BluetoothMap: getConnectedDevices()
09-08 17:25:28.088   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 17:25:28.088  4225  4263 D ObexServerSockets0: Accepting socket connection...
,09-08 17:25:28.088  4225  4225 D BluetoothMapService: onReceive
09-08 17:25:28.088  4225  4225 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 17:25:28.088  4225  4225 D BluetoothMapService: STATE_ON
,09-08 17:25:28.089  4225  4264 D ObexServerSockets0: Accepting socket connection...
,09-08 17:25:28.084  3936  3936 D PanProfile: Bluetooth service connected
,09-08 17:25:28.089  3936  3936 D BluetoothMap: Proxy object connected
,09-08 17:25:28.089  3936  3936 D MapProfile: Bluetooth service connected
,09-08 17:25:28.089  3936  3936 D BluetoothMap: getConnectedDevices()
09-08 17:25:28.089  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:28.090  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:28.095  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 17:25:28.099  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,09-08 17:25:28.101  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 17:25:28.109  3936  3936 D BluetoothPbap: Proxy object connected
,09-08 17:25:28.109  3936  3936 D PbapServerProfile: Bluetooth service connected
,09-08 17:25:28.114  1351  1351 D BluetoothPbap: Proxy object connected
,09-08 17:25:28.114  1351  1351 D PbapServerProfile: Bluetooth service connected
,09-08 17:25:28.115  4225  4225 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 17:25:28.115  4225  4225 D ObexServerSockets0: prepareForNewConnect()
,09-08 17:25:28.119  4225  4269 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:28.130  4225  4273 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:28.131  4225  4273 I BtOppRfcommListener: Accept thread started.
,09-08 17:25:28.180   872   872 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.180   872   872 D BluetoothHeadset: Proxy object connected
,09-08 17:25:28.181  3936  4218 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.181  1351  1370 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.181  1351  1351 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:28.182  1997  2260 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.182  1351  1374 D BluetoothHeadset: Proxy object connected
,09-08 17:25:28.182   872   872 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.182   872   889 D BluetoothHeadset: Proxy object connected
,09-08 17:25:28.184  3936  3946 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.184   872   889 D BluetoothHeadset: Proxy object connected
09-08 17:25:28.184   872   889 D BluetoothHeadset: Proxy object connected
,09-08 17:25:28.185  1351  1351 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:28.186  3936  3936 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:28.188  3936  3936 D HeadsetProfile: Bluetooth service connected
,09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:31.358  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:31.365  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:31.366  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:31.366  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@876e033 removed from the list
,09-08 17:25:31.367  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:25:31.367  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:25:31.367  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:31.370  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:25:31.370  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5f2ff0 added. We now have 4 listener(s)
09-08 17:25:31.371  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:25:31.375   872   883 D WifiService: setWifiEnabled: false pid=3876, uid=10000
09-08 17:25:31.375   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:25:36.388  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:36.389   872  1919 D WifiService: setWifiEnabled: true pid=3876, uid=10000
,09-08 17:25:36.389   872  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 17:25:36.405   872  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:36.425  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:36.429  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 17:25:36.436  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 17:25:36.437   872  1309 D WifiConfigStore: loaded 0 passpoint configs
09-08 17:25:36.438   872  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 17:25:36.439   872  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 17:25:36.439   872  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 17:25:36.440   872  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 17:25:36.440   872  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 17:25:36.440   872  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-08 17:25:36.441  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 17:25:36.453   373   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 17:25:36.453   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:25:36.459   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:36.504   872  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 17:25:36.504   872  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 17:25:36.506   872  1309 E native  : do suspend true
,09-08 17:25:36.528   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:25:36.531   872  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 17:25:36.535   872  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 17:25:37.806   872  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 17:25:37.939   872  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.75 rxSuccessRate=15.56 delta 1000 -> 994
09-08 17:25:37.941   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 17:25:37.941   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:25:37.962   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 17:25:38.027   872  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 17:25:38.029  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 17:25:38.466  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 17:25:38.516  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 17:25:38.516  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 17:25:38.523   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 17:25:38.539   872  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:25:38.539   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 17:25:38.540   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 17:25:38.563   872  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 17:25:38.575   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:38.577   872  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 17:25:38.591   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 17:25:38.608   872  4283 D DhcpClient: Receive thread started
,09-08 17:25:38.703   872  1309 E native  : do suspend false
,09-08 17:25:38.728   872  1846 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 17:25:38.741   872  4283 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 17:25:38.742   872  1846 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 17:25:38.746   872  1846 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 17:25:38.761   872  4283 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 17:25:38.762   872  1846 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 17:25:38.767   373   870 D CommandListener: Setting iface cfg
,09-08 17:25:38.779   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-08 17:25:38.781   872  1846 D DhcpClient: Scheduling renewal in 86399s
,09-08 17:25:38.781   872  1309 E native  : do suspend true
,09-08 17:25:38.809   872  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 17:25:38.812   872  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 17:25:38.815   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 17:25:38.818   872  1311 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 17:25:38.830   872  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 17:25:38.902   872  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 17:25:38.902   872  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 17:25:38.906   872  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 17:25:38.907   872  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 17:25:38.908   872  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 17:25:38.922   872  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 17:25:38.927   872  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 17:25:38.928   872  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 17:25:38.928   872  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 17:25:38.929   872  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 17:25:38.929   872  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-08 17:25:38.929   872  1311 D ConnectivityService:    accepting network in place of null
09-08 17:25:38.930   872  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 17:25:38.949   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402751, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:25:38.999   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:39.050   373   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 17:25:39.057   872  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 17:25:39.057   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:25:39.064   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-08 17:25:39.071   872  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 17:25:39.074   872  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:39.090  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:39.092  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:39.099  3876  3876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:39.101  3876  3876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:39.103  2091  2091 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-08 17:25:39.104  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 17:25:39.111  1727  1727 D SystemUpdateService: onCreate
,09-08 17:25:39.116  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 17:25:39.135   872  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 15:25:39 GMT], X-Android-Received-Millis=[1473348339134], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473348339112]}
,09-08 17:25:39.136   872  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 17:25:39.136   872  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 17:25:39.137   872  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 17:25:39.138  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 17:25:39.143   872  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 17:25:39.149  1727  4292 I SystemUpdateService: active receiver: enabled
,09-08 17:25:39.151  1727  2398 I iu.UploadsManager: num queued entries: 0
,09-08 17:25:39.152  1727  2398 I iu.UploadsManager: num updated entries: 0
,09-08 17:25:39.153  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 17:25:39.157  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 17:25:39.158  3992  3992 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 17:25:39.160  1727  4292 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 17:25:39.165  1727  4294 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 17:25:39.165  1727  4294 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 17:25:39.166  1727  4294 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 17:25:39.169  1727  4292 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 17:25:39.169  1727  4292 I SystemUpdateService: now status is 0 (complete)
,09-08 17:25:39.169  1727  4292 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 17:25:39.169  1727  4292 I SystemUpdateService: file has been verified
09-08 17:25:39.169  1727  4292 I SystemUpdateService: OTA package size = 12249756
09-08 17:25:39.169  1727  2398 I iu.SyncManager: NEXT; no task
,09-08 17:25:39.172  3992  3992 D SprintDMHelper: simOperator: 
09-08 17:25:39.172  3992  3992 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 17:25:39.178  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:25:39.183  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:25:39.237  1727  4292 I SystemUpdateService: showing system update notification
,09-08 17:25:39.266  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 17:25:39.266  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 17:25:39.266  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:25:39.266  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:25:39.270  1727  1727 D SystemUpdateService: onDestroy
,09-08 17:25:39.309  1727  4294 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-08 17:25:39.325  2294  4298 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 17:25:40.057   872  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:41.418  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:41.425  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:41.426  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:41.426  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5f2ff0 removed from the list
09-08 17:25:41.427  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 17:25:41.427  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:41.427  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:41.440  3876  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 17:25:41.440  3876  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 17:25:44.448  3876  4304 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 17:25:44.449  3876  4305 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 17:25:44.450  3876  4305 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:25:44.450  3876  4304 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:25:44.451  3876  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:25:44.451  3876  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:25:44.452  3876  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:25:44.453  3876  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:25:44.457  3876  4304 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 17:25:44.457  3876  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-08 17:25:44.460  3876  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
,09-08 17:25:44.461  3876  4305 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 17:25:44.464  3876  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,09-08 17:25:44.464  3876  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Receiver)
09-08 17:25:44.465  3876  4310 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: IncomingSocketThread/Receiver)
,09-08 17:25:44.465  3876  4310 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 17:25:44.465  3876  4310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 17:25:44.466  3876  4309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
09-08 17:25:44.466  3876  4309 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 17:25:44.466  3876  4309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 17:25:46.935   872  1311 D ConnectivityService: handlePromptUnvalidated 102
,09-08 17:25:47.447  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 17:25:47.449  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 17:25:47.457  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c21beaa Bundle[{}]
,09-08 17:25:47.457  3876  3922 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 17:25:47.458  3876  3922 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 17:25:47.458  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 17:25:47.459  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 17:25:47.459  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 17:25:47.460  3876  3922 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 17:25:47.464  3876  3922 I System.out: Running OutgoingSocketThread
,09-08 17:25:47.469  3876  4311 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 17:25:47.469  3876  4311 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 17:25:50.477  3876  4311 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 17:25:50.478  3876  4311 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:25:50.478  3876  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:25:50.480  3876  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:25:50.482  3876  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Sender)
,09-08 17:25:50.483  3876  4311 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 17:25:50.485  3876  4315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Receiver)
09-08 17:25:50.487  3876  4315 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: OutgoingSocketThread/Receiver)
,09-08 17:25:50.487  3876  4315 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 17:25:50.487  3876  4312 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 17:25:50.487  3876  4315 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 17:25:50.487  3876  4312 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 17:25:50.490  3876  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 17:25:50.490  3876  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:25:50.492  3876  4312 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 17:25:50.496  3876  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Sender)
,09-08 17:25:50.500  3876  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Receiver)
,09-08 17:25:50.501  3876  4317 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: IncomingSocketThread/Receiver)
,09-08 17:25:50.502  3876  4317 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 17:25:50.502  3876  4317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 17:25:53.479  3876  3922 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,09-08 17:25:53.481  3876  3922 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 17:25:53.482  3876  3922 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-08 17:25:53.487  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 17:25:53.488  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c2b969 added. We now have 3 listener(s)
09-08 17:25:53.489  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:25:53.490  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:25:53.490  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:25:53.490  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:25:53.490  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d1fee added. We now have 4 listener(s)
09-08 17:25:53.490  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:25:53.492  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:25:53.497  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:53.512  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:53.519  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:53.520  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:25:53.521  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:25:53.521  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:25:53.521  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:25:53.522  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:25:53.522  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:25:53.522  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:25:53.522  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 17:25:53.523  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c2b969 removed from the list
09-08 17:25:53.523  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:25:53.523  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d1fee removed from the list
09-08 17:25:53.524  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:53.524  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:25:53.525  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:53.526  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:25:53.526  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:53.536  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:25:53.537  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:53.537  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:25:53.537  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:53.537  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d1fee not in the list
09-08 17:25:53.537  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:53.538  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:53.539  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:25:53.539  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:25:53.539  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:53.540  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d1fee not in the list
09-08 17:25:53.540  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:25:53.540  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:53.540  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:53.540  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c2b969 not in the list
09-08 17:25:53.541  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 17:25:53.541  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f5b1c added. We now have 3 listener(s)
09-08 17:25:53.543  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:25:53.543  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:25:53.543  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 17:25:53.544  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:25:53.544  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c48325 added. We now have 4 listener(s)
09-08 17:25:53.544  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:25:53.544  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 17:25:53.547  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:53.554  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:53.556  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:53.557  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:25:53.557  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:25:53.557  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 17:25:53.557  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 17:25:53.557  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:25:53.558  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-08 17:25:53.559  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:53.562  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 17:25:53.562  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 17:25:53.564  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:53.568  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:25:53.569  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:25:53.569  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:25:53.575  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 17:25:53.575  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 17:25:53.576  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 17:25:53.576  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:25:53.581  4225  4235 D BtGatt.GattService: registerClient() - UUID=16c907a5-15b7-4f39-944f-7f482ccc0454
,09-08 17:25:53.582  4225  4241 D BtGatt.GattService: onClientRegistered() - UUID=16c907a5-15b7-4f39-944f-7f482ccc0454, clientIf=5
,09-08 17:25:53.583  3876  3886 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 17:25:53.584  4225  4236 D BtGatt.GattService: start scan with filters
,09-08 17:25:53.590  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 17:25:53.590  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:25:53.591  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:25:53.591  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:25:53.591  4225  4244 D BtGatt.ScanManager: handling starting scan
,09-08 17:25:53.594  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:25:53.595  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 17:25:53.595  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-08 17:25:53.595  4225  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b62d69e
09-08 17:25:53.596  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:25:53.599  3876  3922 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 17:25:53.600  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:25:53.600  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:25:53.600  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:53.600  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:25:53.600  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:25:53.600  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:25:53.600  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:25:53.600  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:25:53.600  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:25:53.600  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 17:25:53.602  3876  3922 D BluetoothAdapter: STATE_ON
09-08 17:25:53.603  4225  4235 D BtGatt.GattService: stopScan() - queue size =1
09-08 17:25:53.604  4225  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:25:53.604  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:25:53.604  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 17:25:53.605  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:25:53.605  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:25:53.605  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 17:25:53.606  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:25:53.607  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:25:53.607  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:25:53.607  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 17:25:53.608  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:25:53.609  4225  4241 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 17:25:53.609  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:53.610  4225  4244 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:25:53.612  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:25:53.612  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:25:53.612  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:25:53.621  4225  4241 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 17:25:53.621  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:53.622  4225  4244 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:25:53.622  4225  4244 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:25:53.641  4225  4241 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 17:25:53.641  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:53.652  4225  4241 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 17:25:53.652  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:53.668  4225  4241 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 17:25:53.668  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:25:53.669  4225  4244 D BtGatt.ScanManager: stopping BLe Batch
,09-08 17:25:53.684  4225  4241 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 17:25:53.685  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:25:53.686  4225  4244 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:25:53.705  4225  4241 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:25:53.706  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:54.113  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:25:54.114  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:25:54.114  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:25:56.614  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:25:56.614  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:25:56.615  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:25:56.616  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:25:56.616  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:56.616  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:25:56.617  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:25:56.617  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f5b1c removed from the list
09-08 17:25:56.617  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:56.618  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c48325 removed from the list
,09-08 17:25:56.618  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:25:56.618  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:56.620  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:56.620  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:56.624  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:25:56.624  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:25:56.624  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:56.625  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c48325 not in the list
,09-08 17:25:56.625  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:56.625  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:56.629  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:25:56.629  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:25:56.629  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:25:56.630  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c48325 not in the list
,09-08 17:25:56.630  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:25:56.630  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:56.630  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:56.631  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f5b1c not in the list
09-08 17:25:56.633  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:25:56.633  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa53ec6 added. We now have 3 listener(s)
09-08 17:25:56.635  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:25:56.635  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:25:56.635  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:25:56.636  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:25:56.636  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a03e87 added. We now have 4 listener(s)
09-08 17:25:56.636  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 17:25:56.636  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 17:25:56.641  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:56.651  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:56.656  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:56.657  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 17:25:56.657  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 17:25:56.659  3876  3922 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 17:25:56.659  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 17:25:56.660  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 17:25:56.660  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 17:25:56.661  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 17:25:56.661  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:25:56.662  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:56.665  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 17:25:56.667  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 17:25:56.668  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:25:56.668  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 17:25:56.668  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 17:25:56.668  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 17:25:56.670  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 17:25:56.672  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 17:25:56.672  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:25:56.674  3876  4318 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 17:25:56.679  3876  4318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 17:25:56.680  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:25:56.681  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 17:25:56.687  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:25:56.688  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 17:25:56.688  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:25:56.690  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 17:25:56.691  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:25:56.691  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-08 17:25:56.692  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 17:25:56.693  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 17:25:56.693  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 17:25:56.693  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:25:56.696  4225  4265 D BtGatt.GattService: registerClient() - UUID=3b19470a-8b06-486a-a43a-2a734998db50
,09-08 17:25:56.697  4225  4241 D BtGatt.GattService: onClientRegistered() - UUID=3b19470a-8b06-486a-a43a-2a734998db50, clientIf=5
,09-08 17:25:56.697  3876  3998 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-08 17:25:56.699  4225  4243 D BtGatt.AdvertiseManager: message : 0
,09-08 17:25:56.702  4225  4243 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 17:25:56.712  4225  4241 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 17:25:56.721  4225  4241 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 17:25:56.723  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 17:25:56.723  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:25:56.725  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 17:25:56.727  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 17:25:56.727  3876  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 17:25:56.727  3876  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 17:25:56.727  3876  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 17:25:56.727  3876  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 17:25:56.727  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 17:25:56.730  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 17:25:56.732  3876  3876 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 17:25:56.732  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 17:25:57.233  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 17:25:57.234  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 17:25:57.234  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:25:59.731  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:25:59.732  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 17:25:59.732  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 17:25:59.733  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 17:25:59.733  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
09-08 17:25:59.733  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 17:25:59.734  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 17:25:59.735  3876  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 17:25:59.734  3876  4318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 17:25:59.735  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:25:59.735  3876  4318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 17:25:59.735  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:25:59.735  3876  4318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 17:25:59.735  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:25:59.736  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 17:25:59.736  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:25:59.738  3876  3876 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 17:25:59.738  3876  3922 D BluetoothAdapter: STATE_ON
09-08 17:25:59.739  3876  3922 D BluetoothLeScanner: could not find callback wrapper
09-08 17:25:59.739  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 17:25:59.739  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 17:25:59.741  4225  4243 D BtGatt.AdvertiseManager: message : 1
09-08 17:25:59.743  4225  4243 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 17:25:59.753  4225  4241 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
09-08 17:25:59.754  4225  4241 D BtGatt.GattService: Client app is not null!
,09-08 17:25:59.756  4225  4265 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:25:59.757  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 17:25:59.757  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 17:25:59.757  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 17:25:59.758  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 17:25:59.758  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 17:25:59.761  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 17:25:59.761  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 17:25:59.762  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:25:59.763  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:25:59.766  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 17:25:59.766  3876  3876 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 17:25:59.766  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:59.766  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:25:59.767  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:25:59.767  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:25:59.767  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa53ec6 removed from the list
09-08 17:25:59.767  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:25:59.767  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:25:59.767  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:25:59.768  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a03e87 removed from the list
09-08 17:25:59.768  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:25:59.768  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:25:59.770  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:25:59.770  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:59.773  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:25:59.773  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 17:25:59.773  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:59.773  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a03e87 not in the list
09-08 17:25:59.774  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:59.774  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:59.775  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:25:59.776  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:25:59.776  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:25:59.776  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a03e87 not in the list
09-08 17:25:59.776  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:25:59.776  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:25:59.776  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:25:59.777  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa53ec6 not in the list
09-08 17:25:59.778  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:25:59.778  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9567520 added. We now have 3 listener(s)
09-08 17:25:59.783  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 17:25:59.783  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:25:59.783  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:25:59.784  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 17:25:59.784  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83fced9 added. We now have 4 listener(s)
09-08 17:25:59.784  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:25:59.785  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 17:25:59.791  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:25:59.800  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:25:59.802  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:25:59.802  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-08 17:25:59.802  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:25:59.802  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 17:25:59.803  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 17:25:59.803  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:25:59.803  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 17:25:59.806  3876  3922 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 17:25:59.807  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 17:25:59.807  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:59.810  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 17:25:59.812  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 17:25:59.812  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-08 17:25:59.813  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 17:25:59.817  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 17:25:59.817  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 17:25:59.817  3876  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 17:25:59.818  3876  3922 D BluetoothAdapter: STATE_ON,
,09-08 17:25:59.821  4225  4261 D BtGatt.GattService: registerClient() - UUID=f8602901-35aa-4943-a55d-ef6be751eb11
,09-08 17:25:59.821  4225  4241 D BtGatt.GattService: onClientRegistered() - UUID=f8602901-35aa-4943-a55d-ef6be751eb11, clientIf=5
09-08 17:25:59.822  3876  3998 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 17:25:59.823  4225  4262 D BtGatt.GattService: start scan with filters
,09-08 17:25:59.826  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 17:25:59.826  4225  4244 D BtGatt.ScanManager: handling starting scan
09-08 17:25:59.826  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 17:25:59.826  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 17:25:59.826  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 17:25:59.829  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 17:25:59.829  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 17:25:59.829  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 17:25:59.831  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 17:25:59.835  4225  4241 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 17:25:59.835  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:25:59.835  4225  4244 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 17:25:59.843  4225  4241 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 17:25:59.843  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:25:59.844  4225  4244 D BtGatt.ScanManager: Starting BLE batch scan
09-08 17:25:59.844  4225  4244 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 17:25:59.859  4225  4241 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 17:25:59.859  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:25:59.867  4225  4241 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 17:25:59.867  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:26:00.268  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:26:00.329  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 17:26:00.330  3876  3876 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 17:26:00.330  3876  3876 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 17:26:01.402  4225  4225 D BtGatt.ScanManager: awakened up at time 425203
,09-08 17:26:01.403  4225  4244 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:26:01.438  1727  4319 I EventLogService: Opted in for usage reporting
,09-08 17:26:01.439  1727  4319 I EventLogService: Aggregate from 1473346552727 (log), 1473346552727 (data)
,09-08 17:26:01.448  4225  4241 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 17:26:01.448  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:26:01.448  4225  4241 D BtGatt.GattService: current time is 425250293755
09-08 17:26:01.449  4225  4241 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, -128, -97, 13, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0, 81, 34, 97, 112, -14, -5, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 17:26:01.451  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 17:26:01.452  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
09-08 17:26:01.453  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 17:26:01.453  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:26:01.453  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 17:26:01.495  1727  4319 W EventLogAggregator: Unknown tag: snet_gcore
,09-08 17:26:01.495  1727  4319 W EventLogAggregator: Unknown tag: snet_launch_service
,09-08 17:26:01.552  1727  4319 I ServiceDumpSys: dumping service [account]
,09-08 17:26:01.953  4225  4225 D BtGatt.ScanManager: awakened up at time 425755
,09-08 17:26:01.956  4225  4244 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 17:26:01.978  4225  4241 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 17:26:01.978  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:26:02.844  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 17:26:02.845  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 17:26:02.845  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 17:26:02.845  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.846  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 17:26:02.846  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 17:26:02.846  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 17:26:02.846  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 17:26:02.847  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 17:26:02.849  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 17:26:02.849  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 17:26:02.853  3876  3922 D BluetoothAdapter: STATE_ON
,09-08 17:26:02.855  4225  4265 D BtGatt.GattService: stopScan() - queue size =1
,09-08 17:26:02.858  4225  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 17:26:02.862  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 17:26:02.863  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 17:26:02.863  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 17:26:02.864  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 17:26:02.864  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 17:26:02.868  4225  4225 D BtGatt.ScanManager: awakened up at time 426668
,09-08 17:26:02.869  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:26:02.869  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 17:26:02.870  3876  3922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 17:26:02.870  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 17:26:02.872  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:26:02.878  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 17:26:02.879  3876  3876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 17:26:02.879  3876  3876 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 17:26:02.880  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:26:02.880  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 17:26:02.881  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 17:26:02.881  4225  4241 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 17:26:02.881  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:26:02.882  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:26:02.882  4225  4244 D BtGatt.ScanManager: stopping BLe Batch
09-08 17:26:02.882  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9567520 removed from the list
09-08 17:26:02.882  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:26:02.883  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83fced9 removed from the list
09-08 17:26:02.884  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:26:02.884  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.886  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.886  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:26:02.888  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:26:02.888  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:26:02.889  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:26:02.889  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83fced9 not in the list
09-08 17:26:02.889  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.889  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 17:26:02.892  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:26:02.892  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 17:26:02.892  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:26:02.893  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83fced9 not in the list
,09-08 17:26:02.893  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:26:02.893  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.893  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.893  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9567520 not in the list
,09-08 17:26:02.895  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 17:26:02.895  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e8aa added. We now have 3 listener(s)
,09-08 17:26:02.900  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 17:26:02.900  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 17:26:02.900  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 17:26:02.901  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 17:26:02.901  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f70c9b added. We now have 4 listener(s)
,09-08 17:26:02.901  3876  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 17:26:02.902  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 17:26:02.902  4225  4241 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 17:26:02.902  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 17:26:02.902  4225  4244 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 17:26:02.904  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 17:26:02.912  3876  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 17:26:02.915  4225  4241 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-08 17:26:02.916  4225  4241 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 17:26:02.916  4225  4241 D BtGatt.GattService: current time is 426718023456
09-08 17:26:02.916  4225  4241 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -93, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 17:26:02.916  3876  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 17:26:02.916  4225  4241 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 17:26:02.917  3876  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 17:26:02.917  3876  3922 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 17:26:02.917  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 17:26:02.917  3876  3922 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 17:26:02.917  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:26:02.917  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.918  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 17:26:02.918  3876  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 17:26:02.918  3876  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e8aa removed from the list
09-08 17:26:02.918  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 17:26:02.918  3876  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f70c9b removed from the list
09-08 17:26:02.919  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:26:02.919  3876  3922 D io.jxcore.node.ConnectivityMonitor: stop
09-08 17:26:02.919  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.920  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.920  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.921  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:26:02.921  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:26:02.921  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:26:02.922  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f70c9b not in the list
09-08 17:26:02.922  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.922  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.922  3876  3876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 17:26:02.923  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 17:26:02.923  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 17:26:02.923  3876  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 17:26:02.923  3876  3922 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f70c9b not in the list
09-08 17:26:02.923  3876  3922 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 17:26:02.923  3876  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 17:26:02.923  3876  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 17:26:02.924  3876  3922 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e8aa not in the list
09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 17:26:02.925  3876  3922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 17:26:03.380  3876  3876 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 17:26:04.940  3876  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-08 17:26:06.938  3876  3922 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
09-08 17:26:06.938  3876  3922 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,09-08 17:26:06.945  3876  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-08 17:26:06.946  3876  4325 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
09-08 17:26:06.946  3876  4325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 17:26:06.952  3876  3922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 17:26:06.960  3876  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name),
09-08 17:26:06.961  3876  4326 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
09-08 17:26:06.961  3876  4326 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 17:26:06.969  3876  3922 I jxcore-log: Total number of executed tests:  82,
09-08 17:26:06.969  3876  3922 I jxcore-log: 
09-08 17:26:06.970  3876  3922 I jxcore-log: Number of passed tests:  82
09-08 17:26:06.970  3876  3922 I jxcore-log: 
09-08 17:26:06.971  3876  3922 I jxcore-log: Number of failed tests:  0
09-08 17:26:06.971  3876  3922 I jxcore-log: 
,09-08 17:26:06.972  3876  3922 I jxcore-log: Number of ignored tests:  0
09-08 17:26:06.972  3876  3922 I jxcore-log: 
,09-08 17:26:06.972  3876  3922 I jxcore-log: Total duration:  101392
09-08 17:26:06.972  3876  3922 I jxcore-log: 
,09-08 17:26:06.982  3876  3922 I jxcore-log: Unit Test app is loaded
09-08 17:26:06.982  3876  3922 I jxcore-log: 
,09-08 17:26:07.006  3876  3876 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 17:26:07.009  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.009  3876  3922 I jxcore-log: 
,09-08 17:26:07.015  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.015  3876  3922 I jxcore-log: 
,09-08 17:26:07.016  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.016  3876  3922 I jxcore-log: 
09-08 17:26:07.017  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.017  3876  3922 I jxcore-log: 
,09-08 17:26:07.018  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:26:07.018  3876  3922 I jxcore-log: 
,09-08 17:26:07.020  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.020  3876  3922 I jxcore-log: 
,09-08 17:26:07.022  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.022  3876  3922 I jxcore-log: 
,09-08 17:26:07.025  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.025  3876  3922 I jxcore-log: 
,09-08 17:26:07.026  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:26:07.026  3876  3922 I jxcore-log: 
09-08 17:26:07.026  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.026  3876  3922 I jxcore-log: 
,09-08 17:26:07.027  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.027  3876  3922 I jxcore-log: 
09-08 17:26:07.028  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.028  3876  3922 I jxcore-log: 
,09-08 17:26:07.029  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.029  3876  3922 I jxcore-log: 
09-08 17:26:07.030  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.030  3876  3922 I jxcore-log: 
09-08 17:26:07.031  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.031  3876  3922 I jxcore-log: 
,09-08 17:26:07.032  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.032  3876  3922 I jxcore-log: 
09-08 17:26:07.033  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.033  3876  3922 I jxcore-log: 
,09-08 17:26:07.033  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.033  3876  3922 I jxcore-log: 
09-08 17:26:07.034  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.034  3876  3922 I jxcore-log: 
,09-08 17:26:07.035  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.035  3876  3922 I jxcore-log: 
09-08 17:26:07.036  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.036  3876  3922 I jxcore-log: 
,09-08 17:26:07.037  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.037  3876  3922 I jxcore-log: 
09-08 17:26:07.037  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.037  3876  3922 I jxcore-log: 
09-08 17:26:07.038  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.038  3876  3922 I jxcore-log: 
,09-08 17:26:07.039  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.039  3876  3922 I jxcore-log: 
09-08 17:26:07.040  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.040  3876  3922 I jxcore-log: 
,09-08 17:26:07.041  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.041  3876  3922 I jxcore-log: 
09-08 17:26:07.042  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.042  3876  3922 I jxcore-log: 
09-08 17:26:07.042  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.042  3876  3922 I jxcore-log: 
,09-08 17:26:07.043  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.043  3876  3922 I jxcore-log: 
09-08 17:26:07.044  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.044  3876  3922 I jxcore-log: 
09-08 17:26:07.045  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.045  3876  3922 I jxcore-log: 
,09-08 17:26:07.045  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.045  3876  3922 I jxcore-log: 
09-08 17:26:07.046  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.046  3876  3922 I jxcore-log: 
09-08 17:26:07.047  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.047  3876  3922 I jxcore-log: 
,09-08 17:26:07.048  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.048  3876  3922 I jxcore-log: 
09-08 17:26:07.048  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.048  3876  3922 I jxcore-log: 
09-08 17:26:07.049  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.049  3876  3922 I jxcore-log: 
,09-08 17:26:07.050  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.050  3876  3922 I jxcore-log: 
09-08 17:26:07.051  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.051  3876  3922 I jxcore-log: 
09-08 17:26:07.051  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 17:26:07.051  3876  3922 I jxcore-log: 
,09-08 17:26:07.052  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.052  3876  3922 I jxcore-log: 
09-08 17:26:07.053  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 17:26:07.053  3876  3922 I jxcore-log: 
09-08 17:26:07.054  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.054  3876  3922 I jxcore-log: ,
,09-08 17:26:07.054  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.054  3876  3922 I jxcore-log: 
,09-08 17:26:07.058  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.058  3876  3922 I jxcore-log: 
09-08 17:26:07.060  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.060  3876  3922 I jxcore-log: 
09-08 17:26:07.063  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.063  3876  3922 I jxcore-log: 
,09-08 17:26:07.065  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.065  3876  3922 I jxcore-log: 
,09-08 17:26:07.067  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.067  3876  3922 I jxcore-log: 
,09-08 17:26:07.069  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 17:26:07.069  3876  3922 I jxcore-log: 
09-08 17:26:07.071  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 17:26:07.071  3876  3922 I jxcore-log: 
,09-08 17:26:07.073  3876  4324 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-08 17:26:07.073  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.073  3876  3922 I jxcore-log: 
09-08 17:26:07.076  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 17:26:07.076  3876  3922 I jxcore-log: 
,09-08 17:26:07.078  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-08 17:26:07.078  3876  3922 I jxcore-log: 
09-08 17:26:07.080  3876  3922 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 17:26:07.080  3876  3922 I jxcore-log: 
,09-08 17:26:07.085  3876  3922 I jxcore-log: My device name is: motorola-Nexus 6
09-08 17:26:07.085  3876  3922 I jxcore-log: 
,09-08 17:26:07.086  3876  3922 I jxcore-log: Running for WIFI network type
09-08 17:26:07.086  3876  3922 I jxcore-log: 
,09-08 17:26:09.587  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 17:26:09.587  3876  3922 I jxcore-log: 
,09-08 17:26:10.046  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 17:26:10.046  3876  3922 I jxcore-log: 
,09-08 17:26:10.079  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 17:26:10.079  3876  3922 I jxcore-log: 
,09-08 17:26:11.473  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 17:26:11.473  3876  3922 I jxcore-log: 
,09-08 17:26:11.720  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 17:26:11.720  3876  3922 I jxcore-log: 
,09-08 17:26:11.725  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 17:26:11.725  3876  3922 I jxcore-log: 
,09-08 17:26:11.734  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 17:26:11.734  3876  3922 I jxcore-log: 
,09-08 17:26:12.004  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 17:26:12.004  3876  3922 I jxcore-log: 
,09-08 17:26:12.022  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 17:26:12.022  3876  3922 I jxcore-log: 
,09-08 17:26:12.026  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 17:26:12.026  3876  3922 I jxcore-log: 
,09-08 17:26:12.756  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 17:26:12.756  3876  3922 I jxcore-log: 
,09-08 17:26:12.926  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 17:26:12.926  3876  3922 I jxcore-log: 
,09-08 17:26:13.266  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 17:26:13.266  3876  3922 I jxcore-log: 
,09-08 17:26:13.277  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 17:26:13.277  3876  3922 I jxcore-log: 
,09-08 17:26:13.284  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 17:26:13.284  3876  3922 I jxcore-log: 
,09-08 17:26:13.291  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 17:26:13.291  3876  3922 I jxcore-log: 
,09-08 17:26:13.333  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 17:26:13.333  3876  3922 I jxcore-log: 
,09-08 17:26:13.381  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 17:26:13.381  3876  3922 I jxcore-log: 
,09-08 17:26:13.389  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 17:26:13.389  3876  3922 I jxcore-log: 
,09-08 17:26:13.397  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 17:26:13.397  3876  3922 I jxcore-log: 
,09-08 17:26:13.417  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 17:26:13.417  3876  3922 I jxcore-log: 
,09-08 17:26:13.423  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 17:26:13.423  3876  3922 I jxcore-log: 
,09-08 17:26:13.429  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 17:26:13.429  3876  3922 I jxcore-log: 
,09-08 17:26:13.446  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 17:26:13.446  3876  3922 I jxcore-log: 
,09-08 17:26:13.473  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 17:26:13.473  3876  3922 I jxcore-log: 
,09-08 17:26:13.485  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 17:26:13.485  3876  3922 I jxcore-log: 
,09-08 17:26:13.500  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 17:26:13.500  3876  3922 I jxcore-log: 
,09-08 17:26:13.512  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 17:26:13.512  3876  3922 I jxcore-log: 
,09-08 17:26:13.528  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 17:26:13.528  3876  3922 I jxcore-log: 
,09-08 17:26:13.539  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 17:26:13.539  3876  3922 I jxcore-log: 
,09-08 17:26:13.545  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 17:26:13.545  3876  3922 I jxcore-log: 
,09-08 17:26:13.577  3876  3922 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 17:26:13.577  3876  3922 I jxcore-log: 
,09-08 17:26:13.589  3876  3922 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 17:26:13.590  3876  3922 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 17:26:13.590  3876  3922 I jxcore-log: 
,09-08 17:26:13.593  3876  3922 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 17:26:13.593  3876  3922 I jxcore-log: 
,09-08 17:26:13.593  3876  3922 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 17:26:13.593  3876  3922 I jxcore-log: 
,09-08 17:26:13.599  3876  3922 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 17:26:13.599  3876  3922 I jxcore-log: 
,09-08 17:26:13.760  3876  3922 I jxcore-log: ThaliTape :: Connected to the test server
09-08 17:26:13.760  3876  3922 I jxcore-log: 
,09-08 17:27:27.817  3046  4337 V KeepSync: Connecting to GoogleApiClient
,09-08 17:27:27.818   872  1915 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 17:27:27.907  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:27:27.910  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:27:27.954  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 17:27:27.954  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 17:27:27.954  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:27:27.955  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:27:27.981  1727  4338 V BaseAuthAsyncOperation: access token request failed
,09-08 17:27:27.983  3046  4337 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 17:27:28.048  1511  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 17:27:28.048  1511  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 17:27:28.048  1511  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:27:28.048  1511  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:27:28.074  3046  4337 E KeepSync: IOException
09-08 17:27:28.074  3046  4337 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 17:27:28.074  3046  4337 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:27:28.074  3046  4337 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 17:27:28.074  3046  4337 E KeepSync: 	... 10 more
09-08 17:27:28.074  3046  4337 W KeepSync: Sync result 2
,09-08 17:27:28.084   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 511521, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:27:59.845  3046  4340 V KeepSync: Connecting to GoogleApiClient
,09-08 17:27:59.846   872  1390 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 17:27:59.902  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:27:59.905  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:27:59.942  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 17:27:59.942  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 17:27:59.942  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:27:59.942  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:27:59.970  1727  4341 V BaseAuthAsyncOperation: access token request failed
,09-08 17:27:59.971  3046  4340 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 17:28:00.033  1511  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 17:28:00.033  1511  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 17:28:00.033  1511  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:28:00.034  1511  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:28:00.059  3046  4340 E KeepSync: IOException
09-08 17:28:00.059  3046  4340 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 17:28:00.059  3046  4340 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 17:28:00.059  3046  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 17:28:00.059  3046  4340 E KeepSync: 	... 10 more
09-08 17:28:00.059  3046  4340 W KeepSync: Sync result 2
,09-08 17:28:00.070   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 543561, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:28:30.463  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:28:30.465  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:28:30.487  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 17:28:30.487  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 17:28:30.488  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:28:30.488  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:28:30.508  3566  4344 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 17:28:30.508  3566  4344 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at blb.a(PG:3937)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at czp.a(PG:18188)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:28:30.508  3566  4344 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	... 12 more
09-08 17:28:30.508  3566  4344 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at fal.a(PG:38)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:28:30.508  3566  4344 E HttpOperation: 	... 14 more
,09-08 17:28:30.562  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 17:28:30.562  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 17:28:30.562  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:28:30.562  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:28:30.579  3566  4344 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 17:28:30.579  3566  4344 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at hec.a(PG:42)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at hee.a(PG:102)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at czr.a(PG:65)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at kka.a(PG:108)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at czp.a(PG:19176)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:28:30.579  3566  4344 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	... 15 more
09-08 17:28:30.579  3566  4344 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at fal.a(PG:38)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:28:30.579  3566  4344 E HttpOperation: 	... 17 more
,09-08 17:28:30.579  3566  4344 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 17:28:30.579  3566  4344 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token,
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at hec.a(PG:42)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at hee.a(PG:102)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at czr.a(PG:65)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at kka.a(PG:108)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	... 15 more
09-08 17:28:30.579  3566  4344 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at fal.a(PG:38)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 17:28:30.579  3566  4344 E ExperimentLoader: 	... 17 more
,09-08 17:28:30.709   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 548265, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:29:00.817  3766  4347 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 17:29:00.847  3766  4348 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 17:29:00.859  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:00.865  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:00.906  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 17:29:00.906  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 17:29:00.906  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:29:00.906  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:29:00.943  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:00.947  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:00.977  1511  2308 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 17:29:00.977  1511  2308 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 17:29:00.977  1511  2308 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:29:00.977  1511  2308 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:29:00.996  3766  4348 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 17:29:00.997  3766  4347 E BooksSync: Soft error
09-08 17:29:00.997  3766  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:29:00.997  3766  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 17:29:00.997  3766  4347 E BooksSync: Sync error
09-08 17:29:00.997  3766  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 17:29:00.997  3766  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 17:29:00.997  3766  4347 I BooksSync: Finished books sync
,09-08 17:29:01.008   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 577265, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:29:01.294  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:01.298  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 17:29:01.325  1511  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 17:29:01.325  1511  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 17:29:01.325  1511  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 17:29:01.325  1511  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:29:01.345  3566  4350 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 17:29:01.345  3566  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at blb.a(PG:3937)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at czp.a(PG:18188)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:29:01.345  3566  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	... 12 more
09-08 17:29:01.345  3566  4350 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at fal.a(PG:38)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:29:01.345  3566  4350 E HttpOperation: 	... 14 more
,09-08 17:29:01.410  1511  3834 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 17:29:01.410  1511  3834 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 17:29:01.410  1511  3834 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 17:29:01.410  1511  3834 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 17:29:01.433  3566  4350 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 17:29:01.433  3566  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jdm.a(PG:82)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jcs.o(PG:406)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jcn.a(PG:1379)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jcs.i(PG:143)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at hec.a(PG:42)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at hee.a(PG:102)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at czr.a(PG:65)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at kka.a(PG:108)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at czp.a(PG:19176)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at czp.a(PG:9081)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at czq.run(PG:1686)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:29:01.433  3566  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jdj.a(PG:4091)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jdj.a(PG:1125)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jdm.a(PG:77)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	... 15 more
09-08 17:29:01.433  3566  4350 E HttpOperation: Caused by: faj: BadAuthentication
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at fal.a(PG:38)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	at jdj.a(PG:4089)
09-08 17:29:01.433  3566  4350 E HttpOperation: 	... 17 more
09-08 17:29:01.434  3566  4350 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 17:29:01.434  3566  4350 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at hec.a(PG:42)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at hee.a(PG:102)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at czr.a(PG:65)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at kka.a(PG:108)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	... 15 more
09-08 17:29:01.434  3566  4350 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at fal.a(PG:38)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 17:29:01.434  3566  4350 E ExperimentLoader: 	... 17 more
,09-08 17:29:01.649   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 604743, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 17:33:39.996   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:33:50.036   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=893837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:34:04.569   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=908370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:34:15.089   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=918891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:34:29.689   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=933491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:34:40.182   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=943983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:34:54.756   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=958557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:35:05.236   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:35:19.823   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=983624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:35:30.316   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=994117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:35:44.889   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1008690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:35:55.369   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1019170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:36:09.955   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1033757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:36:20.463   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1044264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:36:35.022   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:36:45.543   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1069344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:37:00.089   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1083891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:37:10.622   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1094423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:37:25.156   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:37:35.689   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1119490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:37:50.222   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1134024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:38:00.756   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1144557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:38:15.289   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1159090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:38:25.809   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1169610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:38:41.606   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185407, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:38:50.876   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:39:06.702   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:39:14.452   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 17:39:15.929   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1219730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:39:31.769   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:39:41.009   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1244810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:39:56.836   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:40:06.102   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1269904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:40:21.902   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:40:31.156   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1294957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:40:47.022   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:40:56.262   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:41:12.089   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1335890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:41:21.316   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:41:37.156   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1360957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:41:46.382   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:42:02.169   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1385970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:42:11.449   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:42:27.236   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1411037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:42:36.502   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:42:52.302   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1436103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:43:01.556   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:43:17.369   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1461170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:43:26.609   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:43:42.936   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486737, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:43:51.662   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1495463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:44:07.929   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:44:16.729   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1520530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:44:32.996   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1536797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:44:41.795   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1545597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:44:58.116   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1561917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:45:06.929   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1570730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:45:23.182   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1586984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:45:31.982   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1595784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:45:48.249   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1612050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:45:57.062   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1620863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:46:13.315   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1637117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:46:22.116   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1645917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:46:38.382   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1662183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:46:47.182   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1670984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:47:03.449   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1687250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:47:12.249   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1696050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 17:47:28.516   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1712317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 17:47:37.303   872  4282 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1721104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-08 17:47:39.199  4406  4406 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 17:47:39.203  4406  4406 D AndroidRuntime: CheckJNI is OFF
09-08 17:47:39.239  4406  4406 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 17:47:39.279  4406  4406 I Radio-JNI: register_android_hardware_Radio DONE
09-08 17:47:39.301  4406  4406 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 17:47:39.313   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 17:47:39.314   872   885 I ActivityManager: Killing 3876:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-08 17:47:39.396   872  1300 W InputDispatcher: channel 'd771f9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-08 17:47:39.396   872  1300 E InputDispatcher: channel 'd771f9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-08 17:47:39.399   872  1915 D GraphicsStats: Buffer count: 2
09-08 17:47:39.400   872  1310 D WifiService: Client connection lost with reason: 4
09-08 17:47:39.400   872  2018 I WindowState: WIN DEATH: Window{d771f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 17:47:39.400   872  2018 W InputDispatcher: Attempted to unregister already unregistered input channel 'd771f9 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-08 17:47:39.455   872   895 W PackageSettings: Skipping PackageSetting{1cd00b3 com.example.hello/10273} due to missing metadata
09-08 17:47:39.485   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-08 17:47:39.485   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-08 17:47:39.487   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-08 17:47:39.487   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 17:47:39.487   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.487   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.487   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.487   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 17:47:39.487   872   895 I art     : Starting a blocking GC Explicit
09-08 17:47:39.494   872   885 I ActivityManager:   Force finishing activity ActivityRecord{47c0bea u0 com.test.thalitest/.MainActivity t4}
09-08 17:47:39.498   872  1919 W ActivityManager: Spurious death for ProcessRecord{1d05eec 0:com.test.thalitest/u0a0}, curProc for 3876: null
09-08 17:47:39.558   872   895 I art     : Explicit concurrent mark sweep GC freed 37768(3MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/43MB, paused 1.650ms total 69.423ms
09-08 17:47:39.578   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 17:47:39.582  4406  4406 I art     : System.exit called, status: 0
09-08 17:47:39.582  4406  4406 I AndroidRuntime: VM exiting with result code 0.
09-08 17:47:39.587   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 17:47:39.609   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 17:47:39.613  4225  4225 D BluetoothMapAppObserver: onReceive
09-08 17:47:39.613  4225  4225 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 17:47:39.614  1883  1883 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 17:47:39.617   872  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 17:47:39.618  3653  3653 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 17:47:39.623  1916  2238 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 17:47:39.632  1883  4420 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 17:47:39.635   872   883 I ActivityManager: Start proc 4422:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 17:47:39.655  1883  4420 I Decoder : createOrResetDecoder
09-08 17:47:39.680  4422  4422 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 17:47:39.683  1997  1997 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 17:47:39.686   872  1307 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-08 17:47:39.695  1511  1511 I ConfigService: onCreate
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 17:47:39.705  1511  4435 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 17:47:39.705  1511  4435 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-08 17:47:39.709  1511  4435 W SQLiteOpenHelper: Opened config.db in read-only mode
09-08 17:47:39.716   872  1394 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3876 uid 10000
09-08 17:47:39.718  1883  1883 I Keyboard.Facilitator: onFinishInput()
09-08 17:47:39.721   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 17:47:39.723  1883  4420 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 17:47:39.750  1883  4420 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 17:47:39.751  2021  2110 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 17:47:39.752   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 17:47:39.752  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 17:47:39.752  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 17:47:39.753   872   884 E PackageManager: Failed to write settings, restoring backup
09-08 17:47:39.753   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 17:47:39.753   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 17:47:39.753   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 17:47:39.753   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 17:47:39.753   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 17:47:39.753   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.753   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.753   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.755  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 17:47:39.755  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 17:47:39.757  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 17:47:39.757  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 17:47:39.757   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-08 17:47:39.757   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 17:47:39.757   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:47:39.757   872   885 E DropBoxManagerService: 	... 13 more
09-08 17:47:39.759  1883  4420 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 17:47:39.759  1883  4420 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 17:47:39.759  1883  4420 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 17:47:39.759  1883  4420 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 17:47:39.759  1883  4420 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 17:47:39.760  1883  4420 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 17:47:39.763   872  1394 I ActivityManager: Start proc 4440:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-08 17:47:39.764  2021  2110 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 17:47:39.764  2021  2110 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2021
09-08 17:47:39.764  2021  2110 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.764  2021  2110 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.766   872  2015 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 17:47:39.766   872  4446 E DropBoxManagerService: Can't write: system_app_crash
09-08 17:47:39.766   872  4446 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:47:39.766   872  4446 E DropBoxManagerService: 	... 5 more
09-08 17:47:39.767  4422  4422 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 17:47:39.770  2021  2110 I Process : Sending signal. PID: 2021 SIG: 9
09-08 17:47:39.796   872  1919 I ActivityManager: Start proc 4455:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 17:47:39.799  4422  4454 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 17:47:39.822  4455  4455 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 17:47:39.847  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 17:47:39.850  1511  1511 D AndroidRuntime: Shutting down VM
09-08 17:47:39.850  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
09-08 17:47:39.850  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
09-08 17:47:39.850  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 17:47:39.850  1511  1511 E AndroidRuntime: 	... 8 more
09-08 17:47:39.853   872  4472 E DropBoxManagerService: Can't write: system_app_crash
09-08 17:47:39.853   872  4472 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:47:39.853   872  4472 E DropBoxManagerService: 	... 5 more
09-08 17:47:39.854   872  1919 D GraphicsStats: Buffer count: 1
09-08 17:47:39.854   872   883 I WindowState: WIN DEATH: Window{d9d185e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 17:47:39.863  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
09-08 17:47:39.865   872  1919 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2021) has died
09-08 17:47:39.866   872  1919 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 17:47:39.867   872  1919 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 17:47:39.888   872   885 I ActivityManager: Start proc 4473:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.901  4422  4437 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.902  4422  4437 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.905   872  2015 I ActivityManager: Killing 3713:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-08 17:47:39.939  4422  4437 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.943  4422  4454 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 17:47:39.944  4422  4454 E AndroidRuntime: Process: android.process.acore, PID: 4422
09-08 17:47:39.944  4422  4454 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:39.944  4422  4454 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 17:47:39.945  4422  4437 I Process : Sending signal. PID: 4422 SIG: 9
09-08 17:47:39.970   872  1310 D WifiService: Client connection lost with reason: 4
09-08 17:47:39.982   872  2016 I ActivityManager: Process android.process.acore (pid 4422) has died
09-08 17:47:39.983   872  2016 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-08 17:47:39.985   872  1393 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
09-08 17:47:39.986   872  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-08 17:47:39.986   872  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-08 17:47:39.986   872  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
09-08 17:47:39.990   872  1919 W ActivityManager: Can't find mystery application for Crash from pid=4422 uid=10005: android.os.BinderProxy@e4d9c0c
09-08 17:47:39.993   872  1919 E DropBoxManagerService: Can't write: system_server_crash
09-08 17:47:39.993   872  1919 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop78.tmp: open failed: EROFS (Read-only file system)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:47:39.993   872  1919 E DropBoxManagerService: 	... 11 more
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:47:40.010  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:47:40.011  4473  4473 D AndroidRuntime: Shutting down VM
09-08 17:47:40.024  1727  1727 W RocketImpressions: ClearcutLogger connection suspended: 1
09-08 17:47:40.044   872  1393 I ActivityManager: Start proc 4486:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-08 17:47:40.046  4473  4473 E AndroidRuntime: FATAL EXCEPTION: main
09-08 17:47:40.046  4473  4473 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4473
09-08 17:47:40.046  4473  4473 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 17:47:40.046  4473  4473 E AndroidRuntime: 	... 10 more
09-08 17:47:40.053   872  2016 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 17:47:40.055  4473  4473 I Process : Sending signal. PID: 4473 SIG: 9
09-08 17:47:40.059   872  4492 E DropBoxManagerService: Can't write: system_app_crash
09-08 17:47:40.059   872  4492 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 17:47:40.059   872  4492 E DropBoxManagerService: 	... 5 more
09-08 17:47:40.079   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
