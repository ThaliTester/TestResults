#### Test 6810213040493cb_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-28 12:32:47.858  3552  3799 I BooksSync: Starting books sync for 61035162, extras: ade
,07-28 12:32:47.891  3552  3800 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
07-28 12:32:47.915  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 12:32:47.918  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 12:32:47.954  1506  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-28 12:32:47.954  1506  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-28 12:32:47.954  1506  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:32:47.954  1506  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-28 12:32:47.983  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 12:32:47.985  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 12:32:48.005  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-28 12:32:48.005  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-28 12:32:48.005  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:32:48.005  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-28 12:32:48.017  3552  3800 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-28 12:32:48.018  3552  3799 E BooksSync: Soft error
07-28 12:32:48.018  3552  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-28 12:32:48.018  3552  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-28 12:32:48.018  3552  3799 E BooksSync: Sync error
07-28 12:32:48.018  3552  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-28 12:32:48.018  3552  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-28 12:32:48.019  3552  3799 I BooksSync: Finished books sync
07-28 12:32:48.024   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284948, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
07-28 12:32:48.594  3801  3801 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-28 12:32:48.598  3801  3801 D AndroidRuntime: CheckJNI is OFF
07-28 12:32:48.633  3801  3801 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-28 12:32:48.676  3801  3801 I Radio-JNI: register_android_hardware_Radio DONE
07-28 12:32:48.695  3801  3801 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-28 12:32:48.710   874   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:32:48.775   874   884 I ActivityManager: Start proc 3810:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-28 12:32:48.784  3801  3801 D AndroidRuntime: Shutting down VM
07-28 12:32:48.868  3810  3810 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-28 12:32:48.897  3810  3810 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-28 12:32:48.905  3810  3810 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6031-6033)
07-28 12:32:48.905  3810  3810 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:32:48.923  3810  3810 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dee0b9e}
07-28 12:32:48.923  3810  3810 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:32:48.923  3810  3810 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:32:48.931  3810  3810 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-28 12:32:48.932  3810  3810 E SysUtils: ApplicationContext is null in ApplicationStatus
07-28 12:32:48.956  3810  3810 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-28 12:32:48.967  3810  3810 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:32:48.967  3810  3810 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:32:48.968  3810  3810 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 12:32:48.968  3810  3810 I Adreno  : Build Date                       : 10/20/15
07-28 12:32:48.968  3810  3810 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 12:32:48.968  3810  3810 I Adreno  : Local Branch                     : M14
07-28 12:32:48.968  3810  3810 I Adreno  : Remote Branch                    : 
07-28 12:32:48.968  3810  3810 I Adreno  : Remote Branch                    : 
07-28 12:32:48.968  3810  3810 I Adreno  : Reconstruct Branch               : 
,07-28 12:32:49.051   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d569dc0:true
,07-28 12:32:49.086  3810  3810 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-28 12:32:49.103  3810  3810 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-28 12:32:49.202  3810  3851 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-28 12:32:49.219  3810  3835 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-28 12:32:49.263  3810  3851 I OpenGLRenderer: Initialized EGL, version 1.4
,07-28 12:32:49.320   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +501ms (total +568ms)
,07-28 12:32:49.336  1665  1665 I Keyboard.Facilitator: onFinishInput()
,07-28 12:32:49.422  3810  3810 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3810
,07-28 12:32:49.558  3810  3810 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 12:32:49.710  3810  3855 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1697253072
,07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-28 12:32:49.715  3810  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a08150d added. We now have 1 listener(s)
,07-28 12:32:49.719  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-28 12:32:49.720  3810  3855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:32:49.720  3810  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:32:49.721  3810  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-28 12:32:49.724  3810  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5899610 added. We now have 1 listener(s),
07-28 12:32:49.724  3810  3855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:32:49.731   874  1316 D WifiService: New client listening to asynchronous messages
,07-28 12:32:49.740  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:32:49.741  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,07-28 12:32:49.741  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-28 12:32:49.742  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-28 12:32:49.743  3810  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,07-28 12:32:49.746  3810  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:32:49.746  3810  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-28 12:32:49.751  3810  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:32:49.751  3810  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:32:49.751  3810  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-28 12:32:49.751  3810  3855 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:32:49.752  3810  3855 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:32:49.754  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:32:49.755  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:32:49.778  3810  3810 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:32:50.505  3810  3861 W jxcore-log: Initializing JXcore engine
,07-28 12:32:50.505  3810  3861 W jxcore-log: JXcore engine is ready
,07-28 12:32:50.541  3861  3861 W Thread-353: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-28 12:32:50.541  3861  3861 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11496]" dev="sockfs" ino=11496 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-28 12:32:50.541  3861  3861 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-28 12:32:50.541  3861  3861 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24960]" dev="sockfs" ino=24960 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,07-28 12:32:50.558  3810  3861 W jxcore-log: Starting JXcore engine
,07-28 12:32:50.642  3810  3861 W jxcore-log: Platform android
07-28 12:32:50.642  3810  3861 W jxcore-log: 
,07-28 12:32:50.642  3810  3861 W jxcore-log: Process ARCH arm
07-28 12:32:50.642  3810  3861 W jxcore-log: 
,07-28 12:32:50.813  3810  3861 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:32:50.813  3810  3861 I jxcore-log: 
,07-28 12:32:50.814  3810  3861 W jxcore-log: JXcore engine is started
,07-28 12:32:50.826  3810  3855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:32:50.829  3810  3810 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:33:01.096  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:33:01.096  3810  3861 I jxcore-log: 
,07-28 12:33:01.099  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:33:01.099  3810  3861 I jxcore-log: 
,07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.112  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:01.117  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:33:01.119  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:33:01.119  3810  3861 I jxcore-log: 
,07-28 12:33:01.121  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:33:01.121  3810  3861 I jxcore-log: 
,07-28 12:33:01.472  3810  3861 D ExecuteNativeTests: Running unit tests
,07-28 12:33:01.530  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:33:01.530  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f added. We now have 2 listener(s)
,07-28 12:33:01.531  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:01.531  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:33:01.531  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:01.531  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:33:01.531  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c added. We now have 2 listener(s)
07-28 12:33:01.531  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:01.532  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:33:01.536  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.543  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:01.547  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:33:01.547  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:33:01.555  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.558  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:33:01.558  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:33:01.559  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 12:33:01.561  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.565  3810  3861 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 12:33:01.567  3810  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-28 12:33:01.567  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:33:01.568  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:33:01.568  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:33:01.570  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:01.572  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.572  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.573  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.573  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.573  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:01.573  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:01.573  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f removed from the list
,07-28 12:33:01.573  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.573  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c removed from the list
07-28 12:33:01.573  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.573  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.574  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.574  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.578  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:01.578  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.578  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.578  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.580  3810  3861 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:33:01.580  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:01.580  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:33:01.580  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.580  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:01.580  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.580  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.581  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.581  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.581  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.581  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:01.581  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.581  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.581  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.581  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.582  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.582  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:33:01.582  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.582  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:33:01.587  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:33:01.588  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:33:01.588  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:01.588  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.588  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.588  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.589  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.589  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.589  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.589  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.589  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.589  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:01.589  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.589  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.589  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.589  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.590  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.590  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.590  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.590  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.591  3810  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:33:01.592  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.601  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:01.602  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:33:01.603  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:01.603  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:01.603  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:33:01.603  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:33:01.603  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.603  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:33:01.607  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.612  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:33:01.612  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.612  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:33:01.625  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:33:01.627  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:33:01.627  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:33:01.631  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-28 12:33:01.633  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-28 12:33:01.634  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:33:01.634  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:01.634  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:33:01.635  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:01.639  2622  2754 D BtGatt.GattService: registerClient() - UUID=6832074d-1573-41f0-8d0c-9598730075bb
,07-28 12:33:01.640  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=6832074d-1573-41f0-8d0c-9598730075bb, clientIf=5
,07-28 12:33:01.641  3810  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 12:33:01.642  2622  2634 D BtGatt.GattService: start scan with filters
,07-28 12:33:01.646  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:33:01.646  2622  2652 D BtGatt.ScanManager: handling starting scan
07-28 12:33:01.646  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:33:01.647  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-28 12:33:01.647  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:33:01.649  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:01.649  2622  2652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38,
07-28 12:33:01.650  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:01.650  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:33:01.652  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:33:01.656  3810  3861 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:33:01.657  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:33:01.657  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.658  2622  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,07-28 12:33:01.664  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:01.664  3810  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-28 12:33:01.664  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.664  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-28 12:33:01.665  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.665  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 12:33:01.665  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:33:01.665  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:01.665  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:01.666  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-28 12:33:01.667  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 12:33:01.668  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 12:33:01.670  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:01.672  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-28 12:33:01.672  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.672  2622  2652 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:01.672  2622  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:33:01.673  2622  2754 D BtGatt.GattService: stopScan() - queue size =1
,07-28 12:33:01.674  2622  2754 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:01.675  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:33:01.675  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:33:01.675  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:33:01.675  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 12:33:01.675  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 12:33:01.676  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.676  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 12:33:01.676  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:01.677  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:33:01.677  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:01.679  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.679  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 12:33:01.679  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.679  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.679  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.679  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:01.679  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.679  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.679  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.679  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.679  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.680  3810  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:33:01.681  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.685  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:01.688  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:33:01.688  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:33:01.690  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.691  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:01.691  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:33:01.691  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:33:01.691  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.691  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:33:01.691  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:33:01.692  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.692  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.693  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 12:33:01.694  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:33:01.697  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:33:01.697  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:33:01.697  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:33:01.699  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:01.699  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.703  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:33:01.703  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:01.703  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:33:01.704  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:01.706  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:33:01.707  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.707  2622  2652 D BtGatt.ScanManager: stopping BLe Batch
,07-28 12:33:01.708  2622  2754 D BtGatt.GattService: registerClient() - UUID=88212c45-b2c9-4d4f-92f5-3d07198238fb
07-28 12:33:01.708  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=88212c45-b2c9-4d4f-92f5-3d07198238fb, clientIf=5
,07-28 12:33:01.709  3810  3821 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:33:01.709  2622  2635 D BtGatt.GattService: start scan with filters
07-28 12:33:01.712  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 12:33:01.712  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 12:33:01.712  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:33:01.712  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:33:01.714  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:01.714  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:33:01.714  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:01.715  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 12:33:01.716  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:33:01.716  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.716  2622  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:33:01.717  3810  3861 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:33:01.719  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:01.720  3810  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-28 12:33:01.720  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.720  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,07-28 12:33:01.720  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.720  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:33:01.720  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 12:33:01.720  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:01.720  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:01.720  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:01.720  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:33:01.720  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:33:01.721  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:01.722  2622  2634 D BtGatt.GattService: stopScan() - queue size =0
07-28 12:33:01.722  2622  2635 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:01.723  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:33:01.723  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:33:01.723  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-28 12:33:01.723  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:33:01.723  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:33:01.724  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:33:01.724  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.724  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.724  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 12:33:01.724  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:01.724  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:33:01.725  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:01.726  2622  2652 D BtGatt.ScanManager: handling starting scan
,07-28 12:33:01.726  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.726  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 12:33:01.726  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:33:01.726  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.726  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.726  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:01.727  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.727  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.727  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.727  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:01.727  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.727  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.727  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.728  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:01.728  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:33:01.728  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.728  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list,
07-28 12:33:01.729  3810  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 12:33:01.730  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:33:01.730  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.731  2622  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:33:01.731  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.737  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:01.737  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:33:01.737  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.737  2622  2652 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:01.737  2622  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:33:01.738  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.738  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:33:01.739  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:01.739  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:33:01.739  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:33:01.740  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.740  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:33:01.742  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.743  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:33:01.744  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:33:01.744  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.746  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:33:01.746  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.748  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:33:01.748  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:33:01.748  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:33:01.750  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:01.750  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.753  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:33:01.753  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:01.753  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 12:33:01.755  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:01.755  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:33:01.755  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.756  2622  2652 D BtGatt.ScanManager: stopping BLe Batch
,07-28 12:33:01.758  2622  2635 D BtGatt.GattService: registerClient() - UUID=4144ed72-5d77-4d39-9f9c-5b297f355a21
,07-28 12:33:01.759  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=4144ed72-5d77-4d39-9f9c-5b297f355a21, clientIf=5
07-28 12:33:01.759  3810  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 12:33:01.759  2622  2754 D BtGatt.GattService: start scan with filters
,07-28 12:33:01.761  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:33:01.761  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:01.761  2622  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:33:01.763  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:33:01.764  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:33:01.764  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:33:01.764  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:33:01.766  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-28 12:33:01.766  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.768  2622  2652 D BtGatt.ScanManager: handling starting scan
,07-28 12:33:01.768  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:33:01.769  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:01.769  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:33:01.771  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:33:01.773  3810  3861 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:33:01.773  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.773  3810  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-28 12:33:01.774  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.774  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-28 12:33:01.774  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.774  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 12:33:01.774  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 12:33:01.774  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:01.774  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:01.774  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:01.774  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:33:01.774  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 12:33:01.775  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:01.776  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:33:01.776  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.776  2622  2634 D BtGatt.GattService: stopScan() - queue size =1
,07-28 12:33:01.777  2622  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 12:33:01.777  2622  2754 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:01.778  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:33:01.778  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:33:01.778  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:33:01.778  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 12:33:01.778  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 12:33:01.779  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.779  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 12:33:01.779  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:01.779  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:33:01.780  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:01.781  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.782  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.782  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:33:01.782  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.782  3810  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-28 12:33:01.782  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.782  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.782  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:01.782  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.782  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:01.782  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.782  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.782  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.782  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.783  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.783  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.784  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.784  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:33:01.784  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.785  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.785  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:33:01.785  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.785  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.786  3810  3861 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:33:01.786  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.786  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:33:01.786  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.786  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.787  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.787  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.787  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.787  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.787  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.787  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.787  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.787  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.787  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.787  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.788  2622  2652 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:01.788  2622  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:33:01.788  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:01.789  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.789  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.789  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.790  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:33:01.790  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.790  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.790  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.790  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:01.790  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.790  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.790  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.790  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.791  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.791  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.791  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.791  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.791  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.791  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.792  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:01.792  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.792  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.792  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.793  3810  3861 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:33:01.793  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.793  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.793  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:33:01.794  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.794  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.794  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.794  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.794  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.794  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.794  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:01.794  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.794  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.794  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.794  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.796  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.796  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
07-28 12:33:01.796  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.796  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.797  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-28 12:33:01.797  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.797  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.797  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:33:01.797  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.797  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-28 12:33:01.797  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.797  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.797  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.798  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.798  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.798  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.798  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.798  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.798  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.799  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:01.799  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.799  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.799  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.800  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:33:01.803  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-28 12:33:01.803  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.805  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:33:01.805  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:33:01.805  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:33:01.805  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:33:01.805  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:33:01.806  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
07-28 12:33:01.806  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.806  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:33:01.806  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.806  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.806  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.806  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.806  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.806  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.806  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.806  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.806  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.806  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:01.806  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:01.808  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.808  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.808  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:01.808  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
,07-28 12:33:01.809  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 12:33:01.810  3810  3861 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,07-28 12:33:01.810  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:33:01.816  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:01.816  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.816  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:33:01.817  3810  3861 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:33:01.817  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:33:01.818  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:33:01.819  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:33:01.819  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:33:01.819  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:33:01.819  3810  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:33:01.819  3810  3861 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:33:01.820  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:33:01.820  3810  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:33:01.820  3810  3861 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:33:01.820  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:33:01.820  3810  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:33:01.820  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:33:01.823  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:33:01.823  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:33:01.823  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:33:01.823  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.824  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:33:01.824  2622  2652 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:33:01.824  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:33:01.824  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:33:01.824  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:33:01.824  3810  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:33:01.825  3810  3861 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:33:01.825  3810  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 417)
07-28 12:33:01.825  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.825  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.825  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.826  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.826  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.826  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.826  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:33:01.827  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.827  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.827  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.827  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.827  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.827  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.827  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.827  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.827  3810  3862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:33:01.828  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.828  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.828  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.828  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.828  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:33:01.828  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.829  2622  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 12:33:01.829  3810  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 417
07-28 12:33:01.829  3810  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 417)
07-28 12:33:01.829  3810  3861 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:33:01.829  3810  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 417)
07-28 12:33:01.829  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.830  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.830  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.830  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.830  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.830  3810  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 417)
07-28 12:33:01.830  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.830  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.830  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.830  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.830  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.830  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.830  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.830  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.831  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.831  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.832  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.832  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.832  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.833  3810  3861 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:33:01.833  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.833  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.833  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.833  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.833  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.833  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.834  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.834  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.834  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.834  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.834  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.834  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.834  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.834  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.835  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.835  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.835  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.835  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.835  3810  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:33:01.836  3810  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:33:01.836  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:33:01.836  3810  3861 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:33:01.836  3810  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:33:01.836  3810  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:33:01.836  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:33:01.836  3810  3861 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:33:01.836  3810  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:33:01.836  3810  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:33:01.836  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:33:01.836  3810  3861 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:33:01.836  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.836  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.837  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.837  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.837  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.837  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.837  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.837  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.837  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.837  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.837  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.837  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.837  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.837  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.837  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:33:01.838  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:01.838  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.838  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.838  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.839  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.839  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.839  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.839  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.839  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.839  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.839  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.839  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.839  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.840  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.840  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.840  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.840  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.840  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.840  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.840  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.840  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.840  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.840  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.841  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.841  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.841  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.841  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.841  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.841  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.841  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.841  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.841  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.841  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.841  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.843  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.843  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.843  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.843  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.844  3810  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:33:01.845  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.846  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:33:01.846  3810  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:33:01.847  3810  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:33:01.847  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:33:01.847  3810  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:33:01.847  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:33:01.847  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.848  3810  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:33:01.848  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:33:01.848  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:33:01.848  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:33:01.848  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.848  3810  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:33:01.848  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.848  3810  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:33:01.848  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.849  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:01.849  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:01.849  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:01.849  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.849  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.850  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.850  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.850  3810  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 12:33:01.850  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:01.850  3810  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:33:01.850  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:01.850  3810  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:33:01.850  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.850  3810  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:33:01.851  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.851  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.851  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.851  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.851  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.851  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.851  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.851  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.851  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.851  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.851  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.851  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.851  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.852  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.853  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.853  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.853  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.853  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.854  3810  3861 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:33:01.854  3810  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:33:01.854  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:33:01.856  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:33:01.856  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.856  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.856  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.856  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.856  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.856  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.856  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.857  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.857  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.857  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.857  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.857  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.857  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.857  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.858  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.858  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.859  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.859  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.862  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.862  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.862  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.862  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.863  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.863  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.863  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
,07-28 12:33:01.863  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.863  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.863  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.863  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.863  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.863  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.863  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.864  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.864  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.864  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.864  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.865  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:01.865  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:01.865  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:01.866  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:01.866  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.866  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.866  3810  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af8b82f not in the list
07-28 12:33:01.866  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.866  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.866  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:01.866  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.866  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.866  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:01.866  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:01.867  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:01.867  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:01.868  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:01.868  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75eee3c not in the list
07-28 12:33:01.869  3810  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:33:01.869  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:33:01.869  3810  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:33:01.869  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:33:01.869  3810  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:33:01.869  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:33:01.871  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:33:01.871  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:33:01.872  3810  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:33:01.872  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:33:01.872  3810  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:33:01.872  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:33:01.873  3810  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:33:01.873  3810  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:33:01.873  3810  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:33:01.873  3810  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:33:01.874  3810  3861 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:33:01.874  3810  3861 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:33:01.874  3810  3861 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:33:01.875  3810  3861 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:33:01.875  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:01.875  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b9e7ebe added. We now have 2 listener(s)
07-28 12:33:01.875  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:01.878  3810  3861 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:33:01.878   874  1761 D WifiService: setWifiEnabled: true pid=3810, uid=10000
07-28 12:33:01.878   874  1761 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:33:01.879  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:01.879  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20e0b1f added. We now have 3 listener(s)
07-28 12:33:01.879  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:01.884  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:01.885  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@585e6c added. We now have 4 listener(s)
07-28 12:33:01.885  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:01.886  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:01.886  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ed4c35 added. We now have 5 listener(s)
07-28 12:33:01.886  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:01.889   874  1716 D WifiService: setWifiEnabled: false pid=3810, uid=10000
07-28 12:33:01.889   874  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:33:01.897  2622  2642 D BluetoothAdapterState: Current state: ON, message: 23
07-28 12:33:01.897  2622  2642 D BluetoothAdapterProperties: Setting state to 13
,07-28 12:33:01.897  2622  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:33:01.897  2622  2642 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:33:01.898  2622  2642 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:33:01.900  2622  2622 D BluetoothMapService: onReceive
07-28 12:33:01.900  2622  2622 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:33:01.900  2622  2622 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:33:01.900  2622  2622 D BluetoothMapService: MAP Service closeService in
07-28 12:33:01.900  2622  2622 D BluetoothMapMasInstance0: MAP Service shutdown
07-28 12:33:01.900  2622  2622 D ObexServerSockets0: shutdown(block = true)
07-28 12:33:01.901  2622  2622 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:33:01.901  2622  2622 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:33:01.901  2622  2780 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 12:33:01.901  2622  2747 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-28 12:33:01.902  2622  2781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 12:33:01.902  2622  2622 I BtOppRfcommListener: stopping Accept Thread
07-28 12:33:01.902  2622  3384 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:33:01.903  2622  3384 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:33:01.908  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.908  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:33:01.909  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.910  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.911  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:33:01.912   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:33:01.913   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-28 12:33:01.913   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:01.913   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:33:01.919   874  1315 E native  : do suspend true
,07-28 12:33:01.925   874   887 I ActivityManager: Start proc 3867:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-28 12:33:01.926  2622  2647 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:33:01.926  2622  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-28 12:33:01.926  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:01.928  2622  2622 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:33:01.930  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:01.930   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:01.930  1753  1764 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:01.930  2622  2622 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:01.930  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.930  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:01.930  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.930   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:01.931   874  2102 D DhcpClient: Clearing IP address
07-28 12:33:01.931   372   872 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:33:01.931  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:01.931  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:33:01.932  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:01.932  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:01.933  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:01.933  1373  1386 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:01.933   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:01.934  1373  1373 D HeadsetProfile: Bluetooth service disconnected
07-28 12:33:01.934   372   872 D CommandListener: Setting iface cfg
07-28 12:33:01.931  2622  2622 D A2dpService: Received stop request...Stopping profile...
,07-28 12:33:01.935  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.935  2622  2761 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:33:01.936   874   874 D BluetoothA2dp: Proxy object disconnected
,07-28 12:33:01.937  1373  1373 D BluetoothA2dp: Proxy object disconnected
,07-28 12:33:01.937  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.938   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:33:01.938   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-28 12:33:01.939   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
07-28 12:33:01.940   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:01.940   874  1315 E native  : do suspend true
,07-28 12:33:01.941  2622  2622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:33:01.941  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-28 12:33:01.941  2622  2622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:33:01.941  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:01.941  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:01.941  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 12:33:01.941  2622  2647 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-28 12:33:01.942  2622  2622 D HidService: Received stop request...Stopping profile...
07-28 12:33:01.942  2622  2622 D HidService: Stopping Bluetooth HidService
07-28 12:33:01.944   396   396 E Parcel  : Reading a NULL string not supported here.
07-28 12:33:01.944   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,07-28 12:33:01.946  2622  2622 D HealthService: Received stop request...Stopping profile...
,07-28 12:33:01.947  2622  2622 D PanService: Received stop request...Stopping profile...
,07-28 12:33:01.949  2622  2622 D BluetoothMapService: Received stop request...Stopping profile...
,07-28 12:33:01.949  2622  2622 D BluetoothMapService: stop()
,07-28 12:33:01.949  2622  2622 D BluetoothMapAppObserver: deinitObservers()
07-28 12:33:01.950  2622  2622 D BluetoothMapAppObserver: removeReceiver()
07-28 12:33:01.951  2622  2622 V BluetoothAdapterState: isTurningOff()=true
,07-28 12:33:01.951  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.952  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:01.952  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.953  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,07-28 12:33:01.953  1373  1373 D HidProfile: Bluetooth service disconnected
07-28 12:33:01.953  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:33:01.953  1373  1373 D PanProfile: Bluetooth service disconnected
07-28 12:33:01.954  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-28 12:33:01.954  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:01.954  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:01.954  2622  2739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:33:01.954  2622  2739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:33:01.954  2622  2739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:33:01.954  2622  2739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:33:01.955  1373  1373 D BluetoothMap: Proxy object disconnected
07-28 12:33:01.955  1373  1373 D MapProfile: Bluetooth service disconnected
,07-28 12:33:01.943  1506  2300 V NativeCrypto: Read error: ssl=0x9b288e00: I/O error during system call, Connection timed out
07-28 12:33:01.956  2622  2622 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:01.956  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.956  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:01.957  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.957  2622  2622 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:33:01.957  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:33:01.957  2622  2622 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:33:01.958  2622  2622 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:01.958  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.958  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:01.958  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.957  1506  2300 V NativeCrypto: SSL shutdown failed: ssl=0x9b288e00: I/O error during system call, Broken pipe
07-28 12:33:01.958  2622  2622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:33:01.958  2622  2647 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 12:33:01.962  2622  2622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:33:01.962  2622  2622 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:01.962  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.962  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:01.962  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.963  2622  2622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:33:01.963  2622  2622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:33:01.963   874  2107 D DhcpClient: Receive thread stopped
07-28 12:33:01.964  2622  2622 D BluetoothMapService: MAP Service closeService in
07-28 12:33:01.964  2622  2622 V BluetoothAdapterState: isTurningOff()=true
,07-28 12:33:01.964  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:01.964  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:01.964  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:01.964  2622  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-28 12:33:01.964  2622  2642 D BluetoothAdapterProperties: Setting state to 15
07-28 12:33:01.965  2622  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-28 12:33:01.966  1373  1386 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:33:01.967  1373  1845 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:33:01.967  2622  2642 I BluetoothAdapterState: Entering BleOnState
07-28 12:33:01.967   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:01.964  2622  2622 D BluetoothMapService: cleanup()
07-28 12:33:01.967  2622  2622 D BluetoothMapService: MAP Service closeService in
,07-28 12:33:01.967   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:01.967  1373  1847 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:33:01.968  1373  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:01.968  1373  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:33:01.969  1373  1845 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:33:01.969   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:33:01.969   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:01.969  1753  1764 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:01.970  2622  2642 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-28 12:33:01.970  2622  2642 D BluetoothAdapterProperties: Setting state to 16,
07-28 12:33:01.970  2622  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-28 12:33:01.971  2622  2642 D BluetoothAdapterProperties: onBleDisable
07-28 12:33:01.972  2622  2642 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:33:01.972  2622  2643 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-28 12:33:01.973  2622  2647 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:33:01.973  2622  2739 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:33:01.973  2622  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 12:33:01.976  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:01.976  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:01.977  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:01.977  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:01.978  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:01.978  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:01.979  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:01.979  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:01.980  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.981  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:01.989  3867  3867 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-28 12:33:01.990   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:02.010  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:33:02.012   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:02.012   372   872 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:33:02.013   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-28 12:33:02.013   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:02.015   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:33:02.017   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:33:02.017  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:02.019  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:02.025   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a86305:true
,07-28 12:33:02.025  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:02.043   874  2705 I ActivityManager: Start proc 3885:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-28 12:33:02.045   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
07-28 12:33:02.047   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:33:02.050  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:02.050  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:02.051  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:02.051  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:02.053  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:02.053  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:02.054  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:02.054  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:02.057  1852  2059 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:33:02.066  3867  3867 D LocalBluetoothProfileManager: Adding local MAP profile
,07-28 12:33:02.070  3867  3867 D BluetoothMap: Create BluetoothMap proxy object
,07-28 12:33:02.071   372   872 E Netd    : netlink response contains error (No such file or directory)
07-28 12:33:02.072   874  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-28 12:33:02.081  3885  3885 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-28 12:33:02.082  3867  3867 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-28 12:33:02.092  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:02.102   874  1687 I ActivityManager: Killing 2397:com.google.android.talk/u0a61 (adj 15): empty #17
,07-28 12:33:02.174  2622  2647 I bt_hci  : shut_down
07-28 12:33:02.175  2622  2653 D bt_hwcfg: hw_epilog_process
07-28 12:33:02.175  2622  2653 I bt_vendor: low_power_mode_cb
,07-28 12:33:02.202  2622  2653 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-28 12:33:02.202  2622  2653 I bt_vendor: epilog_cb
,07-28 12:33:02.203  2622  2653 I bt_hci  : epilog_finished_callback
,07-28 12:33:02.229  2622  2647 I bt_hci_h4: hal_close
,07-28 12:33:02.230  2622  2647 I bt_userial_vendor: device fd = 51 close
,07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:583)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-,28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:02.254  3885  3885 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.254  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:02.255  3885  3885 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:02.255  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:02.282   874  1385 I ActivityManager: Start proc 3916:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
07-28 12:33:02.283   874  1385 I ActivityManager: Killing 3508:com.google.process.gapps/u0a99 (adj 15): empty #17
,07-28 12:33:02.350  3810  3810 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:33:02.353  2622  2643 D bt_stack_manager: event_shut_down_stack finished.
07-28 12:33:02.354  2622  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-28 12:33:02.355  2622  2642 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-28 12:33:02.355  2622  2622 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:33:02.356  2622  2622 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:33:02.357  2622  2622 D BtGatt.GattService: stop()
,07-28 12:33:02.357  2622  2622 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:33:02.358  2622  2622 V BluetoothAdapterState: isTurningOff()=false
07-28 12:33:02.359  2622  2622 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:02.359  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:02.359  2622  2622 V BluetoothAdapterState: isBleTurningOff()=true
07-28 12:33:02.359  2622  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-28 12:33:02.359  2622  2642 D BluetoothAdapterProperties: Setting state to 10
07-28 12:33:02.359  2622  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-28 12:33:02.359  2622  2642 I BluetoothAdapterState: Entering OffState
,07-28 12:33:02.361   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-28 12:33:02.365  3916  3916 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-28 12:33:02.371  2622  2622 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-28 12:33:02.371  2622  2622 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 12:33:02.371  2622  2622 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:33:02.372  2622  2643 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 12:33:02.375  2622  2643 D bt_stack_manager: event_clean_up_stack finished.
,07-28 12:33:02.392  2622  2622 I art     : System.exit called, status: 0
,07-28 12:33:02.392  2622  2622 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:33:02.448   874  1761 I ActivityManager: Process com.android.bluetooth (pid 2622) has died
,07-28 12:33:02.588  3916  3936 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-28 12:33:02.588  3916  3936 I Babel_SMS: MmsConfig.loadMmsSettings
,07-28 12:33:02.600  3916  3936 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-28 12:33:02.600  3916  3936 I Babel_SMS: MmsConfig.loadFromDatabase
,07-28 12:33:02.630  3916  3936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-28 12:33:02.630  3916  3936 I Babel_SMS: MmsConfig.loadFromResources
,07-28 12:33:02.638  3916  3936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-28 12:33:02.640  3916  3936 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-28 12:33:02.668  3916  3916 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:33:02.672  3916  3916 I Babel_Crash: startup - clean
,07-28 12:33:02.699  3916  3916 I Babel_telephony: TeleModule.launchCompleted
,07-28 12:33:02.712   874  1399 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-28 12:33:02.722  3916  3916 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-28 12:33:02.730  3916  3916 W Babel   : BAM#gBA: invalid account id: -1
,07-28 12:33:02.730  3916  3916 W Babel   : BAM#gBA: invalid account id: -1
07-28 12:33:02.730  3916  3916 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-28 12:33:02.750  3916  3941 I Babel   : deleted: false for 0
,07-28 12:33:02.759   874  1719 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-28 12:33:02.799  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:33:02.830   874  2705 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-28 12:33:02.843  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:02.888  3916  3916 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:33:02.979  3944  3944 D AdapterServiceConfig: Adding HeadsetService
,07-28 12:33:02.980  3944  3944 D AdapterServiceConfig: Adding A2dpService
07-28 12:33:02.980  3944  3944 D AdapterServiceConfig: Adding HidService
07-28 12:33:02.980  3944  3944 D AdapterServiceConfig: Adding HealthService
,07-28 12:33:02.984  3944  3944 D AdapterServiceConfig: Adding PanService
,07-28 12:33:02.984  3944  3944 D AdapterServiceConfig: Adding GattService
07-28 12:33:02.985  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 12:33:02.996  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:03.006  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:33:03.009  1781  1781 D SystemUpdateService: onCreate
,07-28 12:33:03.009  3916  3916 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-28 12:33:03.011  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:33:03.016  1781  3957 I SystemUpdateService: active receiver: enabled
,07-28 12:33:03.021  1781  3957 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:33:03.022  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:33:03.023  1781  3957 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 12:33:03.023  1781  3957 I SystemUpdateService: now status is 0 (complete)
07-28 12:33:03.024  1781  3957 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 12:33:03.024  1781  3957 I SystemUpdateService: file has been verified
,07-28 12:33:03.024  1781  3957 I SystemUpdateService: OTA package size = 12249756
07-28 12:33:03.025  1781  2370 I iu.UploadsManager: num queued entries: 0
07-28 12:33:03.028  1781  2370 I iu.UploadsManager: num updated entries: 0
,07-28 12:33:03.029  1781  3957 I SystemUpdateService: showing system update notification
,07-28 12:33:03.031  1781  2370 I iu.SyncManager: NEXT; no task
,07-28 12:33:03.036  3916  3916 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 12:33:03.038  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-28 12:33:03.038  3916  3916 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 12:33:03.041  3916  3916 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 12:33:03.041  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:33:03.058   874  2705 I ActivityManager: Start proc 3959:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-28 12:33:03.062  1781  1781 D SystemUpdateService: onDestroy
,07-28 12:33:03.074  3916  3916 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:33:03.080   874  1719 I ActivityManager: Killing 2531:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-28 12:33:03.125  3916  3916 I vclib   : onServiceConnected
,07-28 12:33:03.143  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-28 12:33:03.148  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:03.161  3959  3959 D SprintDMHelper: simOperator: 
07-28 12:33:03.161  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 12:33:03.174   874  1719 I ActivityManager: Start proc 3971:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-28 12:33:03.175   874  1719 I ActivityManager: Killing 3436:android.process.acore/u0a5 (adj 15): empty #17
,07-28 12:33:03.187  3885  3914 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-28 12:33:03.249   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e3f799:true
,07-28 12:33:03.383   874  1399 I ActivityManager: Start proc 3986:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-28 12:33:03.387  3916  3985 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-28 12:33:03.396   874  3081 I ActivityManager: Killing 3630:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-28 12:33:03.455  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-28 12:33:03.510  3986  3986 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-28 12:33:03.510  3986  3986 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-28 12:33:03.510  3986  3986 I GAv4    :   adb logcat -s GAv4
,07-28 12:33:03.526  3986  3986 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:33:03.533  3986  3986 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:33:03.569  3986  4003 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:33:03.675  3986  3986 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-28 12:33:03.716  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-28 12:33:03.728  3986  3986 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 850-856)
07-28 12:33:03.728  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:33:03.738  3986  3986 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6c63a72}
,07-28 12:33:03.739  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:33:03.740  3986  3986 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:33:03.749  3986  3986 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:33:03.751  3986  3986 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:33:03.767  3986  3986 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-28 12:33:03.783  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:33:03.783  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:33:03.783  3986  3986 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 12:33:03.783  3986  3986 I Adreno  : Build Date                       : 10/20/15
07-28 12:33:03.783  3986  3986 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 12:33:03.783  3986  3986 I Adreno  : Local Branch                     : M14
07-28 12:33:03.783  3986  3986 I Adreno  : Remote Branch                    : 
07-28 12:33:03.783  3986  3986 I Adreno  : Remote Branch                    : 
07-28 12:33:03.783  3986  3986 I Adreno  : Reconstruct Branch               : 
,07-28 12:33:03.852  3986  3986 I NSApplication: Starting up...
,07-28 12:33:03.852  3986  4032 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 12:33:03.890   874  2705 I ActivityManager: Start proc 4037:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-28 12:33:03.891   874  2705 I ActivityManager: Killing 3647:com.android.musicfx/u0a18 (adj 15): empty #17
,07-28 12:33:03.996  4037  4037 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-28 12:33:04.175   874   884 I ActivityManager: Killing 3343:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-28 12:33:04.276   874  1692 I ActivityManager: Start proc 4051:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-28 12:33:04.346  4051  4051 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-28 12:33:04.408  4051  4051 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-28 12:33:04.429   874  3081 I ActivityManager: Killing 3668:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-28 12:33:04.938   874  1750 D WifiService: setWifiEnabled: true pid=3810, uid=10000
,07-28 12:33:04.939   874  1750 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:33:04.955   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:33:04.962  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:04.963  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:04.963  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:04.963  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:04.966  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:04.967  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:04.967  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:04.967  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:04.991   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,07-28 12:33:04.991   874  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:33:04.992   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-28 12:33:04.992   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-28 12:33:04.993   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:33:04.993   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2,
07-28 12:33:04.994   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-28 12:33:04.994   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 12:33:05.012   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-28 12:33:05.013   372   872 D CommandListener: Setting iface cfg
07-28 12:33:05.014   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-28 12:33:05.014   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-28 12:33:05.014   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:33:05.021   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:33:05.021   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-28 12:33:05.046   874  1315 E native  : do suspend true
,07-28 12:33:05.062   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:33:06.428   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:33:06.470   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.56 rxSuccessRate=11.06 delta 1000 -> 994
,07-28 12:33:06.472   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-28 12:33:06.472   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:33:06.488   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 12:33:06.542   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 12:33:06.544  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 12:33:06.966  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 12:33:07.003  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-28 12:33:07.003  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-28 12:33:07.010   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:33:07.022   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:33:07.022   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:33:07.022   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-28 12:33:07.038   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:33:07.048   372   872 D CommandListener: Setting iface cfg
,07-28 12:33:07.050   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,07-28 12:33:07.059   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-28 12:33:07.097   874  4084 D DhcpClient: Receive thread started
,07-28 12:33:07.182   874  1315 E native  : do suspend false
,07-28 12:33:07.193   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,07-28 12:33:07.205   874  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172520, domain null
,07-28 12:33:07.205   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172520 seconds
07-28 12:33:07.206   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-28 12:33:07.217   874  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-28 12:33:07.217   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-28 12:33:07.218   372   872 D CommandListener: Setting iface cfg
,07-28 12:33:07.222   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-28 12:33:07.224   874  2102 D DhcpClient: Scheduling renewal in 86399s
,07-28 12:33:07.226   874  1315 E native  : do suspend true
,07-28 12:33:07.246   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 12:33:07.249   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 12:33:07.250   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-28 12:33:07.252   874  1317 D ConnectivityService: Adding iface wlan0 to network 101
,07-28 12:33:07.260   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:33:07.330   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-28 12:33:07.330   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-28 12:33:07.332   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-28 12:33:07.335   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-28 12:33:07.338   874  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-28 12:33:07.357   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-28 12:33:07.364   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-28 12:33:07.364   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-28 12:33:07.365   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-28 12:33:07.365   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-28 12:33:07.365   874  1317 D ConnectivityService:    accepting network in place of null
,07-28 12:33:07.365   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:07.366   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:33:07.381   874  4083 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304509, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 12:33:07.414   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:07.449   874  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:4001:815::200e
,07-28 12:33:07.457   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:07.460   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-28 12:33:07.460   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:07.468   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:33:07.468   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 12:33:07.469  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:07.469  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:33:07.469  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:07.469  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:07.470  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:07.471  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:33:07.471  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:07.471  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:07.476  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
07-28 12:33:07.479  1781  1781 D SystemUpdateService: onCreate
,07-28 12:33:07.484  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:33:07.486  1781  4093 I SystemUpdateService: active receiver: enabled
,07-28 12:33:07.490  1781  4093 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:33:07.493  1781  4093 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
07-28 12:33:07.493  1781  4093 I SystemUpdateService: now status is 0 (complete)
07-28 12:33:07.493  1781  4093 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 12:33:07.493  1781  4093 I SystemUpdateService: file has been verified
07-28 12:33:07.493  1781  4093 I SystemUpdateService: OTA package size = 12249756
,07-28 12:33:07.499  1781  4093 I SystemUpdateService: showing system update notification
,07-28 12:33:07.502  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 12:33:07.503  1781  2370 I iu.UploadsManager: num queued entries: 0
,07-28 12:33:07.505  1781  2370 I iu.UploadsManager: num updated entries: 0
,07-28 12:33:07.507  1781  2370 I iu.SyncManager: NEXT; no task
,07-28 12:33:07.509  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 12:33:07.510  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:33:07.512  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:07.514  1781  1781 D SystemUpdateService: onDestroy
,07-28 12:33:07.515  1781  4096 I MDM     : [207] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-28 12:33:07.515  1781  4096 W BaseAppContext: Using Auth Proxy for data requests.
,07-28 12:33:07.517  1781  4096 V GoogleAuthProtoRequest: [207] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 12:33:07.518   874  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:33:07 GMT], X-Android-Received-Millis=[1469701987517], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469701987493]}
07-28 12:33:07.518   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 12:33:07.518   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-28 12:33:07.519   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:33:07.520   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:33:07.520  3959  3959 D SprintDMHelper: simOperator: 
,07-28 12:33:07.521  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
07-28 12:33:07.523  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 12:33:07.526  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:33:07.533  3916  3916 I art     : Waiting for a blocking GC DisableMovingGc
,07-28 12:33:07.539  3916  3916 I art     : WaitForGcToComplete blocked for 5.715ms for cause DisableMovingGc
07-28 12:33:07.539  3916  3916 I art     : Starting a blocking GC DisableMovingGc
,07-28 12:33:07.550  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-28 12:33:07.550  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 12:33:07.550  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:33:07.550  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:33:07.572  1781  4096 E MDM     : [207] SitrepService.a: Error sending sitrep.
,07-28 12:33:07.660  3916  4099 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 12:33:07.947   874   884 D WifiService: setWifiEnabled: false pid=3810, uid=10000
,07-28 12:33:07.948   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:33:07.968  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-28 12:33:07.972   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-28 12:33:07.973   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,07-28 12:33:07.973   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:07.974   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:33:07.994   874  1315 E native  : do suspend true
,07-28 12:33:08.003   874  2102 D DhcpClient: Clearing IP address
07-28 12:33:08.004   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:33:08.011  1506  4103 V NativeCrypto: Read error: ssl=0x9b288000: I/O error during system call, Connection timed out
,07-28 12:33:08.014  1506  4103 V NativeCrypto: SSL shutdown failed: ssl=0x9b288000: I/O error during system call, Broken pipe
,07-28 12:33:08.018   874  3081 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,07-28 12:33:08.019   874  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
07-28 12:33:08.020   874  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:4001:815::200e
,07-28 12:33:08.022   372   872 D CommandListener: Setting iface cfg
,07-28 12:33:08.026   874  4084 D DhcpClient: Receive thread stopped
,07-28 12:33:08.027   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-28 12:33:08.027   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-28 12:33:08.028   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,07-28 12:33:08.029   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:08.029   874  1315 E native  : do suspend true
07-28 12:33:08.035   396   396 E Parcel  : Reading a NULL string not supported here.
,07-28 12:33:08.037   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-28 12:33:08.040   874  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:815::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,07-28 12:33:08.042   372   872 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:33:08.046   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:33:08.059   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
07-28 12:33:08.061  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:08.061  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:08.062  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:08.062  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:08.062  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:08.063  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:08.063  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:08.063  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:08.064  1852  2059 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:33:08.065   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:33:08.076   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:08.102   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:08.103   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:33:08.103   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:08.105   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:33:08.110  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:08.111  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:08.120  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:33:08.123  1781  1781 D SystemUpdateService: onCreate
,07-28 12:33:08.127  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:33:08.131  1781  4113 I SystemUpdateService: active receiver: enabled
,07-28 12:33:08.136  1781  4113 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:33:08.138  1781  4113 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 12:33:08.138  1781  4113 I SystemUpdateService: now status is 0 (complete)
07-28 12:33:08.139  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-28 12:33:08.138  1781  4113 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 12:33:08.141  1781  4113 I SystemUpdateService: file has been verified
07-28 12:33:08.141  1781  2370 I iu.UploadsManager: num queued entries: 0
,07-28 12:33:08.141  1781  4113 I SystemUpdateService: OTA package size = 12249756
07-28 12:33:08.142  1781  2370 I iu.UploadsManager: num updated entries: 0
07-28 12:33:08.145  1781  4113 I SystemUpdateService: showing system update notification
07-28 12:33:08.145  1781  2370 I iu.SyncManager: NEXT; no task
,07-28 12:33:08.153  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 12:33:08.155  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:33:08.159  1781  1781 D SystemUpdateService: onDestroy
,07-28 12:33:08.192  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:08.197  3959  3959 I art     : Waiting for a blocking GC DisableMovingGc
,07-28 12:33:08.198   372   872 E Netd    : netlink response contains error (No such file or directory)
,07-28 12:33:08.199   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 12:33:08.199  3959  3959 I art     : Starting a blocking GC DisableMovingGc
07-28 12:33:08.200  3959  3959 D SprintDMHelper: simOperator: 
07-28 12:33:08.200  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 12:33:08.214  3916  4118 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-28 12:33:08.224   874  2705 I ActivityManager: Killing 3592:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-28 12:33:08.460   874  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-28 12:33:10.985   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@86f1d32:true
07-28 12:33:10.986  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 12:33:10.995  3944  4122 I BluetoothAdapterState: Entering OffState
07-28 12:33:10.995  3944  3944 I bt_bluedroid: init
,07-28 12:33:10.998  3944  4123 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:33:10.999  3944  4123 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:33:10.999  3944  4123 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:33:10.999  3944  4123 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:33:11.000  3944  3944 I bt_bluedroid: get_profile_interface socket
07-28 12:33:11.005  3944  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-28 12:33:11.005  3944  3944 I bt_bluedroid: get_profile_interface sdp
07-28 12:33:11.011  3944  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:33:11.015  3944  3955 I bt_bluedroid: config_hci_snoop_log
07-28 12:33:11.016   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-28 12:33:11.022  3944  4122 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 12:33:11.023  3944  4122 D BluetoothAdapterProperties: Setting state to 14
,07-28 12:33:11.023  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 12:33:11.025  3944  4122 D BluetoothBondStateMachine: make
,07-28 12:33:11.029  3944  4127 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:33:11.034  3944  4122 I BluetoothAdapterState: Entering PendingCommandState,
,07-28 12:33:11.036  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-28 12:33:11.043  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:11.046  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:33:11.047  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
,07-28 12:33:11.047  3944  3944 D BtGatt.GattService: start()
07-28 12:33:11.048  3944  3944 I bt_bluedroid: get_profile_interface gatt
,07-28 12:33:11.050  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:11.050  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:33:11.057  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:11.057  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:11.057  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
07-28 12:33:11.057  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:11.058  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-28 12:33:11.058  3944  4122 I bt_bluedroid: enable
07-28 12:33:11.058  3944  4123 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-28 12:33:11.059  3944  4123 I bt_hci  : start_up
,07-28 12:33:11.077  3944  4123 I bt_vendor: alloc value 0xb3a29189
,07-28 12:33:11.077  3944  4123 I bt_vendor: init
07-28 12:33:11.077  3944  4123 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:33:11.078  3944  4123 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 12:33:11.185  3944  4123 D bt_hci  : start_up starting async portion
,07-28 12:33:11.186  3944  4130 I bt_hci  : event_finish_startup,
07-28 12:33:11.186  3944  4130 I bt_hci_h4: hal_open
,07-28 12:33:11.186  3944  4130 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:33:11.193  3944  4130 I bt_userial_vendor: device fd = 51 open
,07-28 12:33:11.228  3944  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:33:11.260  3944  4130 D bt_hwcfg: Chipset BCM4354A2
07-28 12:33:11.260  3944  4130 D bt_hwcfg: Target name = [BCM4354A2]
,07-28 12:33:11.261  3944  4130 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 12:33:11.922  3944  4130 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:33:11.924  3944  4130 D bt_hwcfg: Settlement delay -- 100 ms
,07-28 12:33:11.925  3944  4130 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:33:12.042  3944  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:33:12.043  3944  4130 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 12:33:12.070  3944  4130 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:33:12.071  3944  4130 I bt_vendor: firmware callback
07-28 12:33:12.071  3944  4130 I bt_hci  : firmware_config_callback
,07-28 12:33:12.084  3944  4132 I bt_btu  : btu_task pending for preload complete event
,07-28 12:33:12.084  3944  4132 I bt_btu_task: Bluetooth chip preload is complete
07-28 12:33:12.084  3944  4132 I bt_btu  : btu_task received preload complete event
,07-28 12:33:12.094  3944  4132 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:33:12.094  3944  4132 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:33:12.095  3944  4132 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-28 12:33:12.095  3944  4132 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:33:12.095  3944  4132 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:33:12.096  3944  4132 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:33:12.096  3944  4132 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-28 12:33:12.097  3944  4132 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:33:12.097  3944  4132 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 12:33:12.098  3944  4132 I         : BTE_InitTraceLevels -- TRC_PAN
,07-28 12:33:12.099  3944  4132 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:33:12.099  3944  4132 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:33:12.100  3944  4132 I         : BTE_InitTraceLevels -- TRC_SMP
,07-28 12:33:12.100  3944  4132 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:33:12.101  3944  4132 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:33:12.239  3944  4132 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,07-28 12:33:12.239  3944  4132 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,07-28 12:33:12.251  3944  4126 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-28 12:33:12.253  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:33:12.254  3944  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:33:12.256  3944  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:33:12.260  3944  4126 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:33:12.260  3944  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:33:12.261  3944  4126 D bt_hci  : do_postload posting postload work item
,07-28 12:33:12.262  3944  4130 I bt_hci  : event_postload
,07-28 12:33:12.262  3944  4130 I bt_vendor: sco_config_cb
,07-28 12:33:12.262  3944  4130 I bt_hci  : sco_config_callback postload finished.
07-28 12:33:12.266  3944  4126 D bt_bte_conf: Device ID record 1 : primary
07-28 12:33:12.266  3944  4126 D bt_bte_conf:   vendorId            = 000f
07-28 12:33:12.267  3944  4126 D bt_bte_conf:   vendorIdSource      = 0001
,07-28 12:33:12.267  3944  4126 D bt_bte_conf:   product             = 1200
07-28 12:33:12.267  3944  4126 D bt_bte_conf:   version             = 1436
07-28 12:33:12.267  3944  4126 D bt_bte_conf:   clientExecutableURL = 
07-28 12:33:12.267  3944  4126 D bt_bte_conf:   serviceDescription  = 
,07-28 12:33:12.268  3944  4126 D bt_bte_conf:   documentationURL    = 
07-28 12:33:12.269  3944  4126 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-28 12:33:12.269  3944  4123 D bt_stack_manager: event_start_up_stack finished
,07-28 12:33:12.270  3944  4130 I bt_vendor: low_power_mode_cb
07-28 12:33:12.270  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:12.274  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:12.274  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-28 12:33:12.275  3944  4122 D BluetoothAdapterProperties: Setting state to 15
07-28 12:33:12.275  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-28 12:33:12.276  3944  4122 I BluetoothAdapterState: Entering BleOnState
,07-28 12:33:12.282  3944  4122 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-28 12:33:12.282  3944  4122 D BluetoothAdapterProperties: Setting state to 11
,07-28 12:33:12.282  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-28 12:33:12.287  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:12.289  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:12.290  3944  3944 D HeadsetService: Received start request. Starting profile...
07-28 12:33:12.291  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:12.293  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:33:12.293  3944  3944 D HeadsetStateMachine: make
,07-28 12:33:12.303  3944  4122 I BluetoothAdapterState: Entering PendingCommandState
,07-28 12:33:12.304  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
,07-28 12:33:12.304  3944  3944 I bt_bluedroid: get_profile_interface handsfree
07-28 12:33:12.304  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-28 12:33:12.304  3944  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-28 12:33:12.311  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:12.313  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:12.314  3944  3944 D A2dpService: Received start request. Starting profile...
,07-28 12:33:12.315  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:33:12.315  3944  3944 I bt_bluedroid: get_profile_interface avrcp
,07-28 12:33:12.322  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:33:12.322  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:33:12.322  3944  3944 D A2dpStateMachine: make
,07-28 12:33:12.323  3944  3944 I bt_bluedroid: get_profile_interface a2dp
,07-28 12:33:12.324  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-28 12:33:12.329  3944  4141 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:33:12.329  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:33:12.331  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:12.332  3944  3944 D HidService: Received start request. Starting profile...
,07-28 12:33:12.332  3867  3867 D BluetoothInputDevice: Proxy object connected
07-28 12:33:12.332  3944  3944 I bt_bluedroid: get_profile_interface hidhost
07-28 12:33:12.332  3944  4126 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
,07-28 12:33:12.332  3944  3944 D HidService: setHidService(): set to: null
07-28 12:33:12.333  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-28 12:33:12.333  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:33:12.334  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
07-28 12:33:12.334  3867  3867 D HidProfile: Bluetooth service connected
07-28 12:33:12.335  3944  3944 D HealthService: Received start request. Starting profile...
,07-28 12:33:12.336  3944  3944 I bt_bluedroid: get_profile_interface health
,07-28 12:33:12.337  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:33:12.338  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:12.339  3944  3944 D PanService: Received start request. Starting profile...
,07-28 12:33:12.339  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:33:12.339  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:33:12.339  3944  3944 I bt_bluedroid: get_profile_interface pan
,07-28 12:33:12.340  3944  4126 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:33:12.340  3867  3867 D PanProfile: Bluetooth service connected
,07-28 12:33:12.345  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:12.347  3944  3944 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:33:12.347  3944  3944 D BluetoothMapService: start()
,07-28 12:33:12.353  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-28 12:33:12.354  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-28 12:33:12.354  3944  3944 D BluetoothMapAppObserver: createReceiver()
,07-28 12:33:12.356  3867  3867 D BluetoothMap: Proxy object connected
,07-28 12:33:12.356  3944  3944 D BluetoothMapAppObserver: initObservers()
07-28 12:33:12.356  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 12:33:12.357  3867  3867 D MapProfile: Bluetooth service connected
,07-28 12:33:12.357  3867  3867 D BluetoothMap: getConnectedDevices()
07-28 12:33:12.357  3867  3867 D BluetoothMap: Bluetooth is Not enabled
,07-28 12:33:12.363  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:12.363  3944  3944 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:12.364  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:12.364  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:12.366  3944  4139 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isTurningOff()=false
07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:12.366  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:12.367  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:12.368  3944  3944 V BluetoothAdapterState: isTurningOff()=false
07-28 12:33:12.368  3944  3944 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:12.368  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:12.368  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:12.369  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-28 12:33:12.369  3944  4122 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:33:12.370  3944  4122 D BluetoothAdapterProperties: State =  11
07-28 12:33:12.372  3944  4126 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:33:12.372  3944  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:33:12.372  3944  4122 D BluetoothAdapterProperties: Setting state to 12
07-28 12:33:12.372  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:33:12.373  3944  4122 I BluetoothAdapterState: Entering OnState
,07-28 12:33:12.373  1373  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:33:12.375  1373  1847 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:12.377  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:12.378   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:12.379   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:33:12.379  1373  1386 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:33:12.379  1373  1373 D BluetoothA2dp: Proxy object connected
07-28 12:33:12.379  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:12.381  1373  1847 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:12.382  1373  1845 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:33:12.382  1373  1373 D BluetoothMap: Proxy object connected
07-28 12:33:12.382  1373  1373 D MapProfile: Bluetooth service connected
,07-28 12:33:12.383  1373  1373 D BluetoothMap: getConnectedDevices()
,07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:12.384  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:12.384  3867  3879 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:33:12.385  1373  1373 D BluetoothInputDevice: Proxy object connected
07-28 12:33:12.385  1373  1373 D HidProfile: Bluetooth service connected
07-28 12:33:12.384  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 12:33:12.386  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:12.386  1373  1847 D BluetoothPan: onBluetoothStateChange on: true
,07-28 12:33:12.386  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-28 12:33:12.388  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:33:12.388  1373  1373 D PanProfile: Bluetooth service connected
07-28 12:33:12.388   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:33:12.388  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:33:12.388   874   874 D BluetoothA2dp: Proxy object connected
07-28 12:33:12.389   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:33:12.390  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:33:12.391  3867  3877 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:33:12.392  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
07-28 12:33:12.392  3867  3879 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:33:12.392  3944  3944 D ObexServerSockets0: startAccept()
07-28 12:33:12.392  3944  3944 D ObexServerSockets0: prepareForNewConnect()
07-28 12:33:12.393  1753  1764 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:12.394  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-28 12:33:12.394  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
07-28 12:33:12.395  3944  4148 D ObexServerSockets0: Accepting socket connection...
,07-28 12:33:12.395  3867  3877 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:33:12.395  3944  4147 D ObexServerSockets0: Accepting socket connection...
07-28 12:33:12.397   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 12:33:12.399  3944  3944 D BluetoothMapService: onReceive
07-28 12:33:12.399  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:33:12.399  3944  3944 D BluetoothMapService: STATE_ON
07-28 12:33:12.399  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:12.400  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:12.403  3867  3867 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-28 12:33:12.412  3867  3867 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-28 12:33:12.417  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:33:12.419  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 12:33:12.419  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,07-28 12:33:12.421  3867  3867 D BluetoothA2dp: Proxy object connected
,07-28 12:33:12.428  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:12.430  1373  1373 D BluetoothPbap: Proxy object connected
,07-28 12:33:12.430  1373  1373 D PbapServerProfile: Bluetooth service connected
,07-28 12:33:12.432  3944  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:33:12.438  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:12.439  3867  3867 D BluetoothPbap: Proxy object connected
,07-28 12:33:12.439  3867  3867 D PbapServerProfile: Bluetooth service connected
,07-28 12:33:12.450  3944  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:33:12.451  3944  4157 I BtOppRfcommListener: Accept thread started.
,07-28 12:33:12.479   874   874 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.479  1753  1928 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.480   874   874 D BluetoothHeadset: Proxy object connected
07-28 12:33:12.480  1373  1386 D BluetoothHeadset: Proxy object connected
07-28 12:33:12.480  1373  1373 D HeadsetProfile: Bluetooth service connected
,07-28 12:33:12.481   874   874 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.482  1373  1384 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.485  1373  1373 D HeadsetProfile: Bluetooth service connected
,07-28 12:33:12.491   874   891 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.494  1753  1765 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.516  3867  3879 D BluetoothHeadset: Proxy object connected
,07-28 12:33:12.519  3867  3867 D HeadsetProfile: Bluetooth service connected
,07-28 12:33:13.966  1781  4160 I EventLogService: Opted in for usage reporting
,07-28 12:33:13.967  1781  4160 I EventLogService: Aggregate from 1469700174708 (log), 1469700174708 (data)
,07-28 12:33:13.969  3944  4122 D BluetoothAdapterState: Current state: ON, message: 23
07-28 12:33:13.969  3944  4122 D BluetoothAdapterProperties: Setting state to 13
07-28 12:33:13.969  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:33:13.971  3944  4122 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:33:13.973  3944  4122 I BluetoothAdapterState: Entering PendingCommandState
,07-28 12:33:13.977  3944  4126 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:33:13.978  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-28 12:33:13.982  3944  3944 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:33:13.983  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:13.984  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:13.985  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:33:13.985  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:13.989  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:13.990  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:13.991  3810  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:33:13.991  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:13.995  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:13.996  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:13.996  3944  3944 D BluetoothMapService: onReceive
07-28 12:33:13.996  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:33:13.996  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
,07-28 12:33:13.997  3944  3944 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:13.997  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:13.997  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:13.997  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:13.995  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:33:13.998  3944  3944 D A2dpService: Received stop request...Stopping profile...
,07-28 12:33:13.998  3944  4141 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:33:13.998  3867  3879 D BluetoothHeadset: Proxy object disconnected
07-28 12:33:13.999   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:14.000  1753  1935 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:14.001  3944  3944 D BluetoothMapService: MAP Service closeService in
,07-28 12:33:14.001   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:14.001  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
,07-28 12:33:14.001  3944  3944 D ObexServerSockets0: shutdown(block = true)
,07-28 12:33:14.002  1373  1845 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:14.003   874   874 D BluetoothHeadset: Proxy object disconnected
,07-28 12:33:14.003  3944  4147 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 12:33:14.003  3867  3867 D HeadsetProfile: Bluetooth service disconnected
,07-28 12:33:14.004   874   874 D BluetoothA2dp: Proxy object disconnected
07-28 12:33:14.004  3867  3867 D BluetoothA2dp: Proxy object disconnected
07-28 12:33:14.002  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:33:14.005  3944  4148 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 12:33:14.006  3944  4134 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-28 12:33:14.006  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:33:14.007  3944  3944 I BtOppRfcommListener: stopping Accept Thread
,07-28 12:33:14.007  3944  4157 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:33:14.007  3944  4157 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:33:14.010  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:33:14.010  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:33:14.010  1373  1373 D BluetoothA2dp: Proxy object disconnected
07-28 12:33:14.010  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,07-28 12:33:14.011  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-28 12:33:14.011  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:14.011  3944  3944 D HidService: Received stop request...Stopping profile...
07-28 12:33:14.011  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:14.011  3944  3944 D HidService: Stopping Bluetooth HidService
07-28 12:33:14.011  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:14.011  3944  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-28 12:33:14.013  3944  3944 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:14.013  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.013  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:14.013  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:14.014  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-28 12:33:14.014  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:14.015  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 12:33:14.015  3944  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:33:14.015  3944  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:33:14.015  3944  4132 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:33:14.015  3944  4132 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:33:14.015  3944  3944 D HealthService: Received stop request...Stopping profile...
07-28 12:33:14.019  3944  3944 D PanService: Received stop request...Stopping profile...
07-28 12:33:14.020  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
,07-28 12:33:14.020  3944  3944 D BluetoothMapService: stop()
07-28 12:33:14.020  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:33:14.021  3944  3944 D BluetoothMapAppObserver: deinitObservers()
07-28 12:33:14.021  3944  3944 D BluetoothMapAppObserver: removeReceiver()
,07-28 12:33:14.027  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:14.028  3944  3944 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:14.028  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.028  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:14.028  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:14.028  1373  1373 D BluetoothInputDevice: Proxy object disconnected
07-28 12:33:14.028  1373  1373 D HidProfile: Bluetooth service disconnected
07-28 12:33:14.028  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:33:14.028  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:33:14.028  1373  1373 D PanProfile: Bluetooth service disconnected
07-28 12:33:14.028  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:33:14.029  3944  3944 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:14.029  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.029  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:14.029  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:14.029  1373  1373 D BluetoothMap: Proxy object disconnected
07-28 12:33:14.029  1373  1373 D MapProfile: Bluetooth service disconnected
07-28 12:33:14.029  3944  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:33:14.029  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:33:14.029  3944  4126 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 12:33:14.029  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:33:14.030  3867  3867 D BluetoothInputDevice: Proxy object disconnected
07-28 12:33:14.030  3867  3867 D HidProfile: Bluetooth service disconnected
,07-28 12:33:14.030  3867  3867 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:33:14.030  3867  3867 D PanProfile: Bluetooth service disconnected
07-28 12:33:14.034  3944  3944 V BluetoothAdapterState: isTurningOff()=true
,07-28 12:33:14.034  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.034  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:14.035  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:14.035  3867  3867 D BluetoothMap: Proxy object disconnected
07-28 12:33:14.035  3867  3867 D MapProfile: Bluetooth service disconnected
07-28 12:33:14.035  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:33:14.035  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:33:14.036  3944  3944 D BluetoothMapService: MAP Service closeService in
07-28 12:33:14.036  3944  3944 V BluetoothAdapterState: isTurningOff()=true
07-28 12:33:14.036  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.036  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:14.036  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:14.036  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-28 12:33:14.037  3944  3944 D BluetoothMapService: cleanup()
07-28 12:33:14.037  3944  4122 D BluetoothAdapterProperties: Setting state to 15
07-28 12:33:14.037  3944  3944 D BluetoothMapService: MAP Service closeService in
07-28 12:33:14.037  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-28 12:33:14.037  3944  4122 I BluetoothAdapterState: Entering BleOnState
07-28 12:33:14.038  1373  1386 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:33:14.039  1373  1845 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:33:14.039   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.039  3867  3867 D BluetoothPbap: Proxy object disconnected
07-28 12:33:14.039  3867  4149 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.039  3867  3867 D PbapServerProfile: Bluetooth service disconnected
07-28 12:33:14.040   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.040  1373  1384 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:33:14.041  1373  1847 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.042  3867  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:33:14.042  1373  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:33:14.043  3867  3877 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:33:14.043  1373  1845 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:33:14.043   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:33:14.044   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.044  3867  4149 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:33:14.044  3867  3879 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:33:14.045  1753  1764 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:33:14.045  3867  3877 D BluetoothPan: onBluetoothStateChange on: false
,07-28 12:33:14.045  3944  4122 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-28 12:33:14.046  3944  4122 D BluetoothAdapterProperties: Setting state to 16
07-28 12:33:14.046  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-28 12:33:14.049  3944  4122 D BluetoothAdapterProperties: onBleDisable
,07-28 12:33:14.049  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:14.049  3944  4123 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-28 12:33:14.050  3944  4126 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:33:14.050  3944  4132 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:33:14.050  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:14.050  3944  4132 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:33:14.051  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:33:14.052  3944  4122 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:33:14.053  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:14.055  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:14.055  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:14.063  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:14.092  1781  4160 W EventLogAggregator: Unknown tag: snet_gcore
07-28 12:33:14.092  1781  4160 W EventLogAggregator: Unknown tag: snet_launch_service
,07-28 12:33:14.138  1781  4160 I ServiceDumpSys: dumping service [account]
,07-28 12:33:14.251  3944  4126 I bt_hci  : shut_down
,07-28 12:33:14.251  3944  4130 D bt_hwcfg: hw_epilog_process
,07-28 12:33:14.253  3944  4130 I bt_vendor: low_power_mode_cb
,07-28 12:33:14.276  3944  4130 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-28 12:33:14.276  3944  4130 I bt_vendor: epilog_cb
07-28 12:33:14.276  3944  4130 I bt_hci  : epilog_finished_callback
07-28 12:33:14.287  3944  4126 I bt_hci_h4: hal_close
07-28 12:33:14.288  3944  4126 I bt_userial_vendor: device fd = 51 close
,07-28 12:33:14.405  3944  4123 D bt_stack_manager: event_shut_down_stack finished.
,07-28 12:33:14.407  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-28 12:33:14.413  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:33:14.413  3944  4122 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-28 12:33:14.415  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:33:14.415  3944  3944 D BtGatt.GattService: stop()
,07-28 12:33:14.416  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:33:14.421  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:14.421  3944  3944 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:14.421  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:14.422  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
,07-28 12:33:14.423  3944  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-28 12:33:14.423  3944  4122 D BluetoothAdapterProperties: Setting state to 10
07-28 12:33:14.423  3944  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-28 12:33:14.426  3944  4122 I BluetoothAdapterState: Entering OffState
07-28 12:33:14.426   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-28 12:33:14.455  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-28 12:33:14.455  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 12:33:14.456  3944  4123 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 12:33:14.465  3944  4123 D bt_stack_manager: event_clean_up_stack finished.
,07-28 12:33:14.467  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:33:14.476  3944  3944 I art     : System.exit called, status: 0
,07-28 12:33:14.476  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:33:14.545   874  1719 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,07-28 12:33:15.372   874  1317 D ConnectivityService: handlePromptUnvalidated 101
,07-28 12:33:16.966  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:16.966  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:19.974  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:33:19.974  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5923a3b added. We now have 6 listener(s)
,07-28 12:33:19.975  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:33:19.979  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:19.979  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a2f558 added. We now have 7 listener(s)
,07-28 12:33:19.979  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:19.981  3810  3861 I System.out: IsBluetoothEnabled
,07-28 12:33:19.992  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:20.041   874   891 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-28 12:33:20.164  4169  4169 D AdapterServiceConfig: Adding HeadsetService
,07-28 12:33:20.165  4169  4169 D AdapterServiceConfig: Adding A2dpService
,07-28 12:33:20.165  4169  4169 D AdapterServiceConfig: Adding HidService
07-28 12:33:20.165  4169  4169 D AdapterServiceConfig: Adding HealthService
,07-28 12:33:20.165  4169  4169 D AdapterServiceConfig: Adding PanService
07-28 12:33:20.166  4169  4169 D AdapterServiceConfig: Adding GattService
07-28 12:33:20.166  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 12:33:20.181  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 12:33:20.181   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db64243:true
,07-28 12:33:20.189  4169  4169 I bt_bluedroid: init
,07-28 12:33:20.189  4169  4181 I BluetoothAdapterState: Entering OffState
,07-28 12:33:20.195  4169  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-28 12:33:20.195  4169  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 12:33:20.195  4169  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:33:20.196  4169  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:33:20.197  4169  4169 I bt_bluedroid: get_profile_interface socket
,07-28 12:33:20.200  4169  4169 I bt_bluedroid: get_profile_interface sdp
,07-28 12:33:20.203  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:33:20.203  4169  4180 I bt_bluedroid: config_hci_snoop_log
,07-28 12:33:20.205   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-28 12:33:20.207  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:33:20.213  4169  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 12:33:20.214  4169  4181 D BluetoothAdapterProperties: Setting state to 14
,07-28 12:33:20.214  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 12:33:20.219  4169  4181 D BluetoothBondStateMachine: make
,07-28 12:33:20.224  4169  4186 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:33:20.230  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,07-28 12:33:20.232  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-28 12:33:20.236  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:20.237  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:33:20.237  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:33:20.238  4169  4169 D BtGatt.GattService: start()
07-28 12:33:20.238  4169  4169 I bt_bluedroid: get_profile_interface gatt
,07-28 12:33:20.239  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
07-28 12:33:20.239  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:33:20.249  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:20.249  4169  4169 V BluetoothAdapterState: isTurningOn()=false
07-28 12:33:20.249  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
07-28 12:33:20.249  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:20.250  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-28 12:33:20.250  4169  4181 I bt_bluedroid: enable
,07-28 12:33:20.250  4169  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-28 12:33:20.251  4169  4182 I bt_hci  : start_up
,07-28 12:33:20.273  4169  4182 I bt_vendor: alloc value 0xb3a79189
,07-28 12:33:20.273  4169  4182 I bt_vendor: init
,07-28 12:33:20.274  4169  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:33:20.274  4169  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 12:33:20.382  4169  4182 D bt_hci  : start_up starting async portion
,07-28 12:33:20.383  4169  4189 I bt_hci  : event_finish_startup
07-28 12:33:20.383  4169  4189 I bt_hci_h4: hal_open
,07-28 12:33:20.383  4169  4189 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:33:20.393  4169  4189 I bt_userial_vendor: device fd = 51 open
,07-28 12:33:20.425  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:33:20.457  4169  4189 D bt_hwcfg: Chipset BCM4354A2
,07-28 12:33:20.457  4169  4189 D bt_hwcfg: Target name = [BCM4354A2]
07-28 12:33:20.458  4169  4189 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 12:33:21.114  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:33:21.116  4169  4189 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:33:21.116  4169  4189 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:33:21.233  4169  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:33:21.234  4169  4189 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 12:33:21.264  4169  4189 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:33:21.264  4169  4189 I bt_vendor: firmware callback
07-28 12:33:21.264  4169  4189 I bt_hci  : firmware_config_callback
,07-28 12:33:21.275  4169  4191 I bt_btu  : btu_task pending for preload complete event
,07-28 12:33:21.276  4169  4191 I bt_btu_task: Bluetooth chip preload is complete
07-28 12:33:21.276  4169  4191 I bt_btu  : btu_task received preload complete event
,07-28 12:33:21.286  4169  4191 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:33:21.286  4169  4191 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:33:21.287  4169  4191 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:33:21.287  4169  4191 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:33:21.287  4169  4191 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:33:21.288  4169  4191 I         : BTE_InitTraceLevels -- TRC_A2D
,07-28 12:33:21.288  4169  4191 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:33:21.288  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTM
,07-28 12:33:21.288  4169  4191 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:33:21.289  4169  4191 I         : BTE_InitTraceLevels -- TRC_PAN
,07-28 12:33:21.289  4169  4191 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:33:21.289  4169  4191 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:33:21.289  4169  4191 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:33:21.290  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-28 12:33:21.290  4169  4191 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:33:21.426  4169  4191 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
07-28 12:33:21.426  4169  4191 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,07-28 12:33:21.436  4169  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-28 12:33:21.438  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:33:21.438  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:33:21.441  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:33:21.444  4169  4185 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:33:21.447  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:33:21.447  4169  4185 D bt_hci  : do_postload posting postload work item,
07-28 12:33:21.448  4169  4189 I bt_hci  : event_postload
07-28 12:33:21.448  4169  4189 I bt_vendor: sco_config_cb
07-28 12:33:21.448  4169  4189 I bt_hci  : sco_config_callback postload finished.
,07-28 12:33:21.451  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:21.452  4169  4185 D bt_bte_conf: Device ID record 1 : primary
,07-28 12:33:21.452  4169  4185 D bt_bte_conf:   vendorId            = 000f
07-28 12:33:21.452  4169  4185 D bt_bte_conf:   vendorIdSource      = 0001
,07-28 12:33:21.452  4169  4185 D bt_bte_conf:   product             = 1200
,07-28 12:33:21.452  4169  4185 D bt_bte_conf:   version             = 1436
,07-28 12:33:21.453  4169  4185 D bt_bte_conf:   clientExecutableURL = 
07-28 12:33:21.453  4169  4185 D bt_bte_conf:   serviceDescription  = 
07-28 12:33:21.453  4169  4185 D bt_bte_conf:   documentationURL    = 
,07-28 12:33:21.453  4169  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-28 12:33:21.454  4169  4182 D bt_stack_manager: event_start_up_stack finished
,07-28 12:33:21.455  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-28 12:33:21.456  4169  4181 D BluetoothAdapterProperties: Setting state to 15
,07-28 12:33:21.456  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-28 12:33:21.459  4169  4181 I BluetoothAdapterState: Entering BleOnState
07-28 12:33:21.465  4169  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-28 12:33:21.466  4169  4181 D BluetoothAdapterProperties: Setting state to 11
,07-28 12:33:21.466  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-28 12:33:21.470  4169  4189 I bt_vendor: low_power_mode_cb
,07-28 12:33:21.478  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:21.481  4169  4169 D HeadsetService: Received start request. Starting profile...
,07-28 12:33:21.486  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:21.487  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,07-28 12:33:21.489  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:33:21.489  4169  4169 D HeadsetStateMachine: make
,07-28 12:33:21.497  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
,07-28 12:33:21.497  4169  4169 I bt_bluedroid: get_profile_interface handsfree
,07-28 12:33:21.497  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-28 12:33:21.498  4169  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-28 12:33:21.500  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:21.501  4169  4169 D A2dpService: Received start request. Starting profile...
,07-28 12:33:21.501  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:33:21.502  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,07-28 12:33:21.508  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:33:21.508  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:33:21.508  4169  4169 D A2dpStateMachine: make
,07-28 12:33:21.510  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,07-28 12:33:21.510  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-28 12:33:21.512  4169  4199 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:33:21.513  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:33:21.514  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:21.514  4169  4169 D HidService: Received start request. Starting profile...
07-28 12:33:21.515  4169  4169 I bt_bluedroid: get_profile_interface hidhost
,07-28 12:33:21.515  4169  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
07-28 12:33:21.515  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-28 12:33:21.515  4169  4169 D HidService: setHidService(): set to: null
,07-28 12:33:21.516  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:33:21.517  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
07-28 12:33:21.517  4169  4169 D HealthService: Received start request. Starting profile...
,07-28 12:33:21.519  4169  4169 I bt_bluedroid: get_profile_interface health
,07-28 12:33:21.520  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:33:21.520  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
07-28 12:33:21.521  4169  4169 D PanService: Received start request. Starting profile...
07-28 12:33:21.521  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:33:21.521  4169  4169 I bt_bluedroid: get_profile_interface pan
07-28 12:33:21.522  4169  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:33:21.525  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:21.525  4169  4169 D BluetoothMapService: Received start request. Starting profile...
07-28 12:33:21.525  4169  4169 D BluetoothMapService: start()
,07-28 12:33:21.528  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-28 12:33:21.529  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-28 12:33:21.529  4169  4169 D BluetoothMapAppObserver: createReceiver()
07-28 12:33:21.530  4169  4169 D BluetoothMapAppObserver: initObservers()
07-28 12:33:21.530  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 12:33:21.538  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:21.538  4169  4169 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:21.538  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:33:21.538  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:21.539  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:21.542  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:21.543  4169  4197 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:21.543  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false,
07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isTurningOff()=false
07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isTurningOn()=true
07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:33:21.544  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:33:21.545  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-28 12:33:21.545  4169  4181 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:33:21.545  4169  4181 D BluetoothAdapterProperties: State =  11
07-28 12:33:21.549  4169  4185 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:33:21.549  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:33:21.549  4169  4181 D BluetoothAdapterProperties: Setting state to 12
,07-28 12:33:21.549  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:33:21.550  4169  4181 I BluetoothAdapterState: Entering OnState
07-28 12:33:21.550  1373  1386 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:33:21.553  1373  1845 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:21.554  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:21.556   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.556  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 12:33:21.556  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:21.556  3867  3879 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.557   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.557  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-28 12:33:21.557  1373  1847 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:33:21.559  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:33:21.560  1373  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.561  3867  3877 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:33:21.561  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:33:21.563  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
,07-28 12:33:21.563  4169  4169 D ObexServerSockets0: startAccept()
07-28 12:33:21.563  4169  4169 D ObexServerSockets0: prepareForNewConnect()
07-28 12:33:21.563  1373  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:33:21.566  3867  4149 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:33:21.567  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-28 12:33:21.567  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-28 12:33:21.568  4169  4206 D ObexServerSockets0: Accepting socket connection...
07-28 12:33:21.568  4169  4205 D ObexServerSockets0: Accepting socket connection...
07-28 12:33:21.568  1373  1845 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:33:21.569  3867  3867 D BluetoothA2dp: Proxy object connected
07-28 12:33:21.569  1373  1373 D BluetoothA2dp: Proxy object connected
,07-28 12:33:21.571   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:33:21.572  3867  3867 D BluetoothInputDevice: Proxy object connected
,07-28 12:33:21.572  1373  1373 D BluetoothMap: Proxy object connected
07-28 12:33:21.572  1373  1373 D MapProfile: Bluetooth service connected
07-28 12:33:21.572  3867  3867 D HidProfile: Bluetooth service connected
07-28 12:33:21.572  1373  1373 D BluetoothMap: getConnectedDevices()
07-28 12:33:21.572   874   874 D BluetoothA2dp: Proxy object connected
,07-28 12:33:21.572   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.572  3867  4149 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:33:21.573  1373  1373 D BluetoothInputDevice: Proxy object connected
07-28 12:33:21.573  1373  1373 D HidProfile: Bluetooth service connected
,07-28 12:33:21.574  3867  3877 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:33:21.575  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:33:21.575  1373  1373 D PanProfile: Bluetooth service connected
07-28 12:33:21.577  1753  1764 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:33:21.577  3867  3867 D BluetoothMap: Proxy object connected
,07-28 12:33:21.577  3867  3867 D MapProfile: Bluetooth service connected
07-28 12:33:21.577  3867  3879 D BluetoothPan: onBluetoothStateChange on: true
,07-28 12:33:21.577  3867  3867 D BluetoothMap: getConnectedDevices()
,07-28 12:33:21.579   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 12:33:21.581  4169  4169 D BluetoothMapService: onReceive
,07-28 12:33:21.581  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:33:21.581  4169  4169 D BluetoothMapService: STATE_ON,
,07-28 12:33:21.582  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:21.583  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:33:21.583  3867  3867 D PanProfile: Bluetooth service connected
,07-28 12:33:21.590  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:33:21.596  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:33:21.600  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:33:21.604  3867  3867 D BluetoothPbap: Proxy object connected
,07-28 12:33:21.604  3867  3867 D PbapServerProfile: Bluetooth service connected
,07-28 12:33:21.606  1373  1373 D BluetoothPbap: Proxy object connected
07-28 12:33:21.606  1373  1373 D PbapServerProfile: Bluetooth service connected
,07-28 12:33:21.612  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 12:33:21.612  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,07-28 12:33:21.615  4169  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:33:21.635  4169  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:33:21.637  4169  4215 I BtOppRfcommListener: Accept thread started.
,07-28 12:33:21.657  3867  3879 D BluetoothHeadset: Proxy object connected
,07-28 12:33:21.657  3867  3867 D HeadsetProfile: Bluetooth service connected
07-28 12:33:21.657   874   874 D BluetoothHeadset: Proxy object connected
,07-28 12:33:21.657  3867  4149 D BluetoothHeadset: Proxy object connected
07-28 12:33:21.657  1753  1928 D BluetoothHeadset: Proxy object connected
07-28 12:33:21.658   874   891 D BluetoothHeadset: Proxy object connected
07-28 12:33:21.658   874   874 D BluetoothHeadset: Proxy object connected
07-28 12:33:21.658  1373  1847 D BluetoothHeadset: Proxy object connected
,07-28 12:33:21.658  1373  1373 D HeadsetProfile: Bluetooth service connected
07-28 12:33:21.659   874   874 D BluetoothHeadset: Proxy object connected
,07-28 12:33:21.661  3867  3867 D HeadsetProfile: Bluetooth service connected
,07-28 12:33:21.661  1373  1384 D BluetoothHeadset: Proxy object connected
07-28 12:33:21.662  1373  1373 D HeadsetProfile: Bluetooth service connected
,07-28 12:33:21.673   874   891 D BluetoothHeadset: Proxy object connected
,07-28 12:33:21.677  1753  1765 D BluetoothHeadset: Proxy object connected
,07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:22.014  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:22.021  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:22.025  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:33:22.026  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33376b1 added. We now have 8 listener(s)
07-28 12:33:22.026  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:33:22.031   874  1773 D WifiService: setWifiEnabled: false pid=3810, uid=10000
,07-28 12:33:22.032   874  1773 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:33:22.044  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:22.045   874  1761 D WifiService: setWifiEnabled: true pid=3810, uid=10000
07-28 12:33:22.046   874  1761 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:33:22.062   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:22.079  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:22.084  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:22.095   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,07-28 12:33:22.095   874  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:33:22.096   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-28 12:33:22.097   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-28 12:33:22.098   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:33:22.098   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-28 12:33:22.098   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-28 12:33:22.098   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 12:33:22.110   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-28 12:33:22.110   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:33:22.111   372   872 D CommandListener: Setting iface cfg
07-28 12:33:22.112   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-28 12:33:22.112   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:33:22.167   874  1315 E native  : do suspend true
,07-28 12:33:22.181   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:33:22.182   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-28 12:33:22.203   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:23.068  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:23.076  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:23.090  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 12:33:23.092  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 12:33:23.097  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4cab2e4 Bundle[{}]
,07-28 12:33:23.099  3810  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:33:23.099  3810  3861 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-28 12:33:23.101  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-28 12:33:23.102  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-28 12:33:23.104  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:33:23.106  3810  3861 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:33:23.114  3810  3861 I System.out: Running OutgoingSocketThread
,07-28 12:33:23.117  3810  4221 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 447)
,07-28 12:33:23.119  3810  4221 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44336
07-28 12:33:23.119  3810  4221 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 12:33:23.606   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:33:23.730   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.25 rxSuccessRate=12.56 delta 1000 -> 994
07-28 12:33:23.731   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-28 12:33:23.731   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:33:23.750   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 12:33:23.821   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 12:33:23.823  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 12:33:24.117  3810  3861 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 448)
07-28 12:33:24.117  3810  3861 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 448)
,07-28 12:33:24.127  3810  3861 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,07-28 12:33:24.129  3810  3861 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-28 12:33:24.130  3810  3861 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,07-28 12:33:24.136  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.136  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f9a796 added. We now have 2 listener(s)
,07-28 12:33:24.138  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.138  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.138  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:33:24.139  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.139  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7603f17 added. We now have 9 listener(s)
07-28 12:33:24.139  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.140  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:33:24.144  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:24.150  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:24.154  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:24.154  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:24.155  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.155  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.156  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7cced added. We now have 3 listener(s)
,07-28 12:33:24.157  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:33:24.161  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.162  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.162  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:33:24.163  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.163  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa0a722 added. We now have 10 listener(s)
07-28 12:33:24.163  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.164  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:24.164  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:24.164  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:24.165  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.165  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.165  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:24.165  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.166  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f9a796 removed from the list
07-28 12:33:24.166  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.166  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7603f17 removed from the list
07-28 12:33:24.166  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:24.167  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.168  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.168  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.171  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:24.171  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.171  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.172  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7603f17 not in the list
07-28 12:33:24.172  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.172  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.174  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:33:24.174  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.175  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.175  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa0a722 removed from the list
07-28 12:33:24.175  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.175  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.176  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.176  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.176  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7cced removed from the list
,07-28 12:33:24.179  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.179  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9fb5b3 added. We now have 2 listener(s)
,07-28 12:33:24.181  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:33:24.181  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.181  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.181  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.181  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcf1770 added. We now have 9 listener(s)
,07-28 12:33:24.181  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.182  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:33:24.185  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:24.188  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:33:24.192  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:33:24.192  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:33:24.192  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.192  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c6136e added. We now have 3 listener(s)
,07-28 12:33:24.193  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.195  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.195  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.195  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:33:24.196  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.196  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.196  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755fa0f added. We now have 10 listener(s)
07-28 12:33:24.196  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.196  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:24.196  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,07-28 12:33:24.196  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:33:24.196  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.197  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:33:24.199  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:33:24.199  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:33:24.204  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:33:24.204  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:33:24.204  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:33:24.209  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:33:24.209  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:24.209  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:33:24.209  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:24.213  4169  4180 D BtGatt.GattService: registerClient() - UUID=b2d89e63-3dff-4670-95d8-fa42be528aea
,07-28 12:33:24.214  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=b2d89e63-3dff-4670-95d8-fa42be528aea, clientIf=5
,07-28 12:33:24.215  3810  3821 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:33:24.217  4169  4207 D BtGatt.GattService: start scan with filters
,07-28 12:33:24.221  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:33:24.221  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:33:24.221  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:33:24.222  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 12:33:24.222  4169  4188 D BtGatt.ScanManager: handling starting scan
07-28 12:33:24.224  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:33:24.224  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:33:24.225  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:24.226  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:33:24.226  4169  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a631b38
,07-28 12:33:24.228  3810  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-28 12:33:24.229  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:33:24.229  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,07-28 12:33:24.229  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.229  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 12:33:24.229  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:33:24.229  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:24.229  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 12:33:24.229  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:24.229  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:33:24.229  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 12:33:24.230  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:24.231  4169  4207 D BtGatt.GattService: stopScan() - queue size =1
07-28 12:33:24.232  4169  4204 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:24.232  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:33:24.233  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-28 12:33:24.234  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-28 12:33:24.234  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:33:24.234  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 12:33:24.235  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 12:33:24.234  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.237  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 12:33:24.238  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:24.239  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:33:24.241  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:33:24.239  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:24.243  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:33:24.245  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:24.247  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 12:33:24.247  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:24.247  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:24.250  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:33:24.250  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:33:24.251  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:33:24.251  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:24.251  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.252  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:24.252  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:33:24.252  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9fb5b3 removed from the list
07-28 12:33:24.252  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:24.252  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcf1770 removed from the list
07-28 12:33:24.252  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:24.252  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.253  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:24.253  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.255  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:24.255  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:33:24.255  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:33:24.255  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcf1770 not in the list
,07-28 12:33:24.255  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:24.255  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.255  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-28 12:33:24.255  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.256  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.256  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:24.256  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:33:24.256  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:33:24.256  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.256  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755fa0f removed from the list
07-28 12:33:24.256  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:24.256  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.256  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.256  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.256  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c6136e removed from the list
07-28 12:33:24.257  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.257  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@882282b added. We now have 2 listener(s)
,07-28 12:33:24.259  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.259  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.259  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.259  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.260  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea6488 added. We now have 9 listener(s)
07-28 12:33:24.260  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.260  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:33:24.263  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:24.266  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:24.268  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:24.268  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:24.269  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.269  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d892246 added. We now have 3 listener(s)
07-28 12:33:24.270  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.271  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.271  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:33:24.271  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.271  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.272  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.272  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f91c07 added. We now have 10 listener(s)
07-28 12:33:24.271  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:33:24.272  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.272  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:33:24.272  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-28 12:33:24.273  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:24.274  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:33:24.274  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:33:24.274  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.274  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:33:24.274  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:33:24.274  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.275   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
07-28 12:33:24.278  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:33:24.279  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:33:24.280  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:24.280  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.281  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:33:24.284  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 12:33:24.284   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:33:24.284  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:33:24.284   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:33:24.285   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-28 12:33:24.288  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 12:33:24.288  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 12:33:24.288  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.288  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:24.288  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 12:33:24.288  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:33:24.288  3810  3861 D BluetoothAdapter: STATE_ON
,07-28 12:33:24.290  4169  4180 D BtGatt.GattService: registerClient() - UUID=44eb624b-d119-4abb-8aaa-ec69fbcb73d4
07-28 12:33:24.290  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=44eb624b-d119-4abb-8aaa-ec69fbcb73d4, clientIf=5
07-28 12:33:24.291  3810  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 12:33:24.291  4169  4179 D BtGatt.GattService: start scan with filters
,07-28 12:33:24.294  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:33:24.294  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 12:33:24.294  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-28 12:33:24.294  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:24.294  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-28 12:33:24.294  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 12:33:24.294  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:33:24.296  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:33:24.296  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
07-28 12:33:24.296  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:33:24.297  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 12:33:24.298   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:33:24.300  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:33:24.300  3810  3861 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-28 12:33:24.300  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:33:24.300  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:24.300  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:24.300  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:24.300  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:24.301  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:33:24.301  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.301  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:33:24.301  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.301  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@882282b removed from the list
,07-28 12:33:24.301  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.301  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea6488 removed from the list
07-28 12:33:24.301  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:33:24.301  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:24.302  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.302  4169  4188 D BtGatt.ScanManager: handling starting scan
07-28 12:33:24.302  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-28 12:33:24.302  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:24.302  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.303  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea6488 not in the list
,07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:24.303  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:24.303  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 12:33:24.303  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:33:24.303  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:24.304  4169  4207 D BtGatt.GattService: stopScan() - queue size =1
07-28 12:33:24.304  4169  4204 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:24.305  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:33:24.305  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:33:24.306  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:33:24.306  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:33:24.306  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:33:24.306   372   872 D CommandListener: Setting iface cfg
07-28 12:33:24.306   874  1315 D WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:33:24.306  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:33:24.307  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:33:24.307  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:24.307  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:33:24.307  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.307  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 12:33:24.307  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.308  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:33:24.308  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.308  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.308  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.308  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f91c07 removed from the list
07-28 12:33:24.308  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-28 12:33:24.308  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:24.308  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.308  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:24.308  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:33:24.308  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.308  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:24.308  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d892246 removed from the list
07-28 12:33:24.309  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.309  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90171a3 added. We now have 2 listener(s)
07-28 12:33:24.310  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:33:24.310  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.310  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.310  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.310  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4f3ca0 added. We now have 9 listener(s)
07-28 12:33:24.310  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:33:24.310  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:33:24.313  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.313   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
07-28 12:33:24.313  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:33:24.313  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.313  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:24.313  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:24.315  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:24.317  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:24.317  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:24.317  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.317  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114341e added. We now have 3 listener(s)
07-28 12:33:24.318  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.318  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:33:24.319  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.319  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.319  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.319  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaf84ff added. We now have 10 listener(s)
07-28 12:33:24.319  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.319  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.319  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:33:24.319  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:33:24.319  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:33:24.319  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.319  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:33:24.321  3810  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:33:24.321  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:33:24.322  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:33:24.322  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:33:24.323  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:33:24.324  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:33:24.324  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:33:24.326  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 12:33:24.326  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:33:24.326  3810  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:33:24.326  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:24.327  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:24.327  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.327  4169  4179 D BtGatt.GattService: registerClient() - UUID=0825e3cb-4a59-4f5d-9959-ee53f7a4e228
07-28 12:33:24.328  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=0825e3cb-4a59-4f5d-9959-ee53f7a4e228, clientIf=5
07-28 12:33:24.328  3810  3820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:33:24.328  4169  4207 D BtGatt.GattService: start scan with filters
07-28 12:33:24.330  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 12:33:24.330  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:33:24.330  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:33:24.330  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 12:33:24.332  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:33:24.332  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:33:24.332  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:33:24.333  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 12:33:24.333  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:33:24.333  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.333  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:33:24.335   874  4224 D DhcpClient: Receive thread started
07-28 12:33:24.336  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:24.336  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:24.336  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:24.336  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.336  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.336  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:33:24.336  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.336  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90171a3 removed from the list
07-28 12:33:24.336  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.336  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4f3ca0 removed from the list
07-28 12:33:24.336  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:24.336  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:24.337  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.337  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-28 12:33:24.337  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.337  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:24.337  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.337  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.337  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.338  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4f3ca0 not in the list
07-28 12:33:24.338  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:33:24.338  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:33:24.338  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:33:24.338  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:33:24.338  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:33:24.338  3810  3861 D BluetoothAdapter: STATE_ON
07-28 12:33:24.338  4169  4207 D BtGatt.GattService: stopScan() - queue size =0
07-28 12:33:24.339  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:33:24.339  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.339  4169  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:33:24.339  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 12:33:24.339  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:33:24.339  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:33:24.339  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:33:24.339  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:33:24.339  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 12:33:24.340  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:24.340  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:33:24.340  3810  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:33:24.340  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:33:24.340  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.341  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.341  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.341  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.341  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaf84ff removed from the list
07-28 12:33:24.341  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.341  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:24.341  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.341  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.341  3810  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:33:24.341  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.341  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114341e removed from the list
07-28 12:33:24.341  3810  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:33:24.342  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.342  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f01721b added. We now have 2 listener(s)
07-28 12:33:24.343  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.343  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.343  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.343  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.343  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43ffb8 added. We now have 9 listener(s)
07-28 12:33:24.343  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.343  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:33:24.344  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:33:24.344  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.345  4169  4188 D BtGatt.ScanManager: handling starting scan
07-28 12:33:24.345  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:33:24.347  3810  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:33:24.348  3810  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:33:24.348  3810  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:33:24.348  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:33:24.348  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a04a8f6 added. We now have 3 listener(s)
07-28 12:33:24.349  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.349  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:33:24.350  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:33:24.350  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:33:24.350  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:33:24.350  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb14f7 added. We now have 10 listener(s)
07-28 12:33:24.350  3810  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:33:24.350  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 12:33:24.350  3810  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:33:24.350  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.350  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:24.350  3810  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:33:24.350  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.350  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.350  4169  4188 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 12:33:24.350  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:33:24.350  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.350  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f01721b removed from the list
07-28 12:33:24.350  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:33:24.350  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.350  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43ffb8 removed from the list
07-28 12:33:24.351  3810  3861 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:33:24.351  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.351  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.351  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.352  3810  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43ffb8 not in the list
07-28 12:33:24.352  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:33:24.352  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:33:24.352  3810  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb14f7 removed from the list
07-28 12:33:24.352  3810  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:33:24.352  3810  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:33:24.352  3810  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:33:24.353  3810  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:33:24.353  3810  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a04a8f6 removed from the list
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:33:24.353  3810  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:33:24.355  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:33:24.355  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.355  4169  4188 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:33:24.355  4169  4188 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:33:24.358  3810  4225 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
07-28 12:33:24.359  3810  4225 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
07-28 12:33:24.359  3810  4225 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
07-28 12:33:24.360  3810  4226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
07-28 12:33:24.360  3810  4226 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
07-28 12:33:24.361  3810  4226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
07-28 12:33:24.362  3810  3861 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:33:24.362  3810  3861 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:33:24.362  3810  3861 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:33:24.362  3810  3861 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 12:33:24.362  3810  3861 D com.test.thalitest.ThaliTestRunner: Total duration: 22834 ms
07-28 12:33:24.364  3810  3861 I jxcore-log: Total number of executed tests:  80
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  3810  3861 I jxcore-log: Number of passed tests:  80
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  3810  3861 I jxcore-log: Number of failed tests:  0
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  3810  3861 I jxcore-log: Number of ignored tests:  0
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  3810  3861 I jxcore-log: Total duration:  22834
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  3810  3861 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:33:24.364  3810  3861 I jxcore-log: 
07-28 12:33:24.364  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:33:24.364  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.366  3810  3861 I jxcore-log: Unit Test app is loaded
07-28 12:33:24.366  3810  3861 I jxcore-log: 
07-28 12:33:24.369  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:33:24.370  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.374  3810  3810 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:33:24.376  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:33:24.376  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.376  4169  4188 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:33:24.377  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.377  3810  3861 I jxcore-log: 
07-28 12:33:24.382  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:33:24.382  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.383  4169  4188 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 12:33:24.383  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.383  3810  3861 I jxcore-log: 
07-28 12:33:24.384  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.384  3810  3861 I jxcore-log: 
07-28 12:33:24.385  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.385  3810  3861 I jxcore-log: 
07-28 12:33:24.387  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.387  3810  3861 I jxcore-log: 
07-28 12:33:24.389  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.389  3810  3861 I jxcore-log: 
07-28 12:33:24.392  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-28 12:33:24.392  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:33:24.392  4169  4185 D BtGatt.GattService: current time is 321521244330
07-28 12:33:24.392  4169  4185 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
07-28 12:33:24.393  4169  4185 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
07-28 12:33:24.394  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.394  3810  3861 I jxcore-log: 
07-28 12:33:24.396  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.396  3810  3861 I jxcore-log: 
07-28 12:33:24.396  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.396  3810  3861 I jxcore-log: 
07-28 12:33:24.397  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.397  3810  3861 I jxcore-log: 
,07-28 12:33:24.398  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.398  3810  3861 I jxcore-log: 
07-28 12:33:24.399  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:33:24.399  3810  3861 I jxcore-log: 
07-28 12:33:24.400  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.400  3810  3861 I jxcore-log: 
07-28 12:33:24.401  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.401  3810  3861 I jxcore-log: 
07-28 12:33:24.402  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.402  3810  3861 I jxcore-log: 
07-28 12:33:24.402  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:33:24.402  3810  3861 I jxcore-log: 
07-28 12:33:24.403  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.403  3810  3861 I jxcore-log: 
07-28 12:33:24.404  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.404  3810  3861 I jxcore-log: 
07-28 12:33:24.405  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.405  3810  3861 I jxcore-log: 
07-28 12:33:24.405  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.405  3810  3861 I jxcore-log: 
07-28 12:33:24.406  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.406  3810  3861 I jxcore-log: 
07-28 12:33:24.406  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.406  3810  3861 I jxcore-log: 
07-28 12:33:24.407  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.407  3810  3861 I jxcore-log: 
07-28 12:33:24.408  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:33:24.408  3810  3861 I jxcore-log: 
07-28 12:33:24.409  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.409  3810  3861 I jxcore-log: 
07-28 12:33:24.409  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.409  3810  3861 I jxcore-log: 
07-28 12:33:24.410  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.410  3810  3861 I jxcore-log: 
07-28 12:33:24.411  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.411  3810  3861 I jxcore-log: 
07-28 12:33:24.411  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.411  3810  3861 I jxcore-log: 
07-28 12:33:24.412  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.412  3810  3861 I jxcore-log: 
07-28 12:33:24.413  3810  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:33:24.413  3810  3861 I jxcore-log: 
07-28 12:33:24.417  3810  3861 I jxcore-log: My device name is: motorola-Nexus 6
07-28 12:33:24.417  3810  3861 I jxcore-log: 
,07-28 12:33:24.419   874  1315 E native  : do suspend false
,07-28 12:33:24.430   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,07-28 12:33:24.459   874  4224 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,07-28 12:33:24.460   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,07-28 12:33:24.460   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-28 12:33:24.472   874  4224 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
07-28 12:33:24.473   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-28 12:33:24.475   372   872 D CommandListener: Setting iface cfg
,07-28 12:33:24.479   874  2102 D DhcpClient: Scheduling renewal in 86399s
,07-28 12:33:24.485   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-28 12:33:24.488   874  1315 E native  : do suspend true
,07-28 12:33:24.500   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 12:33:24.502   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 12:33:24.502   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-28 12:33:24.503   874  1317 D ConnectivityService: Adding iface wlan0 to network 102
,07-28 12:33:24.507   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:33:24.540   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-28 12:33:24.540   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-28 12:33:24.541   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-28 12:33:24.542   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-28 12:33:24.543   874  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-28 12:33:24.552   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-28 12:33:24.558   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-28 12:33:24.558   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,07-28 12:33:24.558   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-28 12:33:24.559   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:33:24.559   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-28 12:33:24.559   874  1317 D ConnectivityService:    accepting network in place of null
,07-28 12:33:24.561   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:33:24.568   874  4223 D NetlinkSocketObserver: NeighborEvent{elapsedMs=321696, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 12:33:24.595   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:24.612   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:33:24.614   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-28 12:33:24.614   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:24.615   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:33:24.619   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:33:24.620  3810  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:33:24.621  3810  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:33:24.636  1781  1781 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:33:24.641  1781  1781 D SystemUpdateService: onCreate
07-28 12:33:24.643  1781  1781 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
07-28 12:33:24.654   874  4222 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.238,2a00:1450:4001:802::200e
,07-28 12:33:24.665  1781  1781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 12:33:24.673  1781  4239 I SystemUpdateService: active receiver: enabled
,07-28 12:33:24.691  1781  2370 I iu.UploadsManager: num queued entries: 0
,07-28 12:33:24.719   874  4222 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:33:24 GMT], X-Android-Received-Millis=[1469702004719], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469702004695]}
,07-28 12:33:24.720   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-28 12:33:24.720   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-28 12:33:24.721   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:33:24.721   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:33:24.737  1781  1781 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 12:33:24.738  1781  1781 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:33:24.745  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:33:24.748  3810  3810 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:33:24.748  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:33:24.752  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:33:24.754  3959  3959 D SprintDMHelper: simOperator: 
,07-28 12:33:24.754  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 12:33:24.791  1781  4242 I MDM     : [213] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-28 12:33:24.791  1781  4242 W BaseAppContext: Using Auth Proxy for data requests.
,07-28 12:33:24.793  1781  4242 V GoogleAuthProtoRequest: [213] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 12:33:24.801  1506  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 12:33:24.801  1506  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 12:33:24.802  1506  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:33:24.802  1506  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:33:24.808  3810  3810 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:33:24.814  3495  4241 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-28 12:33:24.814  3495  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jdm.a(PG:82)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jcs.o(PG:406)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jcn.a(PG:1379)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jcs.i(PG:143)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at blb.a(PG:3937)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at czp.a(PG:18188)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at czp.a(PG:9081)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at czq.run(PG:1686)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:33:24.814  3495  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jdj.a(PG:4091)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jdj.a(PG:1125)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jdm.a(PG:77)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	... 12 more
07-28 12:33:24.814  3495  4241 E HttpOperation: Caused by: faj: BadAuthentication
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at fal.a(PG:38)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	at jdj.a(PG:4089)
07-28 12:33:24.814  3495  4241 E HttpOperation: 	... 14 more
,07-28 12:33:24.842  3810  3810 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:33:24.850  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 12:33:24.850  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 12:33:24.850  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:33:24.850  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:33:24.864  3495  4241 E HttpOperation: [getmobileexperiments] Unexpected exception
07-28 12:33:24.864  3495  4241 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jdm.a(PG:82)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jcs.o(PG:406)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jcn.a(PG:1379)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jcs.i(PG:143)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at hec.a(PG:42)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at hee.a(PG:102)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at czr.a(PG:65)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at kka.a(PG:108)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at czp.a(PG:19176)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at czp.a(PG:9081)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at czq.run(PG:1686)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:33:24.864  3495  4241 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jdj.a(PG:4091)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jdj.a(PG:1125)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jdm.a(PG:77)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	,... 15 more
07-28 12:33:24.864  3495  4241 E HttpOperation: Caused by: faj: BadAuthentication
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at fal.a(PG:38)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	at jdj.a(PG:4089)
07-28 12:33:24.864  3495  4241 E HttpOperation: 	... 17 more
,07-28 12:33:24.864  3495  4241 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-28 12:33:24.864  3495  4241 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jdm.a(PG:82)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jcs.o(PG:406)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jcn.a(PG:1379)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jcs.i(PG:143)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at hec.a(PG:42)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at hee.a(PG:102)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at czr.a(PG:65)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at kka.a(PG:108)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at czp.a(PG:19176)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at czp.a(PG:9081)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at czq.run(PG:1686)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
,07-28 12:33:24.864  3495  4241 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jdj.a(PG:4091)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jdj.a(PG:1125)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jdm.a(PG:77)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	... 15 more
07-28 12:33:24.864  3495  4241 E ExperimentLoader: Caused by: faj: BadAuthentication
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at fal.a(PG:38)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	at jdj.a(PG:4089)
07-28 12:33:24.864  3495  4241 E ExperimentLoader: 	... 17 more
,07-28 12:33:24.874  1781  2370 I iu.UploadsManager: num updated entries: 0,
,07-28 12:33:24.894  1781  4239 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:33:24.911  1781  2370 I iu.SyncManager: NEXT; no task
,07-28 12:33:24.940  1781  4239 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-28 12:33:24.940  1781  4239 I SystemUpdateService: now status is 0 (complete)
07-28 12:33:24.940  1781  4239 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-28 12:33:24.940  1781  4239 I SystemUpdateService: file has been verified
07-28 12:33:24.940  1781  4239 I SystemUpdateService: OTA package size = 12249756
,07-28 12:33:24.986  1781  4239 I SystemUpdateService: showing system update notification
,07-28 12:33:24.991   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 320260, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
07-28 12:33:24.994  3916  4246 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 12:33:25.018  1506  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-28 12:33:25.018  1506  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 12:33:25.018  1506  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:33:25.018  1506  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:33:25.034  1781  4242 E MDM     : [213] SitrepService.a: Error sending sitrep.
,07-28 12:33:25.038  1781  1781 D SystemUpdateService: onDestroy
,07-28 12:33:25.056  4227  4227 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-28 12:33:25.060  4227  4227 D AndroidRuntime: CheckJNI is OFF
,07-28 12:33:25.092  4227  4227 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-28 12:33:25.126  4227  4227 I Radio-JNI: register_android_hardware_Radio DONE
,07-28 12:33:25.146  4227  4227 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:33:25.155   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-28 12:33:25.156   874   887 I ActivityManager: Killing 3810:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,07-28 12:33:25.233   874   898 W PackageSettings: Skipping PackageSetting{f63d8a5 com.example.hello/10273} due to missing metadata
,07-28 12:33:25.260   874   884 D GraphicsStats: Buffer count: 2
,07-28 12:33:25.260   874   884 I WindowState: WIN DEATH: Window{f2cf6f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:33:25.261   874  1316 D WifiService: Client connection lost with reason: 4
07-28 12:33:25.264   874   898 I art     : Starting a blocking GC Explicit
,07-28 12:33:25.291   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,07-28 12:33:25.292   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,07-28 12:33:25.294   874   887 E ActivityManager: Failure starting process com.test.thalitest
07-28 12:33:25.294   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
,07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-28 12:33:25.294   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.294   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.294   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:33:25.294   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 12:33:25.296   874   887 I ActivityManager:   Force finishing activity ActivityRecord{9456945 u0 com.test.thalitest/.MainActivity t2}
,07-28 12:33:25.305   874  1761 W ActivityManager: Spurious death for ProcessRecord{e79d2b1 0:com.test.thalitest/u0a0}, curProc for 3810: null
,07-28 12:33:25.325   874   898 I art     : Explicit concurrent mark sweep GC freed 33187(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 700us total 60.326ms
,07-28 12:33:25.346   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-28 12:33:25.351  4227  4227 I art     : System.exit called, status: 0
07-28 12:33:25.351  4227  4227 I AndroidRuntime: VM exiting with result code 0.
,07-28 12:33:25.368   874   898 I ActivityManager: Start proc 4261:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,07-28 12:33:25.368   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-28 12:33:25.390   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,07-28 12:33:25.394  4169  4169 D BluetoothMapAppObserver: onReceive
07-28 12:33:25.394  4169  4169 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-28 12:33:25.397  1665  1665 I Keyboard.Facilitator: resetDictionaries() : en_US
07-28 12:33:25.398  3616  3616 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,07-28 12:33:25.409  1852  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 12:33:25.410   874  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:33:25.424   874  1399 I ActivityManager: Start proc 4276:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-28 12:33:25.430  1665  4273 I Keyboard.Facilitator.DecoderInitializer: run()
,07-28 12:33:25.432  1665  4273 I Decoder : createOrResetDecoder
,07-28 12:33:25.465  1753  1753 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-28 12:33:25.483   874  1313 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,07-28 12:33:25.494  1506  1506 I ConfigService: onCreate
,07-28 12:33:25.505   874  1399 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3810 uid 10000
,07-28 12:33:25.506  1665  1665 I Keyboard.Facilitator: onFinishInput()
,07-28 12:33:25.527   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 12:33:25.541  1766  1851 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,07-28 12:33:25.541   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-28 12:33:25.542   874   886 E PackageManager: Failed to write settings, restoring backup
07-28 12:33:25.542   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-28 12:33:25.542   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-28 12:33:25.542   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-28 12:33:25.542   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-28 12:33:25.542   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-28 12:33:25.542   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.542   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.542   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-28 12:33:25.540  1506  4289 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-28 12:33:25.542  1506  4289 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,07-28 12:33:25.546   874   887 E DropBoxManagerService: Can't write: system_server_wtf
07-28 12:33:25.546   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 12:33:25.546   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:25.546   874   887 E DropBoxManagerService: 	... 13 more
,07-28 12:33:25.554  1506  4289 W SQLiteOpenHelper: Opened config.db in read-only mode
,07-28 12:33:25.554   874  1385 I ActivityManager: Start proc 4290:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService,
,--------- beginning of crash
07-28 12:33:25.555  1766  1851 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-28 12:33:25.555  1766  1851 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1766
07-28 12:33:25.555  1766  1851 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.555  1766  1851 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 12:33:25.556  4276  4276 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-28 12:33:25.557   874  3081 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 12:33:25.558   874  4296 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:33:25.558   874  4296 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:25.558   874  4296 E DropBoxManagerService: 	... 5 more
,07-28 12:33:25.561  1766  1851 I Process : Sending signal. PID: 1766 SIG: 9
,07-28 12:33:25.591  1665  4273 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-28 12:33:25.629  1665  4273 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-28 12:33:25.632  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-28 12:33:25.632  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-28 12:33:25.633  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-28 12:33:25.633  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-28 12:33:25.634  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,07-28 12:33:25.634  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,07-28 12:33:25.635  1665  4273 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-28 12:33:25.636  1665  4273 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,07-28 12:33:25.636  1665  4273 I Keyboard.Facilitator.Delight2FileSweeper: run()
,07-28 12:33:25.638  1665  4273 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-28 12:33:25.638  1665  4273 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-28 12:33:25.638  1665  4273 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-28 12:33:25.649   874  1687 D GraphicsStats: Buffer count: 1
07-28 12:33:25.649   874   884 I WindowState: WIN DEATH: Window{a7d1cb5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,07-28 12:33:25.661   874  1716 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1766) has died
,07-28 12:33:25.661   874  1716 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
07-28 12:33:25.663   874  1716 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-28 12:33:25.682   874   887 I ActivityManager: Start proc 4310:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 12:33:25.690  4276  4276 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-28 12:33:25.704  1781  4309 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,07-28 12:33:25.704  1781  4309 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,07-28 12:33:25.707  4276  4322 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-28 12:33:25.716   874  1399 I ActivityManager: Start proc 4323:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,07-28 12:33:25.723  4276  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.723  4276  4322 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-28 12:33:25.723  4276  4322 E AndroidRuntime: Process: android.process.acore, PID: 4276
07-28 12:33:25.723  4276  4322 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.723  4276  4322 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.723  4276  4322 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694),
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:25.724  4310  4310 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:25.724  4310  4310 D AndroidRuntime: Shutting down VM
07-28 12:33:25.727  4276  4322 I Process : Sending signal. PID: 4276 SIG: 9
07-28 12:33:25.730   874  4334 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:33:25.730   874  4334 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:25.730   874  4334 E DropBoxManagerService: 	... 5 more
07-28 12:33:25.734  4310  4310 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:33:25.734  4310  4310 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4310
07-28 12:33:25.734  4310  4310 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:33:25.734  4310  4310 E AndroidRuntime: 	... 10 more
07-28 12:33:25.735   874  1692 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:33:25.736  4310  4310 I Process : Sending signal. PID: 4310 SIG: 9
07-28 12:33:25.736   874  4336 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:33:25.736   874  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:25.736   874  4336 E DropBoxManagerService: 	... 5 more
07-28 12:33:25.748  1781  4309 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-28 12:33:25.748  1781  4309 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-28 12:33:25.753  4323  4323 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-28 12:33:25.769  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-28 12:33:25.770   281   281 E lowmemorykiller: Error writing /proc/4276/oom_score_adj; errno=22
07-28 12:33:25.770   281   281 E lowmemorykiller: Error writing /proc/4276/oom_score_adj; errno=22
07-28 12:33:25.771  1506  1506 D AndroidRuntime: Shutting down VM
07-28 12:33:25.772  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:33:25.772  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
07-28 12:33:25.772  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-28 12:33:25.772  1506  1506 E AndroidRuntime: 	... 8 more
07-28 12:33:25.774   874  4340 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:33:25.774   874  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:33:25.774   874  4340 E DropBoxManagerService: 	... 5 more
07-28 12:33:25.775  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
07-28 12:33:25.787   874  1687 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4310) has died
07-28 12:33:25.788   874  1687 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-28 12:33:25.801   874   887 I ActivityManager: Start proc 4341:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:33:25.803   874  1385 I ActivityManager: Killing 3727:com.google.android.deskclock/u0a44 (adj 15): empty #17
07-28 12:33:25.816   874  1316 D WifiService: Client connection lost with reason: 4
,07-28 12:33:25.836  3495  3495 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
07-28 12:33:25.836   874  1692 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
07-28 12:33:25.836   874  1692 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
07-28 12:33:25.836   874  1692 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
07-28 12:33:25.836   874  1692 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
07-28 12:33:25.836   874  1692 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
07-28 12:33:25.838   874   885 I ActivityManager: Process android.process.acore (pid 4276) has died
,07-28 12:33:25.838   874   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40998ms
07-28 12:33:25.840  1781  1781 W RocketImpressions: ClearcutLogger connection suspended: 1
07-28 12:33:25.853   874  3081 I ActivityManager: Start proc 4353:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,07-28 12:33:25.863  4341  4341 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:33:25.863  4341  4341 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:33:25.863  4341  4341 D AndroidRuntime: Shutting down VM

```
