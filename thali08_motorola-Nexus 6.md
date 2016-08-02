#### Test 796897750e9b555_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-02 13:47:25.775  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:25.785  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-02 13:47:25.790  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-02 13:47:25.813  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-02 13:47:25.813  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:47:25.813  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:25.813  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-02 13:47:25.837  1524  1536 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 13:47:25.837  1524  1536 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-02 13:47:25.841  2573  2606 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 13:47:25.841  2573  2606 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 13:47:25.841  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 13:47:25.841  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 13:47:25.841  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 13:47:25.841  2573  2606 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 13:47:25.841  2573  2606 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-02 13:47:26.418  3362  3362 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-02 13:47:26.439  3362  3362 D AndroidRuntime: CheckJNI is OFF
08-02 13:47:26.487  3362  3362 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-02 13:47:26.534  3362  3362 I Radio-JNI: register_android_hardware_Radio DONE
08-02 13:47:26.553  3362  3362 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-02 13:47:26.557   873  2056 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-02 13:47:26.603   873  2056 I ActivityManager: Start proc 3372:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-02 13:47:26.613  3362  3362 D AndroidRuntime: Shutting down VM
08-02 13:47:26.703  3372  3372 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-02 13:47:26.725  3372  3372 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-02 13:47:26.735  3372  3372 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1733-1739)
08-02 13:47:26.735  3372  3372 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-02 13:47:26.754  3372  3372 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29105db}
08-02 13:47:26.755  3372  3372 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-02 13:47:26.755  3372  3372 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-02 13:47:26.760  3372  3372 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-02 13:47:26.761  3372  3372 E SysUtils: ApplicationContext is null in ApplicationStatus
08-02 13:47:26.791  3372  3387 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-02 13:47:26.817  3372  3372 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-02 13:47:26.848  3372  3372 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-02 13:47:26.849  3372  3372 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-02 13:47:26.849  3372  3372 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-02 13:47:26.849  3372  3372 I Adreno  : Build Date                       : 10/20/15
08-02 13:47:26.849  3372  3372 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-02 13:47:26.849  3372  3372 I Adreno  : Local Branch                     : M14
08-02 13:47:26.849  3372  3372 I Adreno  : Remote Branch                    : 
08-02 13:47:26.849  3372  3372 I Adreno  : Remote Branch                    : 
08-02 13:47:26.849  3372  3372 I Adreno  : Reconstruct Branch               : 
,08-02 13:47:26.955   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ed4e9:true
,08-02 13:47:27.007  3372  3372 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-02 13:47:27.026  3372  3372 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-02 13:47:27.118  3372  3409 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-02 13:47:27.138  3372  3396 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-02 13:47:27.177  3372  3409 I OpenGLRenderer: Initialized EGL, version 1.4
,08-02 13:47:27.195  1668  1668 I Keyboard.Facilitator: onFinishInput()
,08-02 13:47:27.239   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +573ms (total +658ms)
,08-02 13:47:27.316  3372  3372 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3372
,08-02 13:47:27.453  3372  3372 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-02 13:47:27.628  3372  3411 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1697973968
,08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-02 13:47:27.633  3372  3411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bf5a4e added. We now have 1 listener(s)
,08-02 13:47:27.636  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-02 13:47:27.637  3372  3411 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-02 13:47:27.637  3372  3411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-02 13:47:27.637  3372  3411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-02 13:47:27.641  3372  3411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b64905 added. We now have 1 listener(s)
08-02 13:47:27.641  3372  3411 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 13:47:27.644   873  1318 D WifiService: New client listening to asynchronous messages
,08-02 13:47:27.647  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-02 13:47:27.647  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-02 13:47:27.647  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-02 13:47:27.647  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-02 13:47:27.647  3372  3411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-02 13:47:27.648  3372  3411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 13:47:27.649  3372  3411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-02 13:47:27.651  3372  3411 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:27.651  3372  3411 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:27.651  3372  3411 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-02 13:47:27.651  3372  3411 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 13:47:27.652  3372  3411 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-02 13:47:27.656  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:27.679  3372  3372 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-02 13:47:28.205  3372  3381 I art     : Background sticky concurrent mark sweep GC freed 70212(7MB) AllocSpace objects, 17(1584KB) LOS objects, 30% free, 22MB/32MB, paused 926us total 153.443ms
,08-02 13:47:28.762  3372  3419 W jxcore-log: Initializing JXcore engine
,08-02 13:47:28.762  3372  3419 W jxcore-log: JXcore engine is ready
,08-02 13:47:28.815  3419  3419 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-02 13:47:28.815  3419  3419 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10857]" dev="sockfs" ino=10857 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-02 13:47:28.815  3419  3419 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-02 13:47:28.815  3419  3419 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24012]" dev="sockfs" ino=24012 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-02 13:47:28.827  3372  3419 W jxcore-log: Starting JXcore engine
,08-02 13:47:28.905  3372  3419 W jxcore-log: Platform android
08-02 13:47:28.905  3372  3419 W jxcore-log: 
,08-02 13:47:28.905  3372  3419 W jxcore-log: Process ARCH arm
08-02 13:47:28.905  3372  3419 W jxcore-log: 
,08-02 13:47:29.068  3372  3419 I jxcore-log: JXcore Cordova bridge is ready!
08-02 13:47:29.068  3372  3419 I jxcore-log: 
08-02 13:47:29.068  3372  3419 W jxcore-log: JXcore engine is started
,08-02 13:47:29.083  3372  3411 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-02 13:47:29.089  3372  3372 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-02 13:47:38.851  3372  3419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-02 13:47:38.851  3372  3419 I jxcore-log: 
,08-02 13:47:38.854  3372  3419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-02 13:47:38.854  3372  3419 I jxcore-log: 
,08-02 13:47:38.856  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:38.856  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:38.856  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 13:47:38.857  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:38.858  3372  3419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-02 13:47:38.858  3372  3419 I jxcore-log: 
08-02 13:47:38.860  3372  3419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-02 13:47:38.860  3372  3419 I jxcore-log: 
,08-02 13:47:39.174  3372  3419 D ExecuteNativeTests: Running unit tests
,08-02 13:47:39.234  3372  3419 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-02 13:47:39.234  3372  3419 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e added. We now have 2 listener(s)
,08-02 13:47:39.235  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-02 13:47:39.235  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-02 13:47:39.235  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-02 13:47:39.235  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 13:47:39.235  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f added. We now have 2 listener(s)
08-02 13:47:39.235  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 13:47:39.236  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-02 13:47:39.238  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-02 13:47:39.239  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.239  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.239  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.239  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:39.239  3372  3419 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-02 13:47:39.241  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-02 13:47:39.241  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:39.243  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-02 13:47:39.243  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 13:47:39.244  3372  3419 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-02 13:47:39.244  3372  3419 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-02 13:47:39.244  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-02 13:47:39.244  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-02 13:47:39.244  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-02 13:47:39.245  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.245  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.245  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.245  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.245  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.245  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 13:47:39.245  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-02 13:47:39.245  3372  3419 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e removed from the list
,08-02 13:47:39.246  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.246  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f removed from the list
08-02 13:47:39.246  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.246  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 13:47:39.247  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.247  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.247  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.247  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.247  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.247  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.249  3372  3419 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-02 13:47:39.249  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-02 13:47:39.249  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.249  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.249  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.250  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.250  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.250  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.250  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.250  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.250  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
,08-02 13:47:39.250  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.250  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.250  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.250  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.250  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.250  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.250  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-02 13:47:39.251  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-02 13:47:39.255  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-02 13:47:39.256  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-02 13:47:39.256  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.256  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.256  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.257  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.257  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.257  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.257  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the li,st
08-02 13:47:39.257  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.258  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.258  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.258  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.258  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.258  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.258  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.258  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.258  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.258  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.258  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.259  3372  3419 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-02 13:47:39.260  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.261  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.261  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.261  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.262  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:39.262  3372  3419 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 13:47:39.262  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:39.262  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 13:47:39.263  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 13:47:39.263  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 13:47:39.263  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.263  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-02 13:47:39.265  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-02 13:47:39.271  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-02 13:47:39.272  3372  3372 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-02 13:47:39.272  3372  3419 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-02 13:47:39.272  3372  3419 I io.jxcore.node.ConnectionHelper: start: OK
08-02 13:47:39.273  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.273  3372  3419 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-02 13:47:39.274  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.274  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.274  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 13:47:39.274  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.274  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 13:47:39.274  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 13:47:39.274  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 13:47:39.274  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 13:47:39.274  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 13:47:39.275  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 13:47:39.275  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 13:47:39.276  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.276  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.276  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.276  3372  3372 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.276  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.276  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.276  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 13:47:39.276  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.276  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.276  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.276  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.276  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.277  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.277  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.277  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.277  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.277  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.277  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.278  3372  3419 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-02 13:47:39.279  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.279  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.279  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.280  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.280  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:39.280  3372  3419 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 13:47:39.280  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:39.280  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-02 13:47:39.280  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-02 13:47:39.280  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-02 13:47:39.280  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.280  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-02 13:47:39.282  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-02 13:47:39.283  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-02 13:47:39.283  3372  3372 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-02 13:47:39.283  3372  3419 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-02 13:47:39.283  3372  3419 I io.jxcore.node.ConnectionHelper: start: OK
08-02 13:47:39.283  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.283  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.283  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-02 13:47:39.283  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.283  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-02 13:47:39.283  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 13:47:39.283  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 13:47:39.283  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 13:47:39.283  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 13:47:39.284  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-02 13:47:39.284  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 13:47:39.284  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.284  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.284  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.284  3372  3372 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.285  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.285  3372  3419 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-02 13:47:39.285  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.285  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.285  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.285  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.285  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-02 13:47:39.285  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.285  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.285  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.285  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.285  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.285  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.285  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.286  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.286  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.286  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.286  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.286  3372  3419 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-02 13:47:39.287  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.287  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.287  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.287  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.287  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.287  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.287  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.287  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.287  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.287  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.287  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.287  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.287  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.287  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.287  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.288  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.288  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.288  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.288  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-02 13:47:39.288  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.288  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.288  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.289  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.289  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.289  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.289  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.289  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.289  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.289  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.289  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.289  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.289  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.289  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.289  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.289  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.289  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.289  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.290  3372  3419 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-02 13:47:39.290  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.290  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.290  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.290  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.290  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.290  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.290  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.290  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.290  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.290  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.290  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.290  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.290  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.290  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.291  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.291  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.291  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.291  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.291  3372  3419 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-02 13:47:39.291  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.291  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-02 13:47:39.291  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.291  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.292  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.292  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.292  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.292  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.292  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.292  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.292  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.292  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.292  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.292  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.292  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.292  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.292  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.292  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.293  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-02 13:47:39.293  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 13:47:39.293  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-02 13:47:39.293  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-02 13:47:39.293  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-02 13:47:39.293  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-02 13:47:39.293  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.293  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.293  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.293  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.293  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.293  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.293  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.294  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.294  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.294  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.294  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.294  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.294  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.294  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.294  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.294  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.294  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.294  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.295  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 13:47:39.295  3372  3419 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-02 13:47:39.295  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-02 13:47:39.297  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 13:47:39.297  3372  3419 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-02 13:47:39.297  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-02 13:47:39.297  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-02 13:47:39.297  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-02 13:47:39.297  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-02 13:47:39.297  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-02 13:47:39.298  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-02 13:47:39.299  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-02 13:47:39.299  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-02 13:47:39.300  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-02 13:47:39.300  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-02 13:47:39.300  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-02 13:47:39.300  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-02 13:47:39.300  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-02 13:47:39.300  3372  3419 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 13:47:39.300  3372  3419 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-02 13:47:39.300  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 13:47:39.300  3372  3419 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 13:47:39.300  3372  3419 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-02 13:47:39.300  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 13:47:39.300  3372  3419 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-02 13:47:39.300  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-02 13:47:39.301  3372  3419 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-02 13:47:39.301  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-02 13:47:39.302  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-02 13:47:39.302  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-02 13:47:39.303  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-02 13:47:39.303  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-02 13:47:39.303  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-02 13:47:39.303  3372  3419 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-02 13:47:39.303  3372  3419 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-02 13:47:39.303  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.303  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.303  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.304  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.304  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.304  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.304  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-02 13:47:39.304  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.304  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.304  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.304  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.304  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.304  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.305  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.305  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.305  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.305  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.305  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.305  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.306  3372  3419 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-02 13:47:39.306  3372  3422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-02 13:47:39.306  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.306  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.306  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.306  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.306  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.306  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.306  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.306  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.306  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.307  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.307  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.307  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.307  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.307  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.307  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.307  3372  3421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-02 13:47:39.307  3372  3421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-02 13:47:39.309  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.309  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.309  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.310  3372  3419 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-02 13:47:39.310  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.310  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.310  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.310  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.310  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.310  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.310  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.310  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.310  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.310  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.311  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.311  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.311  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.311  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.311  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.311  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.311  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.311  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.312  3372  3419 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-02 13:47:39.312  3372  3419 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-02 13:47:39.312  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 13:47:39.312  3372  3419 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-02 13:47:39.312  3372  3419 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-02 13:47:39.312  3372  3419 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-02 13:47:39.313  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 13:47:39.313  3372  3419 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-02 13:47:39.313  3372  3419 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-02 13:47:39.313  3372  3419 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-02 13:47:39.313  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 13:47:39.313  3372  3419 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-02 13:47:39.313  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.313  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.313  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.313  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.313  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.313  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.313  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.314  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.314  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.314  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.314  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.314  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.314  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.314  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.314  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.314  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.314  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.315  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.315  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.315  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.315  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.315  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.315  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.315  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.315  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.315  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.315  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.315  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.315  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.315  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.316  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.316  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.316  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.316  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.316  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.316  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.316  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.316  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.316  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.316  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.316  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.316  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.316  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.316  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.316  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.316  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.316  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.317  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.317  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.317  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.317  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.318  3372  3419 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-02 13:47:39.318  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.318  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-02 13:47:39.318  3372  3419 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-02 13:47:39.318  3372  3372 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-02 13:47:39.318  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-02 13:47:39.318  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.318  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-02 13:47:39.319  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.319  3372  3419 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-02 13:47:39.319  3372  3372 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-02 13:47:39.319  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.319  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.319  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-02 13:47:39.319  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-02 13:47:39.319  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-02 13:47:39.319  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.319  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 13:47:39.320  3372  3419 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.320  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.320  3372  3372 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-02 13:47:39.320  3372  3372 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-02 13:47:39.320  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.320  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.320  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.320  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.320  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.320  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.320  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.320  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.320  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.320  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.321  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.321  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.321  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.321  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.321  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.321  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.321  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.321  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.321  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.322  3372  3419 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-02 13:47:39.322  3372  3419 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-02 13:47:39.322  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-02 13:47:39.322  3372  3419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-02 13:47:39.322  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.322  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.322  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.323  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.323  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.323  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.323  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.323  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.323  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.323  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.323  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.323  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.323  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.323  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.323  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.323  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.324  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.324  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.325  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.325  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.325  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.325  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.325  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.325  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.325  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.325  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.325  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.325  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.325  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.325  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.325  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.326  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.326  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.326  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.326  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.326  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.326  3372  3419 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-02 13:47:39.326  3372  3419 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-02 13:47:39.327  3372  3419 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-02 13:47:39.327  3372  3419 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-02 13:47:39.327  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.327  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.327  3372  3419 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a2c09e not in the list
08-02 13:47:39.327  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.327  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.327  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
08-02 13:47:39.327  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.327  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.327  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-02 13:47:39.327  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-02 13:47:39.327  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-02 13:47:39.327  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-02 13:47:39.327  3372  3419 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-02 13:47:39.328  3372  3419 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30577f not in the list
08-02 13:47:39.328  3372  3419 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-02 13:47:39.328  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 13:47:39.328  3372  3419 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-02 13:47:39.328  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-02 13:47:39.328  3372  3419 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-02 13:47:39.328  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-02 13:47:39.330  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-02 13:47:39.330  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-02 13:47:39.330  3372  3419 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-02 13:47:39.330  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-02 13:47:39.330  3372  3419 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-02 13:47:39.331  3372  3419 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-02 13:47:39.331  3372  3419 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-02 13:47:39.332  3372  3419 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-02 13:47:39.332  3372  3419 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-02 13:47:39.332  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 13:47:39.332  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@46011 added. We now have 2 listener(s)
08-02 13:47:39.332  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 13:47:39.334   873  1841 D WifiService: setWifiEnabled: true pid=3372, uid=10000
08-02 13:47:39.334   873  1841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-02 13:47:39.335  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 13:47:39.335  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5484576 added. We now have 3 listener(s)
08-02 13:47:39.336  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 13:47:39.336  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.336  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.337  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 13:47:39.337  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@433b777 added. We now have 4 listener(s)
08-02 13:47:39.337  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 13:47:39.338  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-02 13:47:39.338  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f58fe4 added. We now have 5 listener(s)
08-02 13:47:39.338  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-02 13:47:39.338   873  2844 D WifiService: setWifiEnabled: false pid=3372, uid=10000
08-02 13:47:39.338   873  2844 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-02 13:47:39.354   873   890 I ActivityManager: Start proc 3425:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-02 13:47:39.354   873  1316 D WifiConfigStore: Loading config and enabling all networks 
08-02 13:47:39.356  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.357  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.357  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.357  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:39.365   873  1316 D WifiConfigStore: loaded 0 passpoint configs
08-02 13:47:39.366   873  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-02 13:47:39.366   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-02 13:47:39.367   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-02 13:47:39.367   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-02 13:47:39.368   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-02 13:47:39.368   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-02 13:47:39.368   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-02 13:47:39.374   873   886 I ActivityManager: Start proc 3437:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-02 13:47:39.378  3372  3419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-02 13:47:39.379  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.379  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.379  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.379  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:39.379  3372  3419 D io.jxcore.node.ConnectivityMonitor: start: OK
08-02 13:47:39.380  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:39.412  3437  3437 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-02 13:47:39.440   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-02 13:47:39.440   873  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 13:47:39.441   371   871 D CommandListener: Setting iface cfg
,08-02 13:47:39.447  3437  3437 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-02 13:47:39.450   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,08-02 13:47:39.451   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-02 13:47:39.451   873  1316 E native  : do suspend true
,08-02 13:47:39.467  1465  1465 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-02 13:47:39.468  1465  1465 W wpa_supplicant: wlan0: Failed to initiate AP scan
08-02 13:47:39.468   873  2056 I ActivityManager: Killing 2666:com.google.android.calendar/u0a37 (adj 15): empty #17
08-02 13:47:39.469   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
08-02 13:47:39.469   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-02 13:47:39.502   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 13:47:39.504  3425  3425 D AdapterServiceConfig: Adding HeadsetService
08-02 13:47:39.504  3425  3425 D AdapterServiceConfig: Adding A2dpService
08-02 13:47:39.505  3425  3425 D AdapterServiceConfig: Adding HidService
08-02 13:47:39.505  1887  2068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-02 13:47:39.505  3425  3425 D AdapterServiceConfig: Adding HealthService
08-02 13:47:39.505  3425  3425 D AdapterServiceConfig: Adding PanService
,08-02 13:47:39.505  3425  3425 D AdapterServiceConfig: Adding GattService
08-02 13:47:39.505  3425  3425 D AdapterServiceConfig: Adding BluetoothMapService
08-02 13:47:39.506  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.506  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.506  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.506  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:39.507  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:39.507  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:39.508  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:39.508  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:39.552   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10c5ff5:true
,08-02 13:47:39.552  3425  3425 D BluetoothAdapterState: make() - Creating AdapterState
,08-02 13:47:39.554  3425  3425 I bt_bluedroid: init
08-02 13:47:39.555  3425  3463 I BluetoothAdapterState: Entering OffState
,08-02 13:47:39.558  3425  3464 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-02 13:47:39.560  3425  3464 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-02 13:47:39.561  3425  3464 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-02 13:47:39.561  3425  3464 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-02 13:47:39.562  3425  3425 I bt_bluedroid: get_profile_interface socket
,08-02 13:47:39.564  3425  3467 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 13:47:39.564  3425  3425 I bt_bluedroid: get_profile_interface sdp
08-02 13:47:39.565  3425  3467 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 13:47:39.567  3425  3436 I bt_bluedroid: config_hci_snoop_log
,08-02 13:47:39.568   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-02 13:47:39.572  3425  3463 D BluetoothAdapterState: Current state: OFF, message: 0
,08-02 13:47:39.576  3425  3463 D BluetoothAdapterProperties: Setting state to 14
08-02 13:47:39.576  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-02 13:47:39.578  3425  3463 D BluetoothBondStateMachine: make
,08-02 13:47:39.580  3425  3468 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-02 13:47:39.583  3425  3463 I BluetoothAdapterState: Entering PendingCommandState
,08-02 13:47:39.584  3425  3425 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-02 13:47:39.587  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:39.587  3425  3425 D BtGatt.DebugUtils: handleDebugAction() action=null
08-02 13:47:39.588  3425  3425 D BtGatt.GattService: Received start request. Starting profile...
08-02 13:47:39.588  3425  3425 D BtGatt.GattService: start()
08-02 13:47:39.588  3425  3425 I bt_bluedroid: get_profile_interface gatt
,08-02 13:47:39.589  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
08-02 13:47:39.589  3425  3425 D BtGatt.AdvertiseManager: advertise manager created
,08-02 13:47:39.595  3425  3425 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:39.595  3425  3425 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:39.596  3425  3425 V BluetoothAdapterState: isBleTurningOn()=true
08-02 13:47:39.596  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:39.596  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-02 13:47:39.596  3425  3463 I bt_bluedroid: enable
08-02 13:47:39.597  3425  3464 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-02 13:47:39.597  3425  3464 I bt_hci  : start_up
,08-02 13:47:39.609  3425  3464 I bt_vendor: alloc value 0xb3a5c189
,08-02 13:47:39.609  3425  3464 I bt_vendor: init
08-02 13:47:39.610  3425  3464 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-02 13:47:39.610  3425  3464 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-02 13:47:39.719  3425  3464 D bt_hci  : start_up starting async portion
,08-02 13:47:39.720  3425  3471 I bt_hci  : event_finish_startup
08-02 13:47:39.720  3425  3471 I bt_hci_h4: hal_open
,08-02 13:47:39.721  3425  3471 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-02 13:47:39.731  3425  3471 I bt_userial_vendor: device fd = 51 open
,08-02 13:47:39.761  3425  3471 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 13:47:39.793  3425  3471 D bt_hwcfg: Chipset BCM4354A2
08-02 13:47:39.793  3425  3471 D bt_hwcfg: Target name = [BCM4354A2]
,08-02 13:47:39.794  3425  3471 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-02 13:47:39.822  3372  3372 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-02 13:47:40.522  3425  3471 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-02 13:47:40.524  3425  3471 D bt_hwcfg: Settlement delay -- 100 ms
,08-02 13:47:40.524  3425  3471 I bt_hwcfg: Setting fw settlement delay to 100 
,08-02 13:47:40.642  3425  3471 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 13:47:40.643  3425  3471 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-02 13:47:40.671  3425  3471 I bt_hwcfg: vendor lib fwcfg completed
,08-02 13:47:40.672  3425  3471 I bt_vendor: firmware callback
08-02 13:47:40.672  3425  3471 I bt_hci  : firmware_config_callback
,08-02 13:47:40.685  3425  3473 I bt_btu  : btu_task pending for preload complete event
,08-02 13:47:40.685  3425  3473 I bt_btu_task: Bluetooth chip preload is complete
08-02 13:47:40.685  3425  3473 I bt_btu  : btu_task received preload complete event
,08-02 13:47:40.698  3425  3473 I         : BTE_InitTraceLevels -- TRC_HCI
,08-02 13:47:40.699  3425  3473 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-02 13:47:40.699  3425  3473 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-02 13:47:40.699  3425  3473 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-02 13:47:40.700  3425  3473 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-02 13:47:40.700  3425  3473 I         : BTE_InitTraceLevels -- TRC_A2D
,08-02 13:47:40.700  3425  3473 I         : BTE_InitTraceLevels -- TRC_BNEP
08-02 13:47:40.700  3425  3473 I         : BTE_InitTraceLevels -- TRC_BTM
08-02 13:47:40.701  3425  3473 I         : BTE_InitTraceLevels -- TRC_GAP
,08-02 13:47:40.702  3425  3473 I         : BTE_InitTraceLevels -- TRC_PAN
08-02 13:47:40.702  3425  3473 I         : BTE_InitTraceLevels -- TRC_SDP
08-02 13:47:40.703  3425  3473 I         : BTE_InitTraceLevels -- TRC_GATT
,08-02 13:47:40.704  3425  3473 I         : BTE_InitTraceLevels -- TRC_SMP
08-02 13:47:40.704  3425  3473 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-02 13:47:40.705  3425  3473 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-02 13:47:40.843  3425  3473 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,08-02 13:47:40.843  3425  3473 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-02 13:47:40.851  3425  3467 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-02 13:47:40.852  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-02 13:47:40.854  3425  3467 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 13:47:40.860  3425  3467 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 13:47:40.864  3425  3467 D BluetoothAdapterProperties: Scan Mode:20
08-02 13:47:40.865  3425  3467 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-02 13:47:40.865  3425  3467 D bt_hci  : do_postload posting postload work item
,08-02 13:47:40.867  3425  3471 I bt_hci  : event_postload
,08-02 13:47:40.867  3425  3471 I bt_vendor: sco_config_cb
08-02 13:47:40.867  3425  3471 I bt_hci  : sco_config_callback postload finished.
08-02 13:47:40.871  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:40.874  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:40.877  3425  3467 D bt_bte_conf: Device ID record 1 : primary
,08-02 13:47:40.878  3425  3467 D bt_bte_conf:   vendorId            = 000f
08-02 13:47:40.878  3425  3467 D bt_bte_conf:   vendorIdSource      = 0001
08-02 13:47:40.878  3425  3467 D bt_bte_conf:   product             = 1200
08-02 13:47:40.879  3425  3467 D bt_bte_conf:   version             = 1436
08-02 13:47:40.879  3425  3467 D bt_bte_conf:   clientExecutableURL = 
08-02 13:47:40.879  3425  3467 D bt_bte_conf:   serviceDescription  = 
08-02 13:47:40.879  3425  3471 I bt_vendor: low_power_mode_cb
08-02 13:47:40.880  3425  3467 D bt_bte_conf:   documentationURL    = 
08-02 13:47:40.880  3425  3467 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-02 13:47:40.880  3425  3464 D bt_stack_manager: event_start_up_stack finished
08-02 13:47:40.881  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-02 13:47:40.882  3425  3463 D BluetoothAdapterProperties: Setting state to 15
08-02 13:47:40.882  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-02 13:47:40.883  3425  3463 I BluetoothAdapterState: Entering BleOnState
,08-02 13:47:40.887  3425  3463 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-02 13:47:40.888  3425  3463 D BluetoothAdapterProperties: Setting state to 11
08-02 13:47:40.888  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-02 13:47:40.897  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.901  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:40.903  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:40.905  3425  3425 D HeadsetService: Received start request. Starting profile...
08-02 13:47:40.910  3425  3425 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-02 13:47:40.911  3425  3425 D HeadsetStateMachine: make
,08-02 13:47:40.918   873   886 I ActivityManager: Start proc 3481:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-02 13:47:40.928  3425  3425 D HeadsetStateMachine: max_hf_connections = 1
,08-02 13:47:40.928  3425  3425 I bt_bluedroid: get_profile_interface handsfree
,08-02 13:47:40.929  3425  3463 I BluetoothAdapterState: Entering PendingCommandState
08-02 13:47:40.930  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-02 13:47:40.930  3425  3467 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-02 13:47:40.935  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.936   873   873 D BluetoothA2dp: Proxy object connected
,08-02 13:47:40.937  3425  3425 D A2dpService: Received start request. Starting profile...
,08-02 13:47:40.940  3425  3425 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-02 13:47:40.940  3425  3425 I bt_bluedroid: get_profile_interface avrcp
,08-02 13:47:40.949  3425  3425 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-02 13:47:40.949  3425  3425 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-02 13:47:40.949  3425  3425 D A2dpStateMachine: make
,08-02 13:47:40.951  3425  3425 I bt_bluedroid: get_profile_interface a2dp
,08-02 13:47:40.952  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-02 13:47:40.958  3425  3425 I BluetoothHidServiceJni: classInitNative: succeeds
,08-02 13:47:40.959  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.958  3425  3494 D A2dpStateMachine: Enter Disconnected: -2
,08-02 13:47:40.960  1383  1383 D BluetoothInputDevice: Proxy object connected
08-02 13:47:40.960  3425  3425 D HidService: Received start request. Starting profile...
08-02 13:47:40.960  3425  3425 I bt_bluedroid: get_profile_interface hidhost
,08-02 13:47:40.960  1383  1383 D HidProfile: Bluetooth service connected
08-02 13:47:40.961  3425  3425 D HidService: setHidService(): set to: null
08-02 13:47:40.961  3425  3467 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
08-02 13:47:40.961  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-02 13:47:40.963  3425  3425 I BluetoothHealthServiceJni: classInitNative: succeeds
08-02 13:47:40.963  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.964  3425  3425 D HealthService: Received start request. Starting profile...
,08-02 13:47:40.965  3425  3425 I bt_bluedroid: get_profile_interface health
,08-02 13:47:40.966  3425  3425 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-02 13:47:40.967  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.968  1383  1383 D BluetoothPan: BluetoothPAN Proxy object connected
,08-02 13:47:40.968  1383  1383 D PanProfile: Bluetooth service connected
08-02 13:47:40.969  3425  3425 D PanService: Received start request. Starting profile...
,08-02 13:47:40.969  3425  3425 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-02 13:47:40.969  3425  3425 I bt_bluedroid: get_profile_interface pan
08-02 13:47:40.969  3425  3467 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-02 13:47:40.972  3425  3425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:40.973  1383  1383 D BluetoothMap: Proxy object connected
,08-02 13:47:40.973  1383  1383 D MapProfile: Bluetooth service connected
,08-02 13:47:40.973  1383  1383 D BluetoothMap: getConnectedDevices()
08-02 13:47:40.974  3425  3425 D BluetoothMapService: Received start request. Starting profile...
08-02 13:47:40.974  3425  3425 D BluetoothMapService: start()
08-02 13:47:40.974  1383  1383 D BluetoothMap: Bluetooth is Not enabled
,08-02 13:47:40.976  3425  3425 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-02 13:47:40.976  3425  3425 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-02 13:47:40.977  3425  3425 D BluetoothMapAppObserver: createReceiver()
08-02 13:47:40.977  3425  3425 D BluetoothMapAppObserver: initObservers()
,08-02 13:47:40.978  3425  3425 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-02 13:47:40.984  3425  3425 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:40.984  3425  3425 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:40.984  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:40.984  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:40.984  3481  3481 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-02 13:47:40.985  3425  3425 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:40.986  3425  3480 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isTurningOn()=true
,08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isTurningOn()=true
,08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:40.986  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:40.987  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:40.988  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-02 13:47:40.988  3425  3463 D BluetoothAdapterProperties: ScanMode =  20
08-02 13:47:40.988  3425  3463 D BluetoothAdapterProperties: State =  11
,08-02 13:47:40.988  3425  3463 D BluetoothAdapterProperties: Setting state to 12
,08-02 13:47:40.988  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-02 13:47:40.989  1745  3110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:40.989  3425  3467 D BluetoothAdapterProperties: Scan Mode:21
,08-02 13:47:40.989  3425  3467 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-02 13:47:40.989  3425  3463 I BluetoothAdapterState: Entering OnState
,08-02 13:47:40.991  1383  1401 D BluetoothPan: onBluetoothStateChange on: true
08-02 13:47:40.992  1383  1400 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-02 13:47:40.992  3372  3372 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-02 13:47:40.992   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:40.993   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-02 13:47:40.993  1383  1786 D BluetoothPbap: onBluetoothStateChange: up=true
,08-02 13:47:40.994   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:40.995  1383  1401 D BluetoothMap: onBluetoothStateChange: up=true
08-02 13:47:40.996   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-02 13:47:40.996  3372  3372 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-02 13:47:40.999   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-02 13:47:41.000  3425  3425 D BluetoothMapService: onReceive
08-02 13:47:41.000  3425  3425 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
08-02 13:47:41.000  3425  3425 D BluetoothMapService: STATE_ON
08-02 13:47:41.001  3372  3372 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-02 13:47:41.004  3425  3425 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener,
08-02 13:47:41.004  1383  1680 D LocalBluetoothProfileManager: Adding local A2DP profile
08-02 13:47:41.004  3425  3425 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-02 13:47:41.006  3425  3425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:41.008  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:41.009  3425  3425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 13:47:41.010   873  1841 I ActivityManager: Killing 2829:com.google.android.gm/u0a78 (adj 15): empty #17
08-02 13:47:41.012  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:41.017  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:41.021  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:41.023  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:41.024  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:41.059  1383  1383 D BluetoothA2dp: Proxy object connected
08-02 13:47:41.059  1383  1680 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-02 13:47:41.060  3425  3425 D ObexServerSockets: Succeed to create listening sockets 
08-02 13:47:41.061  3425  3425 D ObexServerSockets0: startAccept()
,08-02 13:47:41.061  3425  3425 D ObexServerSockets0: prepareForNewConnect()
,08-02 13:47:41.067  3425  3500 D ObexServerSockets0: Accepting socket connection...
,08-02 13:47:41.068  3425  3425 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-02 13:47:41.068  3425  3501 D ObexServerSockets0: Accepting socket connection...
08-02 13:47:41.068  3425  3425 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-02 13:47:41.070  3425  3425 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 13:47:41.070  3425  3425 D ObexServerSockets0: prepareForNewConnect()
,08-02 13:47:41.074  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:41.091  1745  1765 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.092   873   890 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.095   873   890 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.096   873   890 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.096   873   883 I ActivityManager: Start proc 3502:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-02 13:47:41.131  3502  3502 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-02 13:47:41.161  1383  1400 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.163  1383  1383 D HeadsetProfile: Bluetooth service connected
,08-02 13:47:41.313  3502  3502 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.313  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.e.b(PG:170)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.k.d(PG:583)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.e.b(PG:170)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.File.exists(File.java:361)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.314  3502  3502 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 13:47:41.314  3502  3502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-02 13:47:41.337  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 13:47:41.346   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c27c545:true
,08-02 13:47:41.355  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:41.359  3481  3481 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-02 13:47:41.365  3481  3481 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-02 13:47:41.384  1383  1383 D BluetoothPbap: Proxy object connected
,08-02 13:47:41.385  1383  1383 D PbapServerProfile: Bluetooth service connected
,08-02 13:47:41.395  3481  3481 D LocalBluetoothProfileManager: Adding local MAP profile
,08-02 13:47:41.395  3481  3481 D BluetoothMap: Create BluetoothMap proxy object
08-02 13:47:41.403  3481  3481 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-02 13:47:41.406  3425  3531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 13:47:41.413  3481  3481 D DockEventReceiver: finishStartingService: stopping service
,08-02 13:47:41.414  3481  3481 D BluetoothA2dp: Proxy object connected
,08-02 13:47:41.417  3481  3481 D BluetoothInputDevice: Proxy object connected
08-02 13:47:41.418  3481  3481 D HidProfile: Bluetooth service connected
,08-02 13:47:41.419  3481  3481 D BluetoothPan: BluetoothPAN Proxy object connected
,08-02 13:47:41.420  3481  3481 D PanProfile: Bluetooth service connected
08-02 13:47:41.421  3481  3481 D BluetoothMap: Proxy object connected
08-02 13:47:41.421  3481  3481 D MapProfile: Bluetooth service connected
08-02 13:47:41.421  3481  3481 D BluetoothMap: getConnectedDevices()
08-02 13:47:41.424  3481  3481 D BluetoothPbap: Proxy object connected
08-02 13:47:41.424  3481  3481 D PbapServerProfile: Bluetooth service connected
08-02 13:47:41.425   873  1393 I ActivityManager: Killing 3016:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-02 13:47:41.462  3425  3537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 13:47:41.465  3425  3537 I BtOppRfcommListener: Accept thread started.
,08-02 13:47:41.468  3481  3492 D BluetoothHeadset: Proxy object connected
,08-02 13:47:41.468  3481  3481 D HeadsetProfile: Bluetooth service connected
,08-02 13:47:41.566  3502  3520 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-02 13:47:41.587   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b42cd87:true
,08-02 13:47:42.384   873  1784 D WifiService: setWifiEnabled: true pid=3372, uid=10000
,08-02 13:47:42.384   873  1784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 13:47:42.401   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:42.418  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:42.424  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:42.432  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:42.432   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-02 13:47:42.433   873  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-02 13:47:42.433   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-02 13:47:42.434   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-02 13:47:42.435   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-02 13:47:42.436   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-02 13:47:42.436   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-02 13:47:42.436   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-02 13:47:42.436  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:42.437  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-02 13:47:42.525   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-02 13:47:42.526   873  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 13:47:42.529   371   871 D CommandListener: Setting iface cfg
,08-02 13:47:42.531   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-02 13:47:42.531   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-02 13:47:42.531  1465  1465 E wpa_supplicant: PNO: In assoc process
,08-02 13:47:42.533   873  1316 E WifiStateMachine:  Fail to set up pno, want true now false
,08-02 13:47:42.540   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-02 13:47:42.542   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-02 13:47:42.543   873  1316 E native  : do suspend true
,08-02 13:47:42.600   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 13:47:42.897  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-02 13:47:42.937  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-02 13:47:42.937  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-02 13:47:42.946   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-02 13:47:42.957   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-02 13:47:42.958   873  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-02 13:47:42.958   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 13:47:42.979   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 13:47:42.993   371   871 D CommandListener: Setting iface cfg
,08-02 13:47:43.002   873  1316 D WifiStateMachine: Start Dhcp Watchdog 1,
,08-02 13:47:43.010   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-02 13:47:43.061   873  3547 D DhcpClient: Receive thread started
,08-02 13:47:43.151   873  1316 E native  : do suspend false
,08-02 13:47:43.175   873  3546 D DhcpClient: Broadcasting DHCPDISCOVER
,08-02 13:47:43.191   873  3547 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 167194, domain null
,08-02 13:47:43.193   873  3546 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 167194 seconds
,08-02 13:47:43.198   873  3546 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-02 13:47:43.211   873  3547 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-02 13:47:43.212   873  3546 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-02 13:47:43.217   371   871 D CommandListener: Setting iface cfg
,08-02 13:47:43.227   873  3546 D DhcpClient: Scheduling renewal in 86399s
08-02 13:47:43.229   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-02 13:47:43.235   873  1316 E native  : do suspend true
,08-02 13:47:43.259   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-02 13:47:43.263   873  1316 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-02 13:47:43.266   873  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-02 13:47:43.273   873  1319 D ConnectivityService: Adding iface wlan0 to network 100
,08-02 13:47:43.283   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-02 13:47:43.347   873  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-02 13:47:43.348   873  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-02 13:47:43.351   873  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-02 13:47:43.352   873  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-02 13:47:43.354   873  1319 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-02 13:47:43.365   873  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-02 13:47:43.372   873  1319 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-02 13:47:43.373   873  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-02 13:47:43.373   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-02 13:47:43.374   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-02 13:47:43.376   873  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-02 13:47:43.376   873  1319 D ConnectivityService:    accepting network in place of null
,08-02 13:47:43.377   873  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-02 13:47:43.398   873  3545 D NetlinkSocketObserver: NeighborEvent{elapsedMs=348399, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-02 13:47:43.439   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 13:47:43.465   873  3544 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.211.14,2a00:1450:4001:817::200e
,08-02 13:47:43.475   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 13:47:43.477   873  1319 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-02 13:47:43.484   873  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-02 13:47:43.485   873  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-02 13:47:43.487   873  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-02 13:47:43.488   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-02 13:47:43.502   873   883 V BackupManagerService: Scheduling immediate backup pass,
,08-02 13:47:43.503   873   873 V BackupManagerService: Running a backup pass
,08-02 13:47:43.504   873  1337 V BackupManagerService: clearing pending backups
,08-02 13:47:43.507   873  1337 V PerformBackupTask: Beginning backup of 16 targets
,08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 13:47:43.508  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-02 13:47:43.513  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 13:47:43.517  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-02 13:47:43.537   873  1715 D AlarmManagerService: Setting time of day to sec=1470138462
,08-02 13:47:42.916   873  1715 W AlarmManagerService: Unable to set rtc to 1470138462: Invalid argument
,08-02 13:47:42.916   873  1337 D PerformBackupTask: invokeAgentForBackup on @pm@
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-02 13:47:42.919  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-02 13:47:42.922  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-02 13:47:42.924   873  1337 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-02 13:47:42.934   873  3544 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Aug 2016 11:47:42 GMT], X-Android-Received-Millis=[1470138462933], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470138463523]}
,08-02 13:47:42.936   873  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-02 13:47:42.936   873  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-02 13:47:42.937   873  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-02 13:47:42.937  1977  1977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-02 13:47:42.938   873  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-02 13:47:42.941  1977  1977 D SystemUpdateService: onCreate
,08-02 13:47:42.946  1977  1977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-02 13:47:42.948  1977  3566 I SystemUpdateService: active receiver: enabled
,08-02 13:47:42.952  1977  3566 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-02 13:47:42.955  1977  3566 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-02 13:47:42.955  1977  3566 I SystemUpdateService: now status is 0 (complete)
08-02 13:47:42.955  1977  3566 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-02 13:47:42.955  1977  3566 I SystemUpdateService: file has been verified
08-02 13:47:42.956  1977  3566 I SystemUpdateService: OTA package size = 12249756
,08-02 13:47:42.963  1977  3566 I SystemUpdateService: showing system update notification
,08-02 13:47:42.983   873  3573 D GpsLocationProvider: NTP server returned: 1470138462915 (Tue Aug 02 13:47:42 GMT+02:00 2016) reference: 348540 certainty: 4 system time offset: -67
,08-02 13:47:42.983   873  3573 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-02 13:47:42.986   873  1337 I BackupRestoreController: Getting widget state for user: 0
,08-02 13:47:42.997  1977  1977 D SystemUpdateService: onDestroy
,08-02 13:47:43.020  1977  3572 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-02 13:47:43.029   873   883 I ActivityManager: Start proc 3576:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-02 13:47:43.048  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:43.050  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:43.060  1887  1904 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-02 13:47:43.064  1887  1904 V GmsBackupTransport: starting performBackup for @pm@
,08-02 13:47:43.072  1977  3592 I iu.SyncManager: SYNC; picasa accounts
,08-02 13:47:43.077  1887  1904 V GmsBackupTransport: performBackup done for @pm@
,08-02 13:47:43.077  1977  1977 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-02 13:47:43.078  3576  3576 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-02 13:47:43.079  1977  1977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-02 13:47:43.082  1977  3592 I iu.UploadsManager: num queued entries: 0
,08-02 13:47:43.083  1977  3592 I iu.UploadsManager: num updated entries: 0
,08-02 13:47:43.084  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:43.087  1977  3592 I iu.SyncManager: NEXT; no task
,08-02 13:47:43.097  1977  1977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 13:47:43.098  1977  1977 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 13:47:43.103  1977  3590 I MDM     : [191] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-02 13:47:43.103  1977  3590 W BaseAppContext: Using Auth Proxy for data requests.
,08-02 13:47:43.112   873  2825 I ActivityManager: Start proc 3597:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-02 13:47:43.123  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-02 13:47:43.124  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-02 13:47:43.124  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:43.124  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.127  3437  3575 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
08-02 13:47:43.127  1977  3590 V GoogleAuthProtoRequest: [191] a.<init>: mAccountName set to: thalitester@gmail.com
,08-02 13:47:43.137  1524  3058 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 13:47:43.137  1524  3058 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 13:47:43.140  1887  2078 W GmsBackupTransport: Error sending final backup to server: 
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 13:47:43.140  1887  2078 W GmsBackupTransport: 	... 1 more
,08-02 13:47:43.142  1887  1900 I GmsBackupTransport: Next backup will happen in 43199996 millis.
,08-02 13:47:43.142   873  1337 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-02 13:47:43.149  3597  3597 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-02 13:47:43.157  3597  3597 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 13:47:43.167  1524  2678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-02 13:47:43.168  1524  2678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-02 13:47:43.168  1524  2678 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:43.168  1524  2678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.170  1977  1977 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-02 13:47:43.172  3597  3597 D SprintDMHelper: simOperator: 
,08-02 13:47:43.172  3597  3597 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 13:47:43.186   873  1393 I ActivityManager: Start proc 3610:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-02 13:47:43.204   873  1337 I BackupManagerService: Backup pass finished.
,08-02 13:47:43.209  1977  3590 E MDM     : [191] SitrepService.a: Error sending sitrep.
,08-02 13:47:43.211   873  2825 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1977 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-02 13:47:43.239  1524  3182 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-02 13:47:43.239  1524  3182 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-02 13:47:43.239  1524  3182 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:43.239  1524  3182 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.276  3437  3575 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-02 13:47:43.277  3437  3575 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-02 13:47:43.299  3576  3576 W art     : No such thread id for suspend: 12
,08-02 13:47:43.305  3576  3628 W art     : No such thread id for suspend: 12
,08-02 13:47:43.309  1977  3574 W DriveInitializer: Awaiting to be initialized
,08-02 13:47:43.310  1977  3631 W DriveInitializer: Background init thread started
,08-02 13:47:43.358  3576  3614 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-02 13:47:43.386  1524  1524 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-02 13:47:43.387  1977  3631 W DriveInitializer: Background init thread ended
,08-02 13:47:43.457  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-02 13:47:43.457  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 13:47:43.457  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:43.457  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.474  3143  3593 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-02 13:47:43.474  3143  3593 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jdm.a(PG:82)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jcs.o(PG:406)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jcn.a(PG:1379)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jcs.i(PG:143)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at blb.a(PG:3937)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at czp.a(PG:18188)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at czp.a(PG:9081)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at czq.run(PG:1686)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 13:47:43.474  3143  3593 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jdj.a(PG:4091)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jdj.a(PG:1125)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jdm.a(PG:77)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	... 12 more
08-02 13:47:43.474  3143  3593 E HttpOperation: Caused by: faj: BadAuthentication
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at fal.a(PG:38)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	at jdj.a(PG:4089)
08-02 13:47:43.474  3143  3593 E HttpOperation: 	... 14 more
,08-02 13:47:43.506  1524  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-02 13:47:43.507  1524  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-02 13:47:43.507  1524  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:47:43.507  1524  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.517  3143  3593 E HttpOperation: [getmobileexperiments] Unexpected exception
08-02 13:47:43.517  3143  3593 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jdm.a(PG:82)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jcs.o(PG:406)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jcn.a(PG:1379)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jcs.i(PG:143)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at hec.a(PG:42)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at hee.a(PG:102)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at czr.a(PG:65)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at kka.a(PG:108)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at czp.a(PG:19176)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at czp.a(PG:9081)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at czq.run(PG:1686)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-02 13:47:43.517  3143  3593 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jdj.a(PG:4091)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jdj.a(PG:1125)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jdm.a(PG:77)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	... 15 more
08-02 13:47:43.517  3143  3593 E HttpOperation: Caused by: faj: BadAuthentication
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at fal.a(PG:38)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	at jdj.a(PG:4089)
08-02 13:47:43.517  3143  3593 E HttpOperation: 	... 17 more
,08-02 13:47:43.517  3143  3593 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-02 13:47:43.517  3143  3593 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jdm.a(PG:82)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jcs.o(PG:406)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jcn.a(PG:1379)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jcs.i(PG:143)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at hec.a(PG:42)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at hee.a(PG:102)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at czr.a(PG:65)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at kka.a(PG:108)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at czp.a(PG:19176)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at czp.a(PG:9081)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at czq.run(PG:1686)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jdj.a(PG:4091)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jdj.a(PG:1125)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jdm.a(PG:77)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	... 15 more
08-02 13:47:43.517  3143  3593 E ExperimentLoader: Caused by: faj: BadAuthentication
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at fal.a(PG:38)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	at jdj.a(PG:4089)
08-02 13:47:43.517  3143  3593 E ExperimentLoader: 	... 17 more
,08-02 13:47:43.600   873  2844 I ActivityManager: Start proc 3655:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-02 13:47:43.612   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 24532, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-02 13:47:43.656  2872  3629 V KeepSync: Connecting to GoogleApiClient
,08-02 13:47:43.657   873  1784 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-02 13:47:43.668   873   885 I ActivityManager: Start proc 3668:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-02 13:47:43.690  3668  3668 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-02 13:47:43.740  2362  3654 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-02 13:47:43.758  1524  3344 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-02 13:47:43.758  1524  3344 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-02 13:47:43.758  1524  3344 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:43.758  1524  3344 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:43.773  3576  3614 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-02 13:47:43.775  3655  3655 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-02 13:47:43.779  1977  3684 V BaseAuthAsyncOperation: access token request failed
,08-02 13:47:43.781  2872  3629 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-02 13:47:43.810  1524  3643 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-02 13:47:43.870  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:43.932  3576  3614 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-02 13:47:43.952  3668  3668 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-02 13:47:43.959  3668  3668 I BooksApp: Created application version: 3.6.9 (30609)
,08-02 13:47:43.987  3576  3576 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-02 13:47:44.023  3668  3705 I BooksSync: Starting books sync for 61035162, extras: ade
,08-02 13:47:44.035  3702  3702 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-286181713.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-286181713.dex
,08-02 13:47:44.075  3702  3702 I dex2oat : dex2oat took 40.316ms (threads: 4) arena alloc=245KB java alloc=29KB native alloc=1641KB free=1686KB
,08-02 13:47:44.080  3655  3655 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-02 13:47:44.080  3655  3655 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-02 13:47:44.080  3655  3655 I GAv4    :   adb logcat -s GAv4
,08-02 13:47:44.098  3655  3655 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:44.103  3655  3655 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:44.116  3576  3576 W InstanceID/Rpc: Found 10011
,08-02 13:47:44.144  3655  3739 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:44.304  3655  3655 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-02 13:47:44.380  3655  3655 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-02 13:47:44.395  3655  3655 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 11-21)
,08-02 13:47:44.396  3655  3655 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-02 13:47:44.441  3655  3655 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb47d75}
,08-02 13:47:44.442  3655  3655 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-02 13:47:44.442  3655  3655 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-02 13:47:44.453  3655  3655 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-02 13:47:44.454  3655  3655 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-02 13:47:44.492  3655  3655 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-02 13:47:44.517  3655  3655 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-02 13:47:44.518  3655  3655 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-02 13:47:44.518  3655  3655 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-02 13:47:44.518  3655  3655 I Adreno  : Build Date                       : 10/20/15
08-02 13:47:44.518  3655  3655 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-02 13:47:44.518  3655  3655 I Adreno  : Local Branch                     : M14
08-02 13:47:44.518  3655  3655 I Adreno  : Remote Branch                    : 
08-02 13:47:44.518  3655  3655 I Adreno  : Remote Branch                    : 
08-02 13:47:44.518  3655  3655 I Adreno  : Reconstruct Branch               : 
,08-02 13:47:44.539  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-02 13:47:44.540  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-02 13:47:44.540  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:44.540  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:44.586  2872  3629 E KeepSync: IOException
08-02 13:47:44.586  2872  3629 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-02 13:47:44.586  2872  3629 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-02 13:47:44.586  2872  3629 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-02 13:47:44.586  2872  3629 E KeepSync: 	... 10 more
,08-02 13:47:44.586  2872  3629 W KeepSync: Sync result 2
,08-02 13:47:44.604   873  2825 I ActivityManager: Killing 2460:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-02 13:47:44.608   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 13:47:44.644  3668  3794 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-02 13:47:44.676  3655  3798 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-02 13:47:44.718  3655  3655 I NSApplication: Starting up...
,08-02 13:47:44.741   873  1393 I ActivityManager: Start proc 3803:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-02 13:47:44.742   873  1393 I ActivityManager: Killing 2744:android.process.acore/u0a5 (adj 15): empty #17
,08-02 13:47:44.767   873  2844 D WifiService: setWifiEnabled: false pid=3372, uid=10000
,08-02 13:47:44.768   873  2844 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-02 13:47:44.785  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-02 13:47:44.787   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-02 13:47:44.787   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-02 13:47:44.787   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 13:47:44.787   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-02 13:47:44.800   873  1316 E native  : do suspend true
,08-02 13:47:44.807  1524  3182 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-02 13:47:44.807  1524  3182 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 13:47:44.807  1524  3182 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:47:44.807  1524  3182 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:44.811   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-02 13:47:44.811   873  3546 D DhcpClient: Clearing IP address
,08-02 13:47:44.814   371   871 D CommandListener: Setting iface cfg
,08-02 13:47:44.815  1524  3624 V NativeCrypto: Read error: ssl=0x9af7b600: I/O error during system call, Connection timed out
,08-02 13:47:44.816  1524  3624 V NativeCrypto: SSL shutdown failed: ssl=0x9af7b600: I/O error during system call, Broken pipe
,08-02 13:47:44.821   873  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-02 13:47:44.822   873  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-02 13:47:44.823   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-02 13:47:44.825   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-02 13:47:44.825   873  1316 E native  : do suspend true
08-02 13:47:44.829   419   419 E Parcel  : Reading a NULL string not supported here.
,08-02 13:47:44.838   873  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-02 13:47:44.840   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-02 13:47:44.843   873  3547 D DhcpClient: Receive thread stopped
,08-02 13:47:44.854  3803  3803 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-02 13:47:44.871   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 13:47:44.883  3576  3743 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
,08-02 13:47:44.887   873  2056 I ActivityManager: Killing 3233:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-02 13:47:44.899   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-02 13:47:44.900   873  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-02 13:47:44.900   873  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-02 13:47:44.916   873  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-02 13:47:44.918   873   890 D Tethering: MasterInitialState.processMessage what=3
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:44.924  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:44.930  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-02 13:47:44.932  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:44.934   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:44.936  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:44.937  1887  2068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-02 13:47:44.938   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-02 13:47:44.938  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:44.946  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:44.948  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:44.953  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:44.955  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-02 13:47:44.996  1524  3827 I VacuumService: Vacuum at: now=1470138464995 tag=VacuumService
,08-02 13:47:45.000  1524  2678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-02 13:47:45.000  1524  2678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-02 13:47:45.000  1524  2678 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:45.000  1524  2678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:45.003   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-02 13:47:45.004   873  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-02 13:47:45.023  3668  3794 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 13:47:45.024  3668  3705 E BooksSync: Soft error
08-02 13:47:45.024  3668  3705 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 13:47:45.024  3668  3705 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-02 13:47:45.024  3668  3705 E BooksSync: Sync error
08-02 13:47:45.024  3668  3705 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-02 13:47:45.024  3668  3705 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-02 13:47:45.025  3668  3705 I BooksSync: Finished books sync
,08-02 13:47:45.039   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-02 13:47:45.041   873  1841 I ActivityManager: Killing 3250:com.android.musicfx/u0a18 (adj 15): empty #17
,08-02 13:47:45.312   873  1859 I ActivityManager: Killing 3068:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-02 13:47:45.445   873  1859 I ActivityManager: Start proc 3831:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,08-02 13:47:45.541  3831  3831 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-02 13:47:45.640   873   883 I ActivityManager: Start proc 3846:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,08-02 13:47:45.707  3846  3846 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,08-02 13:47:45.768   873  1704 I ActivityManager: Start proc 3861:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,08-02 13:47:45.770   873  1704 I ActivityManager: Killing 3198:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-02 13:47:45.770   279   279 E lowmemorykiller: Error writing /proc/3198/oom_score_adj; errno=22
,08-02 13:47:45.813   873  1704 I ActivityManager: Killing 3271:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,08-02 13:47:45.893  3846  3846 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@29105db(com.android.providers.calendar.CalendarProvider2@9ea6878)
,08-02 13:47:45.912  3831  3831 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-02 13:47:45.926  3861  3861 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-02 13:47:45.947  3861  3861 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-02 13:47:45.947  3861  3861 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-02 13:47:45.947  3861  3861 I GAv4    :   adb logcat -s GAv4
,08-02 13:47:45.967  3861  3861 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:45.972  3861  3861 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:45.986  3861  3877 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-02 13:47:46.049   873  2844 I ActivityManager: Start proc 3880:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-02 13:47:46.104  3880  3880 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,08-02 13:47:46.120  3880  3880 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470138466120
08-02 13:47:46.120  3880  3880 D         : TimeServiceNative: User Time to be set is 1470138466120
08-02 13:47:46.120  3880  3880 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-02 13:47:46.120  3880  3880 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-02 13:47:46.120  3880  3880 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470138466120
08-02 13:47:46.120  3880  3880 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-02 13:47:46.120   416   997 D QC-time-services: Daemon: Connection accepted:time_genoff
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470138466120
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470138466120, operation = 0
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/19/70 7:58:10
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:Value read from RTC seconds = 30441490000
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:new time 1470138466120 
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon: delta 1439696976120 genoff 1439696976120 
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696976120 to memory
08-02 13:47:46.121   416  3892 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-02 13:47:46.122   416  3892 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-02 13:47:46.142   416  3892 D QC-time-services: Updating the TOD offset
08-02 13:47:46.142   416  3892 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696976120 to memory
08-02 13:47:46.142   416  3892 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-02 13:47:46.142   416  3892 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-02 13:47:46.144  3880  3880 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-02 13:47:46.144   416  3892 E QC-time-services: Daemon:Update to modem bit set
,08-02 13:47:46.144   416  3892 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-02 13:47:46.145   416  3892 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1154173666120
08-02 13:47:46.146   873  1860 I ActivityManager: Killing 1817:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-02 13:47:46.189   873  1318 D WifiService: Client connection lost with reason: 4
,08-02 13:47:46.214   416   997 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-02 13:47:46.220   416   995 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-02 13:47:46.237  2362  3895 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-02 13:47:46.265  1977  1977 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-02 13:47:46.268  1977  1977 D SystemUpdateService: onCreate
,08-02 13:47:46.272  1977  1977 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-02 13:47:46.275  1977  3897 I SystemUpdateService: active receiver: enabled
,08-02 13:47:46.279  1977  3897 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-02 13:47:46.281  1977  3897 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-02 13:47:46.281  1977  3897 I SystemUpdateService: now status is 0 (complete)
08-02 13:47:46.281  1977  3897 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-02 13:47:46.281  1977  3897 I SystemUpdateService: file has been verified
08-02 13:47:46.281  1977  3897 I SystemUpdateService: OTA package size = 12249756
,08-02 13:47:46.284  1977  1977 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-02 13:47:46.289  1977  3897 I SystemUpdateService: showing system update notification
,08-02 13:47:46.291  1977  3592 I iu.UploadsManager: num queued entries: 0
,08-02 13:47:46.293  1977  3592 I iu.UploadsManager: num updated entries: 0
,08-02 13:47:46.294  1977  3592 I iu.SyncManager: NEXT; no task
,08-02 13:47:46.297  1977  1977 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-02 13:47:46.298  1977  1977 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-02 13:47:46.299  3597  3597 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-02 13:47:46.302  1977  1977 D SystemUpdateService: onDestroy
,08-02 13:47:46.303  3597  3597 D SprintDMHelper: simOperator: 
08-02 13:47:46.304  3597  3597 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-02 13:47:47.005  3846  3846 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,08-02 13:47:47.008  3846  3846 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-02 13:47:47.780  3425  3463 D BluetoothAdapterState: Current state: ON, message: 23
08-02 13:47:47.781  3425  3463 D BluetoothAdapterProperties: Setting state to 13
,08-02 13:47:47.781  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-02 13:47:47.784  3425  3463 D BluetoothAdapterProperties: onBluetoothDisable()
08-02 13:47:47.788  3425  3463 I BluetoothAdapterState: Entering PendingCommandState
,08-02 13:47:47.793  3425  3425 D BluetoothMapService: onReceive
,08-02 13:47:47.794  3425  3425 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-02 13:47:47.794  3425  3425 D BluetoothMapService: STATE_TURNING_OFF
,08-02 13:47:47.795  3425  3425 D BluetoothMapService: MAP Service closeService in
08-02 13:47:47.795  3425  3425 D BluetoothMapMasInstance0: MAP Service shutdown
,08-02 13:47:47.795  3425  3425 D ObexServerSockets0: shutdown(block = true)
,08-02 13:47:47.796  3425  3425 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 13:47:47.796  3425  3501 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-02 13:47:47.797  3425  3500 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-02 13:47:47.797  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 13:47:47.798  3425  3475 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:47.798  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:47.798  3425  3425 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 13:47:47.798  3425  3425 I BtOppRfcommListener: stopping Accept Thread
,08-02 13:47:47.799  3425  3537 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-02 13:47:47.799  3425  3537 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-02 13:47:47.800  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:47.800  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:47.809  3425  3467 D BluetoothAdapterProperties: Scan Mode:20
,08-02 13:47:47.809  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-02 13:47:47.810  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:47.810  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:47.811  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:47.811  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:47.816  3425  3425 D HeadsetService: Received stop request...Stopping profile...
08-02 13:47:47.816  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:47.818  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:47.819  1745  1757 D BluetoothHeadset: Proxy object disconnected
,08-02 13:47:47.819   873   873 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:47.819  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.819  3425  3425 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:47.819  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:47.819  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:47.820  3481  3492 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:47.820  1383  1400 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:47.820   873   873 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:47.820   873   873 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:47.820  3425  3425 D A2dpService: Received stop request...Stopping profile...
08-02 13:47:47.821  3425  3494 D A2dpStateMachine: Exit Disconnected: -1
08-02 13:47:47.814  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 13:47:47.825   873   873 D BluetoothA2dp: Proxy object disconnected
,08-02 13:47:47.826  3425  3425 D HidService: Received stop request...Stopping profile...
08-02 13:47:47.826  3425  3425 D HidService: Stopping Bluetooth HidService
,08-02 13:47:47.830  3425  3425 D HealthService: Received stop request...Stopping profile...
,08-02 13:47:47.831  1383  1383 D HeadsetProfile: Bluetooth service disconnected
08-02 13:47:47.831  1383  1383 D BluetoothA2dp: Proxy object disconnected
08-02 13:47:47.831  1383  1383 D BluetoothInputDevice: Proxy object disconnected
,08-02 13:47:47.831  1383  1383 D HidProfile: Bluetooth service disconnected
,08-02 13:47:47.832  3425  3425 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-02 13:47:47.832  3425  3425 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-02 13:47:47.832  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 13:47:47.832  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:47.832  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:47.833  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-02 13:47:47.833  3425  3467 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-02 13:47:47.833  3425  3425 D PanService: Received stop request...Stopping profile...
08-02 13:47:47.834  1383  1383 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-02 13:47:47.834  1383  1383 D PanProfile: Bluetooth service disconnected
08-02 13:47:47.835  3425  3425 D BluetoothMapService: Received stop request...Stopping profile...
,08-02 13:47:47.835  3425  3425 D BluetoothMapService: stop()
08-02 13:47:47.836  3425  3425 D BluetoothMapAppObserver: deinitObservers()
08-02 13:47:47.836  3425  3425 D BluetoothMapAppObserver: removeReceiver()
08-02 13:47:47.835  3481  3481 D HeadsetProfile: Bluetooth service disconnected
08-02 13:47:47.838  1383  1383 D BluetoothMap: Proxy object disconnected
08-02 13:47:47.838  1383  1383 D MapProfile: Bluetooth service disconnected
,08-02 13:47:47.838  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.838  3425  3425 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:47.838  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:47.838  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:47.840  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 13:47:47.841  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 13:47:47.841  3425  3473 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-02 13:47:47.841  3425  3473 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 13:47:47.841  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.841  3425  3473 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 13:47:47.841  3425  3425 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:47.841  3425  3473 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 13:47:47.841  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:47.841  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:47.841  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-02 13:47:47.844  3425  3425 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-02 13:47:47.844  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:47.844  3425  3425 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-02 13:47:47.844  3425  3467 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-02 13:47:47.846  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.846  3425  3425 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:47.846  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:47.846  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:47.846  3425  3425 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-02 13:47:47.846  3425  3467 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-02 13:47:47.847  3425  3425 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-02 13:47:47.847  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.847  3425  3425 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:47.847  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:47.847  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:47.848  3425  3425 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-02 13:47:47.848  3425  3425 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-02 13:47:47.849  3425  3425 D BluetoothMapService: MAP Service closeService in
08-02 13:47:47.850  3481  3481 D DockEventReceiver: finishStartingService: stopping service
08-02 13:47:47.850  3425  3425 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:47.850  3425  3425 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:47.850  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:47.850  3425  3425 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:47.850  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-02 13:47:47.850  3425  3463 D BluetoothAdapterProperties: Setting state to 15
,08-02 13:47:47.850  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-02 13:47:47.850  3425  3425 D BluetoothMapService: cleanup()
08-02 13:47:47.850  3425  3425 D BluetoothMapService: MAP Service closeService in
08-02 13:47:47.851  3425  3463 I BluetoothAdapterState: Entering BleOnState
,08-02 13:47:47.853  3481  3910 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:47.854  1383  1383 D BluetoothPbap: Proxy object disconnected
08-02 13:47:47.854  3481  3910 D BluetoothPbap: onBluetoothStateChange: up=false
08-02 13:47:47.854  1383  1383 D PbapServerProfile: Bluetooth service disconnected
08-02 13:47:47.854  1745  3110 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-02 13:47:47.855  1383  1401 D BluetoothPan: onBluetoothStateChange on: false
,08-02 13:47:47.855  1383  1400 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 13:47:47.858   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:47.858   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:47.859  1383  1786 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:47.859  1383  1401 D BluetoothPbap: onBluetoothStateChange: up=false
08-02 13:47:47.860  3481  3491 D BluetoothPan: onBluetoothStateChange on: false
,08-02 13:47:47.860  3481  3492 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:47.861   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:47.861  3481  3910 D BluetoothMap: onBluetoothStateChange: up=false
08-02 13:47:47.861  1383  1400 D BluetoothMap: onBluetoothStateChange: up=false
08-02 13:47:47.862   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:47.862  3481  3491 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 13:47:47.862  1383  1786 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:47.863  3425  3463 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-02 13:47:47.863  3425  3463 D BluetoothAdapterProperties: Setting state to 16
08-02 13:47:47.863  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-02 13:47:47.867  3425  3463 D BluetoothAdapterProperties: onBleDisable
08-02 13:47:47.868  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-02 13:47:47.868  3425  3464 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-02 13:47:47.868  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:47.869  3425  3473 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-02 13:47:47.869  3425  3473 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:47.870  3425  3463 I BluetoothAdapterState: Entering PendingCommandState
08-02 13:47:47.870  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:47.871  3425  3467 D BluetoothAdapterProperties: Scan Mode:20
08-02 13:47:47.874  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:47.875  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:47.875  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-02 13:47:47.880  3481  3481 D DockEventReceiver: finishStartingService: stopping service
,08-02 13:47:48.071  3425  3467 I bt_hci  : shut_down
,08-02 13:47:48.073  3425  3471 D bt_hwcfg: hw_epilog_process
,08-02 13:47:48.075  3425  3471 I bt_vendor: low_power_mode_cb
,08-02 13:47:48.093  3425  3471 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-02 13:47:48.094  3425  3471 I bt_vendor: epilog_cb
08-02 13:47:48.094  3425  3471 I bt_hci  : epilog_finished_callback
,08-02 13:47:48.103  3425  3467 I bt_hci_h4: hal_close
,08-02 13:47:48.104  3425  3467 I bt_userial_vendor: device fd = 51 close
,08-02 13:47:48.224  3425  3464 D bt_stack_manager: event_shut_down_stack finished.
,08-02 13:47:48.225  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-02 13:47:48.231  3425  3425 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 13:47:48.231  3425  3463 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-02 13:47:48.233  3425  3425 D BtGatt.GattService: Received stop request...Stopping profile...
,08-02 13:47:48.233  3425  3425 D BtGatt.GattService: stop()
08-02 13:47:48.233  3425  3425 D BtGatt.AdvertiseManager: advertise clients cleared
,08-02 13:47:48.236  3425  3425 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:48.236  3425  3425 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:48.236  3425  3425 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:48.236  3425  3425 V BluetoothAdapterState: isBleTurningOff()=true
08-02 13:47:48.237  3425  3463 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-02 13:47:48.238  3425  3463 D BluetoothAdapterProperties: Setting state to 10
08-02 13:47:48.238  3425  3463 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-02 13:47:48.239  3425  3463 I BluetoothAdapterState: Entering OffState
,08-02 13:47:48.241   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-02 13:47:48.267  3425  3425 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-02 13:47:48.267  3425  3425 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-02 13:47:48.267  3425  3425 I BluetoothServiceJni: cleanupNative: return from cleanup
08-02 13:47:48.269  3425  3464 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-02 13:47:48.273  3425  3464 D bt_stack_manager: event_clean_up_stack finished.
,08-02 13:47:48.282  3425  3425 I art     : System.exit called, status: 0
08-02 13:47:48.282  3425  3425 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-02 13:47:48.339   873   883 I ActivityManager: Process com.android.bluetooth (pid 3425) has died
,08-02 13:47:48.971  3668  3698 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-02 13:47:50.715  3846  3855 W art     : Suspending all threads took: 7.735ms
,08-02 13:47:50.752  3831  3856 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-02 13:47:50.754   873  1319 D ConnectivityService: handlePromptUnvalidated 100
,08-02 13:47:50.803   873   890 I ActivityManager: Start proc 3923:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-02 13:47:50.878  3923  3923 D AdapterServiceConfig: Adding HeadsetService
,08-02 13:47:50.878  3923  3923 D AdapterServiceConfig: Adding A2dpService
08-02 13:47:50.878  3923  3923 D AdapterServiceConfig: Adding HidService
08-02 13:47:50.878  3923  3923 D AdapterServiceConfig: Adding HealthService
,08-02 13:47:50.879  3923  3923 D AdapterServiceConfig: Adding PanService
08-02 13:47:50.879  3923  3923 D AdapterServiceConfig: Adding GattService
08-02 13:47:50.879  3923  3923 D AdapterServiceConfig: Adding BluetoothMapService
,08-02 13:47:50.891  3923  3923 D BluetoothAdapterState: make() - Creating AdapterState
,08-02 13:47:50.890   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d446a4:true
,08-02 13:47:50.897  3923  3923 I bt_bluedroid: init
,08-02 13:47:50.898  3923  3935 I BluetoothAdapterState: Entering OffState
,08-02 13:47:50.903  3923  3936 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-02 13:47:50.903  3923  3936 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-02 13:47:50.903  3923  3936 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-02 13:47:50.904  3923  3936 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-02 13:47:50.905  3923  3923 I bt_bluedroid: get_profile_interface socket
,08-02 13:47:50.907  3923  3923 I bt_bluedroid: get_profile_interface sdp
,08-02 13:47:50.910  3923  3933 I bt_bluedroid: config_hci_snoop_log
,08-02 13:47:50.911  3923  3939 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-02 13:47:50.913   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-02 13:47:50.914  3923  3939 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 13:47:50.922  3923  3935 D BluetoothAdapterState: Current state: OFF, message: 0
,08-02 13:47:50.923  3923  3935 D BluetoothAdapterProperties: Setting state to 14
,08-02 13:47:50.924  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-02 13:47:50.929  3923  3935 D BluetoothBondStateMachine: make
,08-02 13:47:50.934  3923  3940 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-02 13:47:50.943  3923  3923 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-02 13:47:50.943  3923  3935 I BluetoothAdapterState: Entering PendingCommandState
08-02 13:47:50.946  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:50.947  3923  3923 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 13:47:50.947  3923  3923 D BtGatt.GattService: Received start request. Starting profile...
08-02 13:47:50.947  3923  3923 D BtGatt.GattService: start()
08-02 13:47:50.947  3923  3923 I bt_bluedroid: get_profile_interface gatt
,08-02 13:47:50.951  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:50.952  3923  3923 D BtGatt.AdvertiseManager: advertise manager created
,08-02 13:47:50.969  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:50.969  3923  3923 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:50.970  3923  3923 V BluetoothAdapterState: isBleTurningOn()=true
08-02 13:47:50.970  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:50.971  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-02 13:47:50.972  3923  3935 I bt_bluedroid: enable
,08-02 13:47:50.972  3923  3936 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-02 13:47:50.973  3923  3936 I bt_hci  : start_up
,08-02 13:47:50.991  3923  3936 I bt_vendor: alloc value 0xb3a5c189
,08-02 13:47:50.991  3923  3936 I bt_vendor: init
08-02 13:47:50.992  3923  3936 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-02 13:47:50.992  3923  3936 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-02 13:47:51.100  3923  3936 D bt_hci  : start_up starting async portion
,08-02 13:47:51.101  3923  3943 I bt_hci  : event_finish_startup
08-02 13:47:51.102  3923  3943 I bt_hci_h4: hal_open
,08-02 13:47:51.102  3923  3943 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-02 13:47:51.110  3923  3943 I bt_userial_vendor: device fd = 51 open
,08-02 13:47:51.155  3923  3943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 13:47:51.173  3923  3943 D bt_hwcfg: Chipset BCM4354A2
,08-02 13:47:51.173  3923  3943 D bt_hwcfg: Target name = [BCM4354A2]
08-02 13:47:51.174  3923  3943 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-02 13:47:51.826  3923  3943 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-02 13:47:51.828  3923  3943 D bt_hwcfg: Settlement delay -- 100 ms
08-02 13:47:51.828  3923  3943 I bt_hwcfg: Setting fw settlement delay to 100 
,08-02 13:47:51.945  3923  3943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-02 13:47:51.946  3923  3943 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-02 13:47:51.976  3923  3943 I bt_hwcfg: vendor lib fwcfg completed
,08-02 13:47:51.976  3923  3943 I bt_vendor: firmware callback
08-02 13:47:51.976  3923  3943 I bt_hci  : firmware_config_callback
,08-02 13:47:51.987  3923  3945 I bt_btu  : btu_task pending for preload complete event
,08-02 13:47:51.988  3923  3945 I bt_btu_task: Bluetooth chip preload is complete
08-02 13:47:51.988  3923  3945 I bt_btu  : btu_task received preload complete event
,08-02 13:47:51.998  3923  3945 I         : BTE_InitTraceLevels -- TRC_HCI
,08-02 13:47:51.999  3923  3945 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-02 13:47:51.999  3923  3945 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-02 13:47:51.999  3923  3945 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-02 13:47:52.000  3923  3945 I         : BTE_InitTraceLevels -- TRC_AVRC
08-02 13:47:52.000  3923  3945 I         : BTE_InitTraceLevels -- TRC_A2D
08-02 13:47:52.001  3923  3945 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-02 13:47:52.001  3923  3945 I         : BTE_InitTraceLevels -- TRC_BTM
08-02 13:47:52.001  3923  3945 I         : BTE_InitTraceLevels -- TRC_GAP
08-02 13:47:52.002  3923  3945 I         : BTE_InitTraceLevels -- TRC_PAN
08-02 13:47:52.003  3923  3945 I         : BTE_InitTraceLevels -- TRC_SDP
,08-02 13:47:52.003  3923  3945 I         : BTE_InitTraceLevels -- TRC_GATT
08-02 13:47:52.003  3923  3945 I         : BTE_InitTraceLevels -- TRC_SMP
08-02 13:47:52.004  3923  3945 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-02 13:47:52.004  3923  3945 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-02 13:47:52.135  3923  3945 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,08-02 13:47:52.136  3923  3945 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-02 13:47:52.159  3923  3939 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-02 13:47:52.162  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-02 13:47:52.163  3923  3939 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-02 13:47:52.165  3923  3939 D BluetoothAdapterProperties: Name is: Nexus 6
,08-02 13:47:52.170  3923  3939 D BluetoothAdapterProperties: Scan Mode:20
,08-02 13:47:52.171  3923  3939 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-02 13:47:52.172  3923  3939 D bt_hci  : do_postload posting postload work item
08-02 13:47:52.173  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:52.173  3923  3943 I bt_hci  : event_postload
08-02 13:47:52.173  3923  3943 I bt_vendor: sco_config_cb
08-02 13:47:52.173  3923  3943 I bt_hci  : sco_config_callback postload finished.
08-02 13:47:52.177  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:52.177  3923  3939 D bt_bte_conf: Device ID record 1 : primary
08-02 13:47:52.178  3923  3943 I bt_vendor: low_power_mode_cb
08-02 13:47:52.178  3923  3939 D bt_bte_conf:   vendorId            = 000f
08-02 13:47:52.178  3923  3939 D bt_bte_conf:   vendorIdSource      = 0001
08-02 13:47:52.179  3923  3939 D bt_bte_conf:   product             = 1200
,08-02 13:47:52.179  3923  3939 D bt_bte_conf:   version             = 1436
08-02 13:47:52.179  3923  3939 D bt_bte_conf:   clientExecutableURL = 
08-02 13:47:52.180  3923  3939 D bt_bte_conf:   serviceDescription  = 
,08-02 13:47:52.180  3923  3939 D bt_bte_conf:   documentationURL    = 
08-02 13:47:52.181  3923  3939 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-02 13:47:52.182  3923  3936 D bt_stack_manager: event_start_up_stack finished
,08-02 13:47:52.184  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-02 13:47:52.185  3923  3935 D BluetoothAdapterProperties: Setting state to 15
08-02 13:47:52.185  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-02 13:47:52.187  3923  3935 I BluetoothAdapterState: Entering BleOnState
,08-02 13:47:52.191  3923  3935 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-02 13:47:52.191  3923  3935 D BluetoothAdapterProperties: Setting state to 11
08-02 13:47:52.191  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-02 13:47:52.202  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:52.203  3923  3923 D HeadsetService: Received start request. Starting profile...
,08-02 13:47:52.206  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:52.212  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:52.212  3923  3923 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-02 13:47:52.213  3923  3923 D HeadsetStateMachine: make
,08-02 13:47:52.219  3923  3935 I BluetoothAdapterState: Entering PendingCommandState
,08-02 13:47:52.224  3923  3923 D HeadsetStateMachine: max_hf_connections = 1
08-02 13:47:52.224  3923  3923 I bt_bluedroid: get_profile_interface handsfree
,08-02 13:47:52.224  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-02 13:47:52.225  3923  3939 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-02 13:47:52.228  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
08-02 13:47:52.228  3923  3923 D A2dpService: Received start request. Starting profile...
08-02 13:47:52.229  3923  3923 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-02 13:47:52.229  3923  3923 I bt_bluedroid: get_profile_interface avrcp
,08-02 13:47:52.235  3923  3923 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-02 13:47:52.235  3923  3923 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-02 13:47:52.235  3923  3923 D A2dpStateMachine: make
,08-02 13:47:52.237  3923  3923 I bt_bluedroid: get_profile_interface a2dp
,08-02 13:47:52.238  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-02 13:47:52.239  3923  3955 D A2dpStateMachine: Enter Disconnected: -2
08-02 13:47:52.240  3923  3923 I BluetoothHidServiceJni: classInitNative: succeeds
08-02 13:47:52.240  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
08-02 13:47:52.241  3923  3923 D HidService: Received start request. Starting profile...
08-02 13:47:52.241  3923  3923 I bt_bluedroid: get_profile_interface hidhost
,08-02 13:47:52.241  3923  3939 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
08-02 13:47:52.242  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-02 13:47:52.242  3923  3923 D HidService: setHidService(): set to: null
,08-02 13:47:52.243  3923  3923 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-02 13:47:52.244  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:52.245  3923  3923 D HealthService: Received start request. Starting profile...
,08-02 13:47:52.246  3923  3923 I bt_bluedroid: get_profile_interface health
,08-02 13:47:52.247  3923  3923 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-02 13:47:52.248  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
,08-02 13:47:52.249  3923  3923 D PanService: Received start request. Starting profile...
08-02 13:47:52.249  3923  3923 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-02 13:47:52.249  3923  3923 I bt_bluedroid: get_profile_interface pan
,08-02 13:47:52.250  3923  3939 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-02 13:47:52.253  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35f3b8d
08-02 13:47:52.253   873  1392 I ActivityManager: Killing 2573:com.android.vending/u0a19 (adj 15): empty #17
08-02 13:47:52.253  3923  3923 D BluetoothMapService: Received start request. Starting profile...
08-02 13:47:52.253  3923  3923 D BluetoothMapService: start()
,08-02 13:47:52.303  3923  3923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-02 13:47:52.304  3923  3923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-02 13:47:52.304  3923  3923 D BluetoothMapAppObserver: createReceiver()
,08-02 13:47:52.305  3923  3923 D BluetoothMapAppObserver: initObservers()
,08-02 13:47:52.305  3923  3923 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-02 13:47:52.313  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:52.313  3923  3923 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:52.313  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.313  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.313  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:52.319  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:52.319  3923  3953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.320  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isTurningOff()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isTurningOn()=true
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:52.321  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:52.322  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-02 13:47:52.322  3923  3935 D BluetoothAdapterProperties: ScanMode =  20
08-02 13:47:52.322  3923  3935 D BluetoothAdapterProperties: State =  11
,08-02 13:47:52.322  3923  3935 D BluetoothAdapterProperties: Setting state to 12
08-02 13:47:52.322  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-02 13:47:52.323  3923  3935 I BluetoothAdapterState: Entering OnState
,08-02 13:47:52.324  3923  3939 D BluetoothAdapterProperties: Scan Mode:21
,08-02 13:47:52.324  3923  3939 D BluetoothAdapterProperties: Discoverable Timeout:120
08-02 13:47:52.325  3481  3491 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:52.326  3481  3492 D BluetoothPbap: onBluetoothStateChange: up=true
08-02 13:47:52.330  3923  3923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:52.330  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:52.331  3923  3923 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-02 13:47:52.335  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:52.337  3923  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 13:47:52.340  1745  3110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:52.342  3923  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 13:47:52.343  1383  1401 D BluetoothPan: onBluetoothStateChange on: true
08-02 13:47:52.343  3923  3923 D ObexServerSockets: Succeed to create listening sockets 
08-02 13:47:52.344  3923  3923 D ObexServerSockets0: startAccept()
08-02 13:47:52.344  3923  3923 D ObexServerSockets0: prepareForNewConnect()
,08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:52.348  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-02 13:47:52.349  1383  1400 D BluetoothInputDevice: onBluetoothStateChange: up=true,
08-02 13:47:52.349  3923  3923 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-02 13:47:52.349  3923  3923 D BluetoothSdpJni: SDP Create record success - handle: 0
08-02 13:47:52.351  3923  3960 D ObexServerSockets0: Accepting socket connection...
08-02 13:47:52.351  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:52.352  3923  3961 D ObexServerSockets0: Accepting socket connection...
,08-02 13:47:52.352  1383  1383 D BluetoothPan: BluetoothPAN Proxy object connected
,08-02 13:47:52.353  1383  1383 D PanProfile: Bluetooth service connected
08-02 13:47:52.353  1383  1383 D BluetoothInputDevice: Proxy object connected
08-02 13:47:52.353  1383  1383 D HidProfile: Bluetooth service connected
,08-02 13:47:52.353   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:52.354   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-02 13:47:52.355  1383  1786 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-02 13:47:52.356   873   873 D BluetoothA2dp: Proxy object connected
,08-02 13:47:52.358  1383  1383 D BluetoothA2dp: Proxy object connected
,08-02 13:47:52.358  1383  1400 D BluetoothPbap: onBluetoothStateChange: up=true
,08-02 13:47:52.360  3481  3910 D BluetoothPan: onBluetoothStateChange on: true
,08-02 13:47:52.361  3481  3492 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-02 13:47:52.361  3481  3481 D BluetoothPan: BluetoothPAN Proxy object connected
,08-02 13:47:52.361  3481  3481 D PanProfile: Bluetooth service connected
,08-02 13:47:52.362   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:52.362  3481  3481 D BluetoothA2dp: Proxy object connected
08-02 13:47:52.363  3481  3910 D BluetoothMap: onBluetoothStateChange: up=true
,08-02 13:47:52.367  1383  1401 D BluetoothMap: onBluetoothStateChange: up=true
,08-02 13:47:52.368  3481  3481 D BluetoothMap: Proxy object connected
08-02 13:47:52.368  3481  3481 D MapProfile: Bluetooth service connected
08-02 13:47:52.368  3481  3481 D BluetoothMap: getConnectedDevices()
,08-02 13:47:52.371  1383  1383 D BluetoothMap: Proxy object connected
,08-02 13:47:52.371  1383  1383 D MapProfile: Bluetooth service connected
,08-02 13:47:52.371  1383  1383 D BluetoothMap: getConnectedDevices()
,08-02 13:47:52.372   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-02 13:47:52.373  3481  3491 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-02 13:47:52.375  3481  3481 D BluetoothInputDevice: Proxy object connected
,08-02 13:47:52.375  1383  1400 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-02 13:47:52.375  3481  3481 D HidProfile: Bluetooth service connected
08-02 13:47:52.377   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-02 13:47:52.378  3923  3923 D BluetoothMapService: onReceive
08-02 13:47:52.378  3923  3923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-02 13:47:52.379  3923  3923 D BluetoothMapService: STATE_ON
08-02 13:47:52.381  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:52.383  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:52.387  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 13:47:52.402  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:52.403  3481  3481 D DockEventReceiver: finishStartingService: stopping service
,08-02 13:47:52.404  3923  3923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-02 13:47:52.404  3923  3923 D ObexServerSockets0: prepareForNewConnect()
08-02 13:47:52.404  3481  3481 D BluetoothPbap: Proxy object connected
08-02 13:47:52.404  3481  3481 D PbapServerProfile: Bluetooth service connected
,08-02 13:47:52.407  1383  1383 D BluetoothPbap: Proxy object connected
08-02 13:47:52.407  1383  1383 D PbapServerProfile: Bluetooth service connected
,08-02 13:47:52.411  3923  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-02 13:47:52.451  1745  1765 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.451   873   873 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.451  3481  3491 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.452  1383  1400 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.452  1383  1383 D HeadsetProfile: Bluetooth service connected
08-02 13:47:52.452   873   873 D BluetoothHeadset: Proxy object connected
08-02 13:47:52.452   873   873 D BluetoothHeadset: Proxy object connected
08-02 13:47:52.454  3481  3481 D HeadsetProfile: Bluetooth service connected
,08-02 13:47:52.455   873   890 D BluetoothHeadset: Proxy object connected
08-02 13:47:52.457  3923  3970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-02 13:47:52.458  3923  3970 I BtOppRfcommListener: Accept thread started.
,08-02 13:47:52.463   873   890 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.472   873   890 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.475  1383  1786 D BluetoothHeadset: Proxy object connected
,08-02 13:47:52.475  1383  1383 D HeadsetProfile: Bluetooth service connected
,08-02 13:47:53.783  3372  3419 D io.jxcore.node.ConnectivityMonitor: stop
,08-02 13:47:53.784  3372  3419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-02 13:47:54.035   873  2844 I ActivityManager: Start proc 3973:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,08-02 13:47:54.179  3973  3973 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-02 13:47:54.261  1524  1905 I art     : Waiting for a blocking GC DisableMovingGc
,08-02 13:47:54.284  1524  1905 I art     : WaitForGcToComplete blocked for 23.004ms for cause DisableMovingGc
,08-02 13:47:54.284  1524  1905 I art     : Starting a blocking GC DisableMovingGc
,08-02 13:47:54.360  3973  3973 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-02 13:47:54.425  3973  3973 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-02 13:47:54.439  3973  3973 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-02 13:47:54.441  3973  3973 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-02 13:47:54.502   873  1393 I ActivityManager: Killing 3576:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-02 13:47:54.518  3973  3983 D Finsky  : [324] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-02 13:47:54.601  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:54.616  3973  4007 D Ads     : Skipping gmscore version check
,08-02 13:47:54.623  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:54.626  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:54.632  3973  4007 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-02 13:47:54.660  3973  3973 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-02 13:47:54.661  3973  3973 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,08-02 13:47:54.667  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:47:54.667  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:47:54.667  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:47:54.667  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-02 13:47:54.672  3973  3973 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-02 13:47:54.693  3973  3973 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-02 13:47:54.711  3973  3983 D Finsky  : [324] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-02 13:47:56.792  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 13:47:56.792  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86dc650 added. We now have 6 listener(s)
,08-02 13:47:56.793  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 13:47:56.800  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-02 13:47:56.800  3372  3419 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0a0049 added. We now have 7 listener(s)
08-02 13:47:56.801  3372  3419 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-02 13:47:56.804  3372  3419 I System.out: IsBluetoothEnabled
,08-02 13:47:56.814  3923  3935 D BluetoothAdapterState: Current state: ON, message: 23
,08-02 13:47:56.814  3923  3935 D BluetoothAdapterProperties: Setting state to 13
,08-02 13:47:56.815  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-02 13:47:56.816  3923  3935 D BluetoothAdapterProperties: onBluetoothDisable()
,08-02 13:47:56.821  3923  3935 I BluetoothAdapterState: Entering PendingCommandState
,08-02 13:47:56.829  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:56.830  3372  3419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:56.832  3923  3939 D BluetoothAdapterProperties: Scan Mode:20
08-02 13:47:56.832  3923  3923 D BluetoothMapService: onReceive
,08-02 13:47:56.833  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-02 13:47:56.833  3923  3923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-02 13:47:56.833  3923  3923 D BluetoothMapService: STATE_TURNING_OFF
08-02 13:47:56.835  3923  3923 D BluetoothMapService: MAP Service closeService in
08-02 13:47:56.835  3923  3923 D BluetoothMapMasInstance0: MAP Service shutdown
08-02 13:47:56.836  3923  3923 D ObexServerSockets0: shutdown(block = true)
,08-02 13:47:56.836  3923  3960 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-02 13:47:56.837  3923  3923 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 13:47:56.837  3923  3923 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-02 13:47:56.837  3923  3948 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-02 13:47:56.838  3372  3419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 13:47:56.838  3372  3419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:56.838  3923  3961 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-02 13:47:56.839  3923  3923 I BtOppRfcommListener: stopping Accept Thread
08-02 13:47:56.840  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-02 13:47:56.840  3372  3372 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-02 13:47:56.840  3923  3970 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-02 13:47:56.841  3372  3372 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-02 13:47:56.841  3372  3372 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-02 13:47:56.841  3923  3970 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-02 13:47:56.843  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:56.847  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 13:47:56.852  3923  3923 D HeadsetService: Received stop request...Stopping profile...
,08-02 13:47:56.854  3973  3973 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-02 13:47:56.858  1745  1765 D BluetoothHeadset: Proxy object disconnected
,08-02 13:47:56.858   873   873 D BluetoothHeadset: Proxy object disconnected
,08-02 13:47:56.859  3481  3910 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:56.859  1383  1400 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:56.859   873   873 D BluetoothHeadset: Proxy object disconnected
,08-02 13:47:56.859   873   873 D BluetoothHeadset: Proxy object disconnected
08-02 13:47:56.861  3923  3923 D A2dpService: Received stop request...Stopping profile...
08-02 13:47:56.861  3923  3955 D A2dpStateMachine: Exit Disconnected: -1
08-02 13:47:56.862   873   873 D BluetoothA2dp: Proxy object disconnected
,08-02 13:47:56.863  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.863  3923  3923 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:56.863  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.863  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:56.864  3923  3923 D HidService: Received stop request...Stopping profile...
08-02 13:47:56.864  3923  3923 D HidService: Stopping Bluetooth HidService
08-02 13:47:56.865  1383  1383 D HeadsetProfile: Bluetooth service disconnected
,08-02 13:47:56.865  1383  1383 D BluetoothA2dp: Proxy object disconnected
,08-02 13:47:56.869  1383  1383 D BluetoothInputDevice: Proxy object disconnected
,08-02 13:47:56.869  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-02 13:47:56.869  1383  1383 D HidProfile: Bluetooth service disconnected
,08-02 13:47:56.869  3923  3935 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-02 13:47:56.870  3923  3923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-02 13:47:56.870  3923  3923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-02 13:47:56.870  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-02 13:47:56.871  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:56.871  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:56.871  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:56.871  3923  3939 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-02 13:47:56.871  3923  3923 D HealthService: Received stop request...Stopping profile...
,08-02 13:47:56.875  3481  3481 D DockEventReceiver: finishStartingService: stopping service
,08-02 13:47:56.876  3481  3481 D HeadsetProfile: Bluetooth service disconnected
08-02 13:47:56.876  3481  3481 D BluetoothA2dp: Proxy object disconnected
08-02 13:47:56.877  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-02 13:47:56.877  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.877  3923  3923 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:56.877  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.877  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,08-02 13:47:56.877  3481  3481 D BluetoothInputDevice: Proxy object disconnected
08-02 13:47:56.878  3923  3923 D PanService: Received stop request...Stopping profile...
08-02 13:47:56.878  3481  3481 D HidProfile: Bluetooth service disconnected
08-02 13:47:56.879  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-02 13:47:56.881  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.881  3923  3923 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:56.881  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.881  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-02 13:47:56.881  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:56.881  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:56.881  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000,
08-02 13:47:56.881  3923  3945 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 13:47:56.881  3923  3923 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-02 13:47:56.881  3923  3945 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-02 13:47:56.881  3923  3945 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-02 13:47:56.881  3923  3923 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-02 13:47:56.881  3923  3945 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-02 13:47:56.882  3923  3923 D BluetoothMapService: Received stop request...Stopping profile...
,08-02 13:47:56.882  3923  3923 D BluetoothMapService: stop()
,08-02 13:47:56.882  3923  3939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-02 13:47:56.883  3923  3923 D BluetoothMapAppObserver: deinitObservers()
,08-02 13:47:56.883  3923  3923 D BluetoothMapAppObserver: removeReceiver()
08-02 13:47:56.884  3481  3481 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-02 13:47:56.885  3481  3481 D PanProfile: Bluetooth service disconnected
08-02 13:47:56.883  1383  1383 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-02 13:47:56.885  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.885  1383  1383 D PanProfile: Bluetooth service disconnected
08-02 13:47:56.885  3923  3923 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:56.885  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.885  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:56.885  1383  1383 D BluetoothMap: Proxy object disconnected
,08-02 13:47:56.885  3481  3481 D BluetoothMap: Proxy object disconnected
08-02 13:47:56.885  3481  3481 D MapProfile: Bluetooth service disconnected
,08-02 13:47:56.885  1383  1383 D MapProfile: Bluetooth service disconnected
08-02 13:47:56.885  3923  3923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-02 13:47:56.885  3923  3939 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-02 13:47:56.887  3923  3923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-02 13:47:56.888  3481  3481 D BluetoothPbap: Proxy object disconnected
,08-02 13:47:56.889  3481  3481 D PbapServerProfile: Bluetooth service disconnected
08-02 13:47:56.889  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.889  3923  3923 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:56.889  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.889  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:56.889  3923  3923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-02 13:47:56.889  3923  3923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-02 13:47:56.891  3923  3923 D BluetoothMapService: MAP Service closeService in
08-02 13:47:56.891  3923  3923 V BluetoothAdapterState: isTurningOff()=true
08-02 13:47:56.891  3923  3923 V BluetoothAdapterState: isTurningOn()=false
08-02 13:47:56.891  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
08-02 13:47:56.891  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
08-02 13:47:56.891  1383  1383 D BluetoothPbap: Proxy object disconnected
,08-02 13:47:56.891  1383  1383 D PbapServerProfile: Bluetooth service disconnected
08-02 13:47:56.892  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-02 13:47:56.892  3923  3935 D BluetoothAdapterProperties: Setting state to 15
08-02 13:47:56.892  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-02 13:47:56.892  3923  3935 I BluetoothAdapterState: Entering BleOnState
08-02 13:47:56.892  3923  3935 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-02 13:47:56.893  3923  3923 D BluetoothMapService: cleanup()
08-02 13:47:56.893  3923  3923 D BluetoothMapService: MAP Service closeService in
08-02 13:47:56.896  3481  3491 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:56.897  3481  3492 D BluetoothPbap: onBluetoothStateChange: up=false
,08-02 13:47:56.899  1745  1919 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:56.900  1383  1401 D BluetoothPan: onBluetoothStateChange on: false
08-02 13:47:56.900  1383  1400 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-02 13:47:56.901   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:56.901   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:56.901  1383  1786 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:56.902  1383  1401 D BluetoothPbap: onBluetoothStateChange: up=false
,08-02 13:47:56.902  3481  3910 D BluetoothPan: onBluetoothStateChange on: false
08-02 13:47:56.903  3481  3491 D BluetoothA2dp: onBluetoothStateChange: up=false
08-02 13:47:56.903   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:56.903  3481  3492 D BluetoothMap: onBluetoothStateChange: up=false
08-02 13:47:56.905  1383  1400 D BluetoothMap: onBluetoothStateChange: up=false
08-02 13:47:56.905   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-02 13:47:56.906  3481  3910 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-02 13:47:56.906  1383  1786 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-02 13:47:56.906  3923  3935 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-02 13:47:56.907  3923  3935 D BluetoothAdapterProperties: Setting state to 16
08-02 13:47:56.907  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-02 13:47:56.908  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-02 13:47:56.908  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-02 13:47:56.908  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:56.908  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-02 13:47:56.909  3923  3935 D BluetoothAdapterProperties: onBleDisable
08-02 13:47:56.909  3923  3935 I BluetoothAdapterState: Entering PendingCommandState
08-02 13:47:56.909  3923  3936 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-02 13:47:56.910  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-02 13:47:56.910  3923  3945 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-02 13:47:56.910  3923  3945 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-02 13:47:56.911  3923  3939 D BluetoothAdapterProperties: Scan Mode:20
08-02 13:47:56.913  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-02 13:47:56.914  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:56.921  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:56.928  3481  3481 D DockEventReceiver: finishStartingService: stopping service
08-02 13:47:56.930  3973  3973 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:47:56.938  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:56.952  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:47:56.952  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:47:56.952  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:56.952  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:56.985  3973  4018 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-02 13:47:56.985  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:56.988  3973  3973 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-02 13:47:56.989  3973  3973 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,08-02 13:47:57.011  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:47:57.011  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:47:57.011  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:47:57.011  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:57.026  3973  3973 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:47:57.114  3923  3939 I bt_hci  : shut_down
,08-02 13:47:57.115  3923  3943 D bt_hwcfg: hw_epilog_process
,08-02 13:47:57.124  3923  3943 I bt_vendor: low_power_mode_cb
,08-02 13:47:57.144  3923  3943 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-02 13:47:57.144  3923  3943 I bt_vendor: epilog_cb
,08-02 13:47:57.144  3923  3943 I bt_hci  : epilog_finished_callback
,08-02 13:47:57.150  3923  3939 I bt_hci_h4: hal_close
,08-02 13:47:57.151  3923  3939 I bt_userial_vendor: device fd = 51 close
,08-02 13:47:57.183  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:47:57.226  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:47:57.226  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-02 13:47:57.226  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:47:57.227  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:47:57.261  3973  3973 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:47:57.262  3973  3973 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-02 13:47:57.265  3973  3973 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-02 13:47:57.269  3973  3973 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,08-02 13:47:57.270  3923  3936 D bt_stack_manager: event_shut_down_stack finished.
08-02 13:47:57.272  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24,
,08-02 13:47:57.280  3923  3935 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-02 13:47:57.280  3923  3923 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-02 13:47:57.281  3923  3923 D BtGatt.GattService: Received stop request...Stopping profile...
,08-02 13:47:57.281  3923  3923 D BtGatt.GattService: stop()
08-02 13:47:57.282  3923  3923 D BtGatt.AdvertiseManager: advertise clients cleared
,08-02 13:47:57.286  3973  4020 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-02 13:47:57.286  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,08-02 13:47:57.287  3923  3923 V BluetoothAdapterState: isTurningOn()=false
,08-02 13:47:57.287  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,08-02 13:47:57.287  3923  3923 V BluetoothAdapterState: isBleTurningOff()=true
,08-02 13:47:57.288  3923  3935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-02 13:47:57.288  3923  3935 D BluetoothAdapterProperties: Setting state to 10
08-02 13:47:57.288  3923  3935 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-02 13:47:57.289  3923  3935 I BluetoothAdapterState: Entering OffState
08-02 13:47:57.294  3372  3372 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-02 13:47:57.298  3481  3481 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-02 13:47:57.306  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-02 13:47:57.306  3481  3481 D DockEventReceiver: finishStartingService: stopping service
,08-02 13:47:58.539   873  1859 I ActivityManager: Killing 3668:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-02 13:48:16.484  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:16.491  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:16.496  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:16.531  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:48:16.532  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:48:16.532  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:48:16.532  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:48:16.564  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-02 13:48:16.568  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 13:48:16.571  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-02 13:48:26.614  1668  1721 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-02 13:48:26.615  1668  1721 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-02 13:48:26.669  1524  1524 I ConfigService: onCreate
,08-02 13:48:31.762  1524  1524 I ConfigService: onDestroy
,08-02 13:48:44.918   873  1319 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-02 13:48:49.974  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:49.986  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:49.990  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:48:50.036  1524  2678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:48:50.037  1524  2678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:48:50.037  1524  2678 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:48:50.038  1524  2678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:48:50.084  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:48:50.084  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-02 13:48:50.084  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-02 13:49:10.439  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:10.459  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:10.466  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:10.557  1524  2678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:49:10.558  1524  2678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:49:10.558  1524  2678 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:49:10.559  1524  2678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:49:10.629  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:49:10.630  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-02 13:49:10.631  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-02 13:49:31.000  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:31.012  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:31.017  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:31.104  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:49:31.105  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:49:31.105  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:49:31.106  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:49:31.174  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:49:31.177  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 13:49:31.181  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-02 13:49:57.203  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:57.220  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:57.227  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:49:57.294  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:49:57.294  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:49:57.295  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:49:57.295  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:49:57.342  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:49:57.343  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-02 13:49:57.344  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-02 13:50:16.602  1524  2001 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-02 13:50:17.699  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:50:17.717  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:50:17.723  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:50:17.800  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:50:17.801  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-02 13:50:17.802  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:50:17.803  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:50:17.860  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:50:17.861  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-02 13:50:17.862  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-02 13:52:54.556  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:52:54.569  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:52:54.571  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:52:54.636  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:52:54.636  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:52:54.637  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:52:54.637  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:52:54.683  1524  3058 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 13:52:54.683  1524  3058 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 13:52:54.699  3973  4002 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 13:52:54.699  3973  4002 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 13:52:54.699  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 13:52:54.699  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 13:52:54.699  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 13:52:54.699  3973  4002 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 13:52:54.699  3973  4002 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 13:54:54.724  1524  2001 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-02 13:57:54.879  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:57:54.888  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:57:54.891  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:57:54.947  1524  2678 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:57:54.948  1524  2678 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:57:54.948  1524  2678 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:57:54.948  1524  2678 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:57:54.976  1524  2678 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 13:57:54.976  1524  2678 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 13:57:54.982  3973  4002 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 13:57:54.982  3973  4002 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 13:57:54.982  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 13:57:54.982  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 13:57:54.982  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 13:57:54.982  3973  4002 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 13:57:54.982  3973  4002 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 13:58:26.110  3973  3973 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-02 13:58:26.134  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:26.152  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:26.158  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:26.204  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:58:26.204  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:58:26.204  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:58:26.204  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:58:26.245  3973  3973 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:58:26.265  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:26.348  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:58:26.349  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:58:26.349  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:58:26.349  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:58:26.454  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:26.547  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:58:26.548  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 13:58:26.548  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:58:26.549  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:58:26.623  3973  3973 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:58:27.012  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:27.049  1524  3182 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 13:58:27.049  1524  3182 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-02 13:58:27.049  1524  3182 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:58:27.050  1524  3182 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:58:27.084  3973  3973 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-02 13:58:27.085  3973  3973 D Finsky  : [1] WearSupportService.startHygiene: disabled
08-02 13:58:27.086  3973  3973 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-02 13:58:27.094  3973  4018 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438,
,08-02 13:58:27.097  3973  3973 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,08-02 13:58:41.883  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:41.901  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:41.906  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:58:41.971  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:58:41.971  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-02 13:58:41.972  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:58:41.972  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:58:42.027  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:58:42.031  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 13:58:42.035  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-02 13:59:02.320  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:02.329  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:02.333  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:02.380  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:59:02.380  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:59:02.380  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:59:02.381  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:59:02.425  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:59:02.426  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 13:59:02.427  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-02 13:59:22.686  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:22.703  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:22.710  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:22.784  1524  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:59:22.785  1524  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-02 13:59:22.785  1524  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 13:59:22.785  1524  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:59:22.841  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 13:59:22.842  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 13:59:22.844  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-02 13:59:43.181  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:43.200  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:43.207  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 13:59:43.289  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 13:59:43.290  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 13:59:43.290  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 13:59:43.291  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 13:59:43.355  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-02 13:59:43.357  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-02 13:59:43.358  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-02 14:00:03.927  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:03.941  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:03.947  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:03.988  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-02 14:00:03.989  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-02 14:00:03.989  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 14:00:03.989  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 14:00:04.024  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-02 14:00:04.024  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 14:00:04.025  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-02 14:00:24.358  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:24.377  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:24.385  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:00:24.475  1524  1905 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-02 14:00:24.476  1524  1905 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-02 14:00:24.476  1524  1905 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 14:00:24.476  1524  1905 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 14:00:24.548  3973  3973 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-02 14:00:24.549  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-02 14:00:24.550  3973  3973 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-02 14:02:13.338   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-02 14:02:55.121  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:02:55.148  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:02:55.156  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:02:55.249  1524  3344 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 14:02:55.249  1524  3344 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 14:02:55.249  1524  3344 I GLSUser : [GLSUser] Extracting token using key: Auth
08-02 14:02:55.250  1524  3344 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 14:02:55.294  1524  3344 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 14:02:55.294  1524  3344 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 14:02:55.309  3973  4002 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 14:02:55.309  3973  4002 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 14:02:55.309  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 14:02:55.309  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 14:02:55.309  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 14:02:55.309  3973  4002 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 14:02:55.309  3973  4002 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 14:07:55.428  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:07:55.442  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:07:55.447  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-02 14:07:55.491  1524  3058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-02 14:07:55.491  1524  3058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-02 14:07:55.491  1524  3058 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-02 14:07:55.491  1524  3058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-02 14:07:55.519  1524  3058 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-02 14:07:55.519  1524  3058 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-02 14:07:55.524  3973  4002 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-02 14:07:55.524  3973  4002 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-02 14:07:55.524  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-02 14:07:55.524  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-02 14:07:55.524  3973  4002 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-02 14:07:55.524  3973  4002 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-02 14:07:55.524  3973  4002 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-02 14:10:56.913  4104  4104 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-02 14:10:56.918  4104  4104 D AndroidRuntime: CheckJNI is OFF
08-02 14:10:56.953  4104  4104 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-02 14:10:56.994  4104  4104 I Radio-JNI: register_android_hardware_Radio DONE
08-02 14:10:57.015  4104  4104 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-02 14:10:57.029   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-02 14:10:57.030   873   886 I ActivityManager: Killing 3372:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-02 14:10:57.127   873  1393 D GraphicsStats: Buffer count: 2
08-02 14:10:57.130   873  1859 I WindowState: WIN DEATH: Window{1c9ca59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-02 14:10:57.129   873  1318 D WifiService: Client connection lost with reason: 4
08-02 14:10:57.143   873   896 W PackageSettings: Skipping PackageSetting{26cfd86 com.example.hello/10273} due to missing metadata
08-02 14:10:57.171   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-02 14:10:57.172   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-02 14:10:57.173   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-02 14:10:57.173   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-02 14:10:57.173   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.173   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.173   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.173   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-02 14:10:57.174   873   886 I ActivityManager:   Force finishing activity ActivityRecord{83d2aca u0 com.test.thalitest/.MainActivity t2}
08-02 14:10:57.178   873   896 I art     : Starting a blocking GC Explicit
08-02 14:10:57.190   873  2844 W ActivityManager: Spurious death for ProcessRecord{a31a554 0:com.test.thalitest/u0a0}, curProc for 3372: null
08-02 14:10:57.222   873   896 I art     : Explicit concurrent mark sweep GC freed 39708(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 690us total 43.467ms
08-02 14:10:57.274   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-02 14:10:57.277  4104  4104 I art     : System.exit called, status: 0
08-02 14:10:57.277  4104  4104 I AndroidRuntime: VM exiting with result code 0.
08-02 14:10:57.308   873   896 I ActivityManager: Start proc 4117:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-02 14:10:57.309   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-02 14:10:57.358   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-02 14:10:57.369  1887  2025 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-02 14:10:57.379   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-02 14:10:57.382  1668  1668 I Keyboard.Facilitator: resetDictionaries() : en_US
08-02 14:10:57.387  3219  3219 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-02 14:10:57.390  1668  4131 I Keyboard.Facilitator.DecoderInitializer: run()
08-02 14:10:57.392  1668  4131 I Decoder : createOrResetDecoder
08-02 14:10:57.420   873  1841 I ActivityManager: Start proc 4134:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-02 14:10:57.438  1745  1745 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-02 14:10:57.451   873   884 I ActivityManager: Killing 3880:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-02 14:10:57.460   873  1704 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3372 uid 10000
08-02 14:10:57.461  1668  1668 I Keyboard.Facilitator: onFinishInput()
08-02 14:10:57.468  4134  4134 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-02 14:10:57.481   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-02 14:10:57.490  1524  1524 I ConfigService: onCreate
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-02 14:10:57.496  1524  4146 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-02 14:10:57.497  1524  4146 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-02 14:10:57.501  1524  4146 W SQLiteOpenHelper: Opened config.db in read-only mode
08-02 14:10:57.508  1759  1837 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-02 14:10:57.511   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-02 14:10:57.512   873   885 E PackageManager: Failed to write settings, restoring backup
08-02 14:10:57.512   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-02 14:10:57.512   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-02 14:10:57.512   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-02 14:10:57.512   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-02 14:10:57.512   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-02 14:10:57.512   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.512   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.512   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.516   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-02 14:10:57.516   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-02 14:10:57.516   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 14:10:57.516   873   886 E DropBoxManagerService: 	... 13 more
08-02 14:10:57.521   873   883 I ActivityManager: Start proc 4150:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-02 14:10:57.522  1759  1837 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-02 14:10:57.522  1759  1837 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1759
08-02 14:10:57.522  1759  1837 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.522  1759  1837 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.524   873  1859 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 14:10:57.524   873  4156 E DropBoxManagerService: Can't write: system_app_crash
08-02 14:10:57.524   873  4156 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 14:10:57.524   873  4156 E DropBoxManagerService: 	... 5 more
08-02 14:10:57.529  1759  1837 I Process : Sending signal. PID: 1759 SIG: 9
08-02 14:10:57.537  1668  4131 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-02 14:10:57.545  4134  4134 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-02 14:10:57.566  4134  4164 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-02 14:10:57.571   873  1859 I ActivityManager: Start proc 4165:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-02 14:10:57.576  1668  4131 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-02 14:10:57.602  4165  4165 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-02 14:10:57.577  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-02 14:10:57.605  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-02 14:10:57.607  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-02 14:10:57.607  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-02 14:10:57.619  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-02 14:10:57.619  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-02 14:10:57.620  1668  4131 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-02 14:10:57.621  1668  4131 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-02 14:10:57.621  1668  4131 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-02 14:10:57.622  1668  4131 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-02 14:10:57.622  1668  4131 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-02 14:10:57.631  1668  4131 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-02 14:10:57.638   873  1304 W InputDispatcher: channel '8165f1e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-02 14:10:57.638   873  1304 E InputDispatcher: channel '8165f1e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-02 14:10:57.639   873  1784 D GraphicsStats: Buffer count: 1
08-02 14:10:57.639   873  1784 I WindowState: WIN DEATH: Window{8165f1e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-02 14:10:57.639   873  1784 W InputDispatcher: Attempted to unregister already unregistered input channel '8165f1e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-02 14:10:57.648  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-02 14:10:57.648  1524  1524 D AndroidRuntime: Shutting down VM
08-02 14:10:57.649  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
08-02 14:10:57.649  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
08-02 14:10:57.649  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-02 14:10:57.649  1524  1524 E AndroidRuntime: 	... 8 more
08-02 14:10:57.655   873  1841 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1759) has died
08-02 14:10:57.657   873  1841 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-02 14:10:57.658   873  1841 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.674  4134  4148 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.675  4134  4148 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.680   873   886 I ActivityManager: Start proc 4183:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-02 14:10:57.688  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
08-02 14:10:57.688   873  4189 E DropBoxManagerService: Can't write: system_app_crash
08-02 14:10:57.688   873  4189 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 14:10:57.688   873  4189 E DropBoxManagerService: 	... 5 more
08-02 14:10:57.704   873   884 I ActivityManager: Killing 3597:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-02 14:10:57.733  4183  4183 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-02 14:10:57.734  4183  4183 D AndroidRuntime: Shutting down VM
08-02 14:10:57.736  4134  4148 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.741  4134  4164 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-02 14:10:57.742  4134  4164 E AndroidRuntime: Process: android.process.acore, PID: 4134
08-02 14:10:57.742  4134  4164 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-02 14:10:57.742  4134  4164 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-02 14:10:57.742  4134  4148 I Process : Sending signal. PID: 4134 SIG: 9
08-02 14:10:57.746   873  1318 D WifiService: Client connection lost with reason: 4
08-02 14:10:57.759  1977  1977 W RocketImpressions: ClearcutLogger connection suspended: 1
08-02 14:10:57.763   873  4197 E DropBoxManagerService: Can't write: system_app_crash
08-02 14:10:57.763   873  4197 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-02 14:10:57.763   873  4197 E DropBoxManagerService: 	... 5 more
08-02 14:10:57.764   279   279 E lowmemorykiller: Error writing /proc/4134/oom_score_adj; errno=22
08-02 14:10:57.765   873  2844 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
08-02 14:10:57.765   873  2844 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-02 14:10:57.766   873  2844 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-02 14:10:57.766   873  2844 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-02 14:10:57.766   873  2844 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 31000ms
08-02 14:10:57.767   279   279 E lowmemorykiller: Error writing /proc/4134/oom_score_adj; errno=22
08-02 14:10:57.767   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
